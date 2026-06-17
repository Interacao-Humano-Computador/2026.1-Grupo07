<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DICOM AI Viewer - Protótipo</title>
<script src="https://cdn.tailwindcss.com"></script>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#050505;color:#e5e5e5;font-family:"Courier New",monospace;overflow:hidden}
.toolbar{height:60px;background:#111;border-bottom:1px solid #333;display:flex;align-items:center;gap:10px;padding:10px 20px}
.tool{width:42px;height:42px;background:#111;border:1px solid #555;border-radius:6px;color:white;font-size:18px;cursor:pointer;transition:.2s}
.tool:hover{background:#333}.tool.active{background:#2563eb;border-color:#3b82f6}.info-top{margin-left:20px;color:#888;font-size:12px}
.main{display:flex;height:calc(100vh - 60px)}
.viewer{flex:1;background:black;position:relative;display:flex;justify-content:center;align-items:center;overflow:hidden}
.viewport{position:relative;width:100%;height:100%;transform-origin:center center;will-change:transform;cursor:grab}
.viewport.grabbing{cursor:grabbing}
.layer{position:absolute;inset:0;width:100%;height:100%;background-position:center top;background-repeat:no-repeat;background-size:contain;transition:opacity .35s ease;pointer-events:none;filter:none}
#muscle{background-image:url("musculo.png");opacity:1}
#middle{background-image:url("inte.png");opacity:0;filter:contrast(1.08) brightness(.82)}
#bone{background-image:url("osso.png");opacity:0}
.hud{position:absolute;color:#aaa;font-size:11px;line-height:1.4;pointer-events:none;z-index:5}
.top-left{top:15px;left:15px}.top-right{top:15px;right:15px;text-align:right}.bottom-left{bottom:15px;left:15px}.bottom-right{bottom:15px;right:15px;text-align:right}
.depth-panel{position:absolute;right:25px;top:50%;transform:translateY(-50%);background:rgba(10,10,10,.8);border:1px solid #333;border-radius:8px;padding:15px;display:flex;flex-direction:column;align-items:center;gap:10px;z-index:6}
.depth-panel span{font-size:11px;color:#888}#depthSlider{width:6px;height:250px;cursor:ns-resize}.depth-labels{display:flex;flex-direction:column;gap:8px;font-size:10px;color:#666}
.sidebar{width:230px;background:#090909;border-left:1px solid #333;padding:15px;overflow-y:auto}.sidebar h2{color:#777;font-size:12px;margin-bottom:15px}
.thumb{height:120px;background:#111;border:2px solid transparent;border-radius:8px;margin-bottom:15px;overflow:hidden;position:relative;cursor:pointer;transition:.3s}.thumb:hover{transform:scale(1.03)}.thumb.active{border-color:#2563eb}
.thumb img{width:100%;height:100%;object-fit:contain;opacity:.55}.thumb-text{position:absolute;bottom:5px;left:5px;background:rgba(0,0,0,.7);font-size:11px;padding:4px}
#middle{background-image:url("inte.png");opacity:0;filter:contrast(1.08) brightness(.82)}
.inverted{filter:invert(1)}
#middle.inverted{filter:contrast(1.08) brightness(.82) invert(1)}
</style>
</head>
<body>
<header class="toolbar">
<button class="tool active" id="panTool" aria-label="Mover" title="Mover">✥</button>
<button class="tool" id="zoomTool" aria-label="Zoom" title="Zoom">⊕</button>
<button class="tool" id="invertTool" aria-label="Contraste" title="Contraste">◐</button>
<div class="info-top">DICOM AI Viewer | Arraste o controle de profundidade para explorar estruturas anatômicas</div>
</header>
<div class="main">
<section class="viewer" id="viewer">
<div class="viewport" id="viewport">
<div id="muscle" class="layer"></div>
<div id="middle" class="layer"></div>
<div id="bone" class="layer"></div>
</div>
<div class="hud top-left">Patient: João Silva<br>ID: 384920<br>Age: 45Y<br>Sex: M</div>
<div class="hud top-right">Hospital Base DF<br>Study: Full Body MRI<br>Date: 09/06/2026</div>
<div class="hud bottom-left" id="hudSlice">Slice: 142<br>Window: 400<br>Level: 40</div>
<div class="hud bottom-right" id="hudZoom">Zoom: 100%<br>Orientation: AXIAL<br>AI: Active</div>
<div class="depth-panel">
<span>Profundidade</span>
<input type="range" id="depthSlider" min="0" max="100" value="0" orient="vertical">
<div class="depth-labels"><span>Superficial</span><span>Intermediário</span><span>Profundo</span></div>
</div>
</section>
<section class="sidebar">
<h2>SERIES</h2>
<div class="thumb active" data-frame="superficial" data-depth="0"><img src="musculo.png" alt="Frame superficial"><div class="thumb-text">Superficial</div></div>
<div class="thumb" data-frame="intermediario" data-depth="50"><img src="inte.png" alt="Frame intermediário"><div class="thumb-text">Intermediário</div></div>
<div class="thumb" data-frame="profundo" data-depth="100"><img src="osso.png" alt="Frame profundo"><div class="thumb-text">Profundo</div></div>
</section>
</div>
<script>
const layers = {
  superficial: document.getElementById('muscle'),
  intermediario: document.getElementById('middle'),
  profundo: document.getElementById('bone')
};
const depthSlider = document.getElementById('depthSlider');
const viewer = document.getElementById('viewer');
const viewport = document.getElementById('viewport');
const depthPanel = document.querySelector('.depth-panel');
const hudZoom = document.getElementById('hudZoom');
const hudSlice = document.getElementById('hudSlice');
let currentTool = 'pan';
let isDragging = false;
let depthInteracting = false;
let startX = 0, startY = 0;
let panX = 0, panY = 0;
let scale = 1;
function getPanLimits(){
  const rect = viewer.getBoundingClientRect();
  const maxX = Math.max(0, (rect.width * scale - rect.width) / 2);
  const maxY = Math.max(0, (rect.height * scale - rect.height) / 2);
  return { maxX, maxY };
}
function clampPan(){
  const { maxX, maxY } = getPanLimits();
  panX = Math.min(maxX, Math.max(-maxX, panX));
  panY = Math.min(maxY, Math.max(-maxY, panY));
}
function updateViewport(){
  clampPan();
  viewport.style.transform = `translate(${panX}px, ${panY}px) scale(${scale})`;
  hudZoom.innerHTML = `Zoom: ${Math.round(scale * 100)}%<br>Orientation: AXIAL<br>AI: Active`;
}
function setDepth(depth){
  if (depth <= 40) layers.superficial.style.opacity = 1 - (depth / 40); else layers.superficial.style.opacity = 0;
  if (depth >= 25 && depth <= 75){
    layers.intermediario.style.opacity = depth <= 50 ? (depth - 25) / 25 : 1 - ((depth - 50) / 25);
  } else layers.intermediario.style.opacity = 0;
  if (depth >= 60) layers.profundo.style.opacity = (depth - 60) / 40; else layers.profundo.style.opacity = 0;
  hudSlice.innerHTML = `Frame: ${depth < 25 ? 'superficial' : depth < 75 ? 'intermediário' : 'profundo'}<br>Window: 400<br>Level: 40`;
  updateActiveThumb(depth);
}
depthSlider.addEventListener('input', e => setDepth(parseInt(e.target.value, 10)));
const depthStops = [0, 50, 100];
function snapDepthToNearest(){
  const current = Number(depthSlider.value);
  const nearest = depthStops.reduce((best, stop) => Math.abs(stop - current) < Math.abs(best - current) ? stop : best, depthStops[0]);
  depthSlider.value = nearest;
  setDepth(nearest);
}
depthSlider.addEventListener('change', snapDepthToNearest);
depthSlider.addEventListener('pointerup', snapDepthToNearest);
depthSlider.addEventListener('touchend', snapDepthToNearest);
depthSlider.addEventListener('pointerdown', (e) => {
  depthInteracting = true;
  isDragging = false;
  viewport.classList.remove('grabbing');
  e.stopPropagation();
});
depthSlider.addEventListener('pointerup', () => {
  depthInteracting = false;
});
depthSlider.addEventListener('pointercancel', () => {
  depthInteracting = false;
});
depthPanel.addEventListener('mousedown', (e) => e.stopPropagation());
window.addEventListener('mouseup', () => {
  depthInteracting = false;
});
const tools = { panTool:'pan', zoomTool:'zoom', invertTool:'invert' };
document.querySelectorAll('.tool').forEach(tool => {
  tool.addEventListener('click', () => {
    document.querySelectorAll('.tool').forEach(t => t.classList.remove('active'));
    tool.classList.add('active');
    currentTool = tools[tool.id];
    if (currentTool === 'invert') {
      Object.values(layers).forEach(layer => layer.classList.toggle('inverted'));
    }
  });
});
viewer.addEventListener('mousedown', (e) => {
  if (depthInteracting) return;
  if (currentTool !== 'pan' || scale <= 1) return;
  isDragging = true;
  startX = e.clientX - panX;
  startY = e.clientY - panY;
  viewport.classList.add('grabbing');
});
window.addEventListener('mousemove', (e) => {
  if (depthInteracting) return;
  if (!isDragging || currentTool !== 'pan' || scale <= 1) return;
  panX = e.clientX - startX;
  panY = e.clientY - startY;
  updateViewport();
});
window.addEventListener('mouseup', () => {
  isDragging = false;
  viewport.classList.remove('grabbing');
});
viewer.addEventListener('wheel', (e) => {
  const zoomShortcut = e.ctrlKey || currentTool === 'zoom';
  if (!zoomShortcut) return;
  e.preventDefault();
  const delta = e.deltaY > 0 ? -0.1 : 0.1;
  scale = Math.min(4, Math.max(1, +(scale + delta).toFixed(2)));
  if (scale <= 1) {
    panX = 0;
    panY = 0;
  }
  updateViewport();
}, { passive:false });
window.addEventListener('resize', updateViewport);
function updateActiveThumb(depth){
  const thumbs = [...document.querySelectorAll('.thumb')];
  let active = thumbs[0];
  let best = Infinity;
  thumbs.forEach(thumb => {
    const value = Math.abs(depth - Number(thumb.dataset.depth || 0));
    if (value < best) {
      best = value;
      active = thumb;
    }
  });
  thumbs.forEach(t => t.classList.remove('active'));
  active.classList.add('active');
}

document.querySelectorAll('.thumb').forEach(thumb => {
  thumb.addEventListener('click', () => {
    const depth = Number(thumb.dataset.depth || 0);
    depthSlider.value = depth;
    setDepth(depth);
    updateActiveThumb(depth);
    hudSlice.innerHTML = `Frame: ${thumb.dataset.frame}<br>Window: 400<br>Level: 40`;
  });
});
document.addEventListener('keydown', (e) => {
  if (e.key === '1') document.getElementById('panTool').click();
  if (e.key === '2') document.getElementById('zoomTool').click();
  if (e.key === '3') document.getElementById('invertTool').click();
});
setDepth(0);
updateViewport();
</script>
</body>
</html>