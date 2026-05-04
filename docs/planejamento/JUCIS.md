# PLANEJAMENTO DE UMA AVALIAÇÃO DE INTERAÇÃO HUMANO-COMPUTADOR

* **Site avaliado:** JUCIS DF — [jucis.df.gov.br](http://jucis.df.gov.br)
* **Método:** Avaliação heurística segundo as heurísticas de usabilidade de Nielsen.
* **Funcionalidades avaliadas:** 
  1. Navegação na Página Inicial
  2. Consulta de Viabilidade Regin
  3. Pesquisa de Nome Empresarial
  4. Autenticação de Documentos
  5. Consulta de Tabela de Preços
  6. Acesso aos Canais de Atendimento

---

## 1. OBJETIVOS
O objetivo desta avaliação de IHC é identificar problemas na interação e na interface com o usuário no portal da JUCIS-DF. A análise foca em como a arquitetura de informação e o design visual impactam a capacidade do empresário e do cidadão de realizar serviços autônomos, minimizando erros e confusão terminológica.

## 2. METODOLOGIA
O planejamento segue o framework **DECIDE**:
* **D** — Determinar os objetivos da avaliação
* **E** — Explorar perguntas a serem respondidas
* **C** — Escolher os métodos de avaliação
* **I** — Identificar e gerir as questões práticas
* **D** — Decidir como lidar com as questões éticas
* **E** — Avaliar, interpretar e apresentar os resultados

## 3. PERGUNTAS A SEREM RESPONDIDAS
* O usuário consegue ler as informações críticas sem esforço visual excessivo?
* O sistema fornece feedback visual adequado durante o carregamento de sistemas externos?
* A linguagem técnica jurídica é um impeditivo para a compreensão do cidadão leigo?
* A interface previne erros de preenchimento em campos críticos como chaves de segurança?

## 4. ESCALA DE SEVERIDADE (NIELSEN)

| Grau | Classificação | Descrição |
| :---: | :--- | :--- |
| **0** | Sem importância | Não é necessariamente um problema de usabilidade |
| **1** | Cosmético | Não precisa ser corrigido a menos que haja tempo |
| **2** | Simples | Baixa prioridade de correção |
| **3** | Grave | Alta prioridade; importante de ser corrigido |
| **4** | Catastrófico | Deve ser corrigido antes do lançamento |

## 5. DADOS COLETADOS (FIGURAS)
* **Figura 1:** Home apresentando baixo contraste entre fontes brancas e fundos claros nos banners.
* **Figura 2:** Sistema Regin abrindo em nova aba sem navegação de retorno.
* **Figura 3:** Formulário de pesquisa de nome com siglas (DREI, NIRE) sem explicação.
* **Figura 4:** Campo de autenticação de certidões sem máscara de entrada.
* **Figura 5:** Tabela de preços em formato de imagem estática.
* **Figura 6:** Página de suporte com links redundantes e circulares.

---

## 6. RESULTADOS DA AVALIAÇÃO (INSPEÇÃO)

### 6.1. Funcionalidade 1: Navegação na Página Inicial
* **Verificação:** As cores do texto e fundo possuem contraste suficiente para leitura? A interface atende a requisitos básicos de acessibilidade visual?
* **Grau de Severidade:** [3] Grave
* **Natureza do problema:** Obstáculo
* **Perspectiva do usuário:** Problema Geral
* **Perspectiva da tarefa:** Problema Principal
* **Descrição:** Os banners principais e alguns menus de rodapé utilizam fontes brancas sobre fundos coloridos claros ou fotos sem máscara de escurecimento. Isso dificulta a leitura para usuários com baixa visão ou em ambientes muito iluminados.
* **Correção:** Aplicar filtros de contraste nos fundos de imagem e garantir que o rácio de contraste entre texto e fundo siga as normas da WCAG (mínimo 4.5:1).

### 6.2. Funcionalidade 2: Consulta de Viabilidade (Regin)
* **Verificação:** O sistema oferece uma saída clara de janelas extras? O usuário consegue voltar para a home facilmente?
* **Grau de Severidade:** [3] Grave
* **Natureza do problema:** Barreira
* **Perspectiva do usuário:** Problema Geral
* **Perspectiva da tarefa:** Problema Principal
* **Descrição:** Ao clicar em viabilidade, o site abre um sistema externo numa nova janela. Não existe botão "Voltar ao Site da JUCIS", obrigando o usuário a fechar a aba.
* **Correção:** Integrar o sistema via iframe ou adicionar um botão de retorno proeminente.

### 6.3. Funcionalidade 3: Pesquisa de Nome Empresarial
* **Verificação:** A terminologia utilizada é simples e familiar? Siglas técnicas são explicadas na interface?
* **Grau de Severidade:** [2] Simples
* **Natureza do problema:** Obstáculo
* **Perspectiva do usuário:** Problema Geral
* **Perspectiva da tarefa:** Problema Secundário
* **Descrição:** O formulário exige que o usuário entenda termos como "Objeto Social" e "NIRE" sem oferecer balões de ajuda ou exemplos.
* **Correção:** Adicionar tooltips explicativos em cada campo técnico do formulário.

### 6.4. Funcionalidade 4: Autenticação de Documentos
* **Verificação:** O sistema utiliza máscaras para evitar erros de digitação? O feedback de erro é específico sobre o que foi errado?
* **Grau de Severidade:** [3] Grave
* **Natureza do problema:** Barreira
* **Perspectiva do usuário:** Problema Geral
* **Perspectiva da tarefa:** Problema Principal
* **Descrição:** O campo de "Chave de Segurança" aceita qualquer caractere. Se o usuário digitar um espaço acidental, o sistema dá erro de processamento sem instruir sobre o formato correto.
* **Correção:** Aplicar máscara de entrada e validação de campo antes do envio.

### 6.5. Funcionalidade 5: Consulta de Tabela de Preços
* **Verificação:** O sistema oferece atalhos ou busca para informações? A informação é apresentada de forma legível e buscável?
* **Grau de Severidade:** [2] Simples
* **Natureza do problema:** Obstáculo
* **Perspectiva do usuário:** Problema Geral
* **Perspectiva da tarefa:** Problema Secundário
* **Descrição:** A tabela de preços é uma imagem estática. Não é possível usar o "Ctrl+F" para localizar um valor; o usuário precisa fazer uma varredura visual em toda a lista.
* **Correção:** Transformar a tabela de preços em uma página HTML com filtro de busca por palavra-chave.

### 6.6. Funcionalidade 6: Canais de Atendimento
* **Verificação:** A ajuda é fácil de encontrar e integrada ao fluxo? Existe consistência entre os canais de suporte?
* **Grau de Severidade:** [2] Simples
* **Natureza do problema:** Ruído
* **Perspectiva do usuário:** Problema Geral
* **Perspectiva da tarefa:** Problema Secundário
* **Descrição:** Os links para "Fale Conosco" e "Ouvidoria" levam a páginas com layouts diferentes e informações desencontradas sobre horários.
* **Correção:** Criar uma Central de Atendimento Unificada com design consistente.

---

## 7. INTERPRETAÇÃO E CONCLUSÃO
O sistema da JUCIS-DF atende funcionalmente ao objetivo legal, mas apresenta falhas críticas de acessibilidade visual e de fluxo. A baixa legibilidade e a falta de unidade entre os módulos de serviço indicam uma ausência de Design Centrado no Usuário, priorizando a burocracia do processo em detrimento da facilidade de uso pelo cidadão.

## 8. QUESTÕES PRÁTICAS
* **Avaliadores:** 1 (Contexto acadêmico).
* **Cronograma:** 07/04/2026 (Avaliação Heurística); 23/04/2026 (Consolidação dos Dados).
* **Equipamentos:** Computador pessoal.
* **Local:** FCTE - UnB Campus Gama.

## 9. REFERÊNCIAS
* BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação Humano-Computador*. Rio de Janeiro: Elsevier, 2010.