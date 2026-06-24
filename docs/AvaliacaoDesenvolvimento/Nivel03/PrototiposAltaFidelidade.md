# Protótipo de Alta Fidelidade

## Tabela de Contribuição

| Artefato(s) | Autor(es) |
| --- | --- |
| Página de Protótipo de Alta Fidelidade | [Hugo Freitas Silva](https://github.com/HugoFreitass) |
| [Protótipo de Alta Fidelidade — Cadastro de Exame Laboratorial](#51-tarefa-1-cadastro-de-exame-laboratorial) | [Hugo Freitas Silva](https://github.com/HugoFreitass) |
| [Protótipo de Alta Fidelidade — Agendamento de Exames com Dúvidas Críticas de Preparo](#52-tarefa-2-pre-agendamento-de-exames-com-duvidas-criticas-de-preparo) | [Maria Laura Regis](https://github.com/Maria-Laura-Regis) |
| [Protótipo de Alta Fidelidade — Acesso ao Resultado de Imagem com Visualizador DICOM](#53-tarefa-3-acesso-ao-resultado-de-imagem-com-visualizador-dicom) | [Philipe Amancio](https://github.com/Phill-Chill) |
| [Protótipo de Alta Fidelidade — Acompanhamento de Resultados e Download de Laudos](#54-tarefa-4-acompanhamento-de-resultados-e-download-de-laudos) | [Ingrid Alves](https://github.com/alvesingrid) |

---

## 1. Introdução

O **Protótipo de Alta Fidelidade** representa uma etapa avançada do processo de design de interfaces, permitindo a simulação detalhada da aparência e do comportamento de um sistema antes de sua implementação. Diferentemente dos protótipos de baixa fidelidade, essa abordagem busca reproduzir com maior precisão elementos visuais, componentes interativos, fluxos de navegação e padrões de interação que estarão presentes no produto final.

Para o Portal Sabin, o protótipo de alta fidelidade foi desenvolvido com base nos resultados obtidos durante a avaliação do [protótipo de papel](../Nivel02/PrototipoDePapel/PrototipoDePapel.md), incorporando melhorias relacionadas à organização das informações, nomenclatura dos elementos e fluxo de agendamento de exames. Além disso, sua construção foi orientada pelas tarefas definidas na [Análise de Tarefas](../../../requisitos/analisedetarefa.md) e pelos cenários elaborados para as [Personas](../../../requisitos/persona.md) do projeto.

O objetivo deste protótipo é representar de forma mais realista a experiência do usuário, permitindo validar decisões de design, avaliar a usabilidade das interfaces e identificar oportunidades de melhoria antes da etapa de desenvolvimento do sistema.

### Posicionamento no Ciclo de Vida de Mayhew

No **Ciclo de Vida de Mayhew** <span class="hover-image">(BARBOSA; SILVA, 2021, p. 110)<sup class="Print">[PRINT]</sup></span>, o desenvolvimento de sistemas interativos é organizado em três grandes fases: **Análise de Requisitos**, **Design, Avaliação e Desenvolvimento**, e **Instalação**. O Protótipo de Alta Fidelidade integra o **Nível 3** — o estágio mais avançado — da fase de **Design, Avaliação e Desenvolvimento**, conforme apresentado abaixo. Para mais detalhes sobre como o grupo adotou esse ciclo de vida, consulte a [página de Processo de Design](../../../planejamento/processoDesign.md).

| Fase Mayhew | Nível | Artefato desta seção |
|------------|-------|----------------------|
| Design, Avaliação e Desenvolvimento | Nível 1 | Storyboards, Análise de Tarefas, Cenários |
| Design, Avaliação e Desenvolvimento | Nível 2 | Protótipo de Papel |
| Design, Avaliação e Desenvolvimento | **Nível 3** — Protótipo interativo e avaliação final antes do desenvolvimento | Protótipo de Alta Fidelidade |


Neste nível, o protótipo de alta fidelidade acumula todas as correções derivadas das etapas anteriores e permite uma avaliação de usabilidade mais próxima da experiência real do produto final. Os resultados desta etapa subsidiam o **reprojeto final** antes do desenvolvimento do sistema, fechando o ciclo iterativo de design proposto por Mayhew.



## 2. Por que usar o Protótipo de Alta Fidelidade?

O protótipo de alta fidelidade foi adotado nesta etapa do projeto porque:

- **Maior realismo:** reproduz com fidelidade a aparência visual e os fluxos de interação esperados para o sistema final;
- **Validação da experiência do usuário:** permite avaliar aspectos de usabilidade, navegação e compreensão da interface em um contexto mais próximo da utilização real;
- **Avaliação de decisões de design:** possibilita verificar se as melhorias propostas após a avaliação do protótipo de papel solucionam os problemas identificados;
- **Comunicação entre stakeholders:** facilita o alinhamento entre equipe de desenvolvimento, avaliadores e demais interessados no projeto;
- **Redução de riscos:** permite identificar falhas de interação e requisitos de interface antes do início da implementação, reduzindo retrabalho e custos de desenvolvimento.

---

## 3. Tarefas Representadas

Os protótipos de alta fidelidade desenvolvidos pela equipe representam os seguintes fluxos de tarefas:

| ID | Tarefa | Responsável |
|----|--------|-------------|
| T1 | Cadastro de exame laboratorial com informação incompleta no sistema | [Hugo Freitas Silva](https://github.com/HugoFreitass) |
| T2 | Agendamento de exames com dúvidas críticas de preparo | [Maria Laura Regis](https://github.com/Maria-Laura-Regis) |
| T3 | Acesso ao resultado de imagem com visualizador DICOM | [Philipe Amancio](https://github.com/Phill-Chill) |
| T4 | Acompanhamento de resultados e download de laudos | [Ingrid Alves](https://github.com/alvesingrid) |

---

## 4. Correções Implementadas com Base na Avaliação do Protótipo de Papel

Os protótipos de alta fidelidade desta etapa não foram construídos do zero: eles são **evoluções diretas** dos fluxos avaliados durante a fase de [Protótipo de Papel](../Nivel02/PrototipoDePapel/PrototipoDePapel.md). Cada problema de usabilidade identificado nos [Relatos dos Resultados do Protótipo de Papel](../Nivel02/PrototipoDePapel/RelatosDosResultados/index.md) foi analisado e transformado em uma melhoria concreta de design na versão de alta fidelidade.

A tabela a seguir sintetiza as principais correções implementadas por tarefa:

| Tarefa | Problema identificado no Protótipo de Papel | Correção implementada no Protótipo de Alta Fidelidade |
|--------|---------------------------------------------|-------------------------------------------------------|
| T1 — Cadastro de Exame Laboratorial | Nomenclaturas técnicas dificultavam a identificação do exame correto; falta de clareza nas instruções de preparo durante o fluxo | Busca com sugestões e descrições simplificadas dos exames; exibição das instruções de preparo de forma proeminente e contextualizada ao longo do fluxo |
| T2 — Agendamento de Exames | Redirecionamento para PDF genérico ao buscar orientações sobre dúvidas de preparo; fluxo abandonado por insegurança | Integração de FAQ contextual e específico por exame diretamente na tela de preparo; botão de atendimento humano via WhatsApp como alternativa acessível |
| T3 — Acesso ao Visualizador DICOM | Dificuldade na transição entre o laudo em texto e as imagens médicas; ferramentas de visualização pouco intuitivas | Interface do visualizador DICOM com apoio de IA educacional para orientar a leitura da imagem de forma didática; ferramentas de zoom e contraste com acionamento mais claro |
| T4 — Download de Laudos | Necessidade de baixar múltiplos PDFs separados para exames seriados (Curva Glicêmica), gerando atrito e carga cognitiva desnecessária; ausência de visibilidade do status do exame na tela inicial | Geração de **PDF consolidado** com todas as coletas em um único arquivo; **notificação proativa** de exame liberado na tela inicial; rastreador visual de status (Coletado → Em análise → Liberado); compartilhamento direto por WhatsApp e e-mail integrado ao portal |

> Cada protótipo individual documenta de forma detalhada as correções aplicadas e a rastreabilidade com os problemas identificados na fase anterior. Consulte os relatos individuais na seção **Relatos dos Resultados** para mais informações.



## 5. Protótipos de Alta Fidelidade da Equipe

### 5.1. Tarefa 1 — Cadastro de Exame Laboratorial

> Elaborado por: [Hugo Freitas Silva](https://github.com/HugoFreitass)

Este protótipo representa o fluxo de agendamento de um exame laboratorial no sistema do Portal Sabin, avaliando qual o fluxo do usuário durante a execução desta atividade.

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/GpeJOPjNGV6x0R6Wg51aQM/Prot%C3%B3tipo-de-Alta-fiddelidade?node-id=0-1&embed-host=share" allowfullscreen></iframe>


---

### 5.2. Tarefa 2 — Pré-Agendamento de Exames com Dúvidas Críticas de Preparo

> Elaborado por: [Maria Laura Regis](https://github.com/Maria-Laura-Regis)

Este protótipo representa o fluxo de agendamento de exames de sangue pelo Portal Sabin.

<iframe src="https://interacao-humano-computador.github.io/2026.1-Grupo07/assets/sabin-pre-cadastro.html" width="100%" height="800px" style="border:1px solid #ccc; border-radius:8px;"></iframe>

> Fonte: Autoria própria.

---

### 5.3. Tarefa 3 — Acesso ao Resultado de Imagem com Visualizador DICOM


> Elaborado por: [Philipe Amancio](https://github.com/Phill-Chill)

Este protótipo foca na experiência direta dentro do visualizador de imagens DICOM do Portal Sabin. O fluxo tem início já na interface de visualização, mapeando a utilização manual das ferramentas de zoom e ajuste de profundidade. O diferencial é o apoio de um modelo de Inteligência Artificial educacional integrado, que orienta o paciente no entendimento anatômico da imagem de forma visual, didática e segura, sem emitir diagnósticos clínicos.

<iframe src="https://interacao-humano-computador.github.io/2026.1-Grupo07/assets/visualizador-dicom.html" width="100%" height="800px" style="border:1px solid #ccc; border-radius:8px;"></iframe>


> Fonte: Autoria própria.

---

### 5.4. Tarefa 4 — Acompanhamento de Resultados e Download de Laudos

> Elaborado por: [Ingrid Alves](https://github.com/alvesingrid)

Este protótipo representa o fluxo completo de acompanhamento e download de laudos no Portal Sabin, contemplando as telas de login com token SMS, página inicial com notificação de exame liberado, listagem de resultados com filtros, visualização detalhada do laudo da Curva Glicêmica e download em PDF consolidado. O protótipo incorpora a melhoria central identificada na avaliação do protótipo de papel: a geração de um **PDF unificado** com todas as coletas da Curva Glicêmica, eliminando a necessidade de baixar arquivos separados.

<iframe src="../../../assets/prototipo-ingrid/index.html" width="100%" height="800px" style="border:1px solid #ccc; border-radius:8px;"></iframe>

> Fonte: Autoria própria.

---



## Agradecimentos à IA

Gostaríamos de registrar nossos agradecimentos ao modelo de Inteligência Artificial Generativa Gemini, desenvolvido pelo Google, pelo auxílio na estruturação, revisão gramatical e padronização da formatação em Markdown dos artefatos deste projeto. A ferramenta foi utilizada estritamente como suporte técnico e operacional para refinar a apresentação da documentação. Ressaltamos que todo o planejamento, execução das metodologias, análise crítica de dados e tomadas de decisão descritas neste documento são de autoria e responsabilidade exclusiva dos membros da equipe.

---

## Referências Bibliográficas

> BARBOSA, S. D. J. et al. **Interação Humano-Computador e Experiência do Usuário.** 1. ed. Rio de Janeiro: Autopublicação, 2021.

---

## Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 16/06/2026 | Criação do documento e adição do protótipo da tarefa de agendamento de exame | [Hugo Freitas Silva](https://github.com/HugoFreitass) | 16/06/2026 | Revisão da estrutura | [Philipe Amancio](https://github.com/Phill-Chill) |
| 1.1 | 22/06/2026 | Adição do protótipo de alta fidelidade da tarefa de Acompanhamento de Resultados e Download de Laudos | [Ingrid Alves](https://github.com/alvesingrid) | - | - | - |
| 1.2 | 23/06/2026 | Descrevendo as correções implementadas com base na avaliação do protótipo de papel | [Ingrid Alves](https://github.com/alvesingrid) | - | - | - |
| 1.3 | 23/06/2026 | Adição de link para a página de Processo de Design na seção de posicionamento no Ciclo de Vida de Mayhew | [Ingrid Alves](https://github.com/alvesingrid) | - | - | - |

