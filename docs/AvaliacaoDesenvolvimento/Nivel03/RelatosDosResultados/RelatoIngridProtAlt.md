# Relato dos Resultados — Protótipo de Alta Fidelidade: Acompanhamento de Resultados e Download de Laudos

## Tabela de Contribuição

| Artefato(s) | Autor(es) |
| --- | --- |
| Relato dos resultados da avaliação do protótipo de alta fidelidade — Acompanhamento de Resultados e Download de Laudos | [Ingrid Alves](https://github.com/alvesingrid) |

---

## 1. Objetivos e Escopo da Avaliação

Este documento apresenta os resultados da avaliação do **Protótipo de Alta Fidelidade** referente à tarefa de **Acompanhamento de Resultados e Download de Laudos** no Portal Sabin. A avaliação foi conduzida pela avaliadora **Ingrid Alves** com o objetivo de validar as melhorias de design propostas a partir da avaliação do [Protótipo de Papel](../../Nivel02/PrototipoDePapel/RelatosDosResultados/RelatoIngrid.md) e identificar novos problemas de usabilidade na versão interativa da interface.

**Tarefas avaliadas e telas do protótipo utilizadas:**

- Login com token SMS;
- Visualização da notificação de exame liberado na página inicial;
- Navegação até a seção "Meus Resultados";
- Localização e filtragem de exames na listagem;
- Visualização detalhada do laudo da Curva Glicêmica com o rastreador de status;
- Download em PDF consolidado (melhoria central do redesign).

**Fluxos de navegação analisados:** Login → Home (notificação) → Meus Resultados → Detalhe do Exame → Download PDF Consolidado → Confirmação.

**Melhorias incorporadas a partir do Protótipo de Papel:**

- Adição de **notificação proativa** de exame liberado na tela inicial, eliminando a necessidade de rolagem para encontrar o resultado;
- Substituição dos múltiplos PDFs individuais por um único **PDF consolidado** com todas as coletas da Curva Glicêmica;
- Adição de opção de **compartilhamento direto** por WhatsApp e e-mail sem dependência do sistema operacional;
- Implementação de **rastreador visual de status** (Coletado → Em análise → Liberado).

---

## 2. Método de Avaliação Empregado

A avaliação foi conduzida por meio de **Teste de Usabilidade com Protótipo de Alta Fidelidade**, seguindo o método definido no [Planejamento da Avaliação](../PlanejamentoAvaliacao.md). Durante a sessão:

- O participante interagiu diretamente com o protótipo HTML interativo hospedado no portal da disciplina;
- O teste foi conduzido com o protocolo *Think Aloud* (verbalização dos pensamentos);
- **Estratégias de coleta de dados:**
  - Observação direta das ações e interações do participante com a interface;
  - Gravação audiovisual da sessão (mediante consentimento);
  - Anotações da avaliadora sobre cliques, hesitações e comentários espontâneos.

### Protótipo Avaliado

<iframe src="../../../assets/prototipo-ingrid/index.html" width="100%" height="700px" style="border:1px solid #ccc; border-radius:8px;"></iframe>

> Fonte: Autoria própria. Acesse também: [Protótipo de Alta Fidelidade — Nível 3](../PrototiposAltaFidelidade.md#44-tarefa-4-acompanhamento-de-resultados-e-download-de-laudos)

### Gravações das Sessões de Avaliação

As gravações foram realizadas com o consentimento dos participantes, cujos nomes foram substituídos por nomes fictícios para preservar o anonimato.

#### Participante 1 — Ana Ferreira

**Entrevista completa:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/fSXe2i6dF3c" title="Entrevista — Participante 1 (Ana Ferreira)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Termo de consentimento (gravação curta):**

<iframe width="315" height="560" src="https://www.youtube.com/embed/nJevB4riO54" title="Termo de consentimento — Participante 1 (Ana Ferreira)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

#### Participante 2 — Bruno Costa

**Entrevista completa:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/bXUzj1126MY" title="Entrevista — Participante 2 (Bruno Costa)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Termo de consentimento (gravação curta):**

<iframe width="315" height="560" src="https://www.youtube.com/embed/bLLKNCr1Lg0" title="Termo de consentimento — Participante 2 (Bruno Costa)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

#### Participante 3 — Carla Rodrigues

**Entrevista completa:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/KTMVGLg1YLE" title="Entrevista — Participante 3 (Carla Rodrigues)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Termo de consentimento (gravação curta):**

<iframe width="315" height="560" src="https://www.youtube.com/embed/QHGG2_vpg-E" title="Termo de consentimento — Participante 3 (Carla Rodrigues)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## 3. Perfil de Usuários e Avaliadores

### Participantes

Os nomes abaixo são fictícios para preservar o anonimato dos participantes, conforme o Termo de Consentimento Livre e Esclarecido assinado por cada um.

| Participante (nome fictício) | Perfil |
|------------------------------|--------|
| Ana Ferreira | [Perfil de usuário correspondente](../../../requisitos/perfilDeUsuario.md) |
| Bruno Costa | [Perfil de usuário correspondente](../../../requisitos/perfilDeUsuario.md) |
| Carla Rodrigues | [Perfil de usuário correspondente](../../../requisitos/perfilDeUsuario.md) |

### Avaliadores

| Avaliador | Papel |
|------------|---------|
| [Ingrid Alves](https://github.com/alvesingrid) | Facilitador |
| A definir | Anotador / Observador |
| A definir | Cinegrafista / Gestor de Gravação |

### Relação com o Perfil de Usuário

O participante selecionado apresenta características compatíveis com o [perfil de usuário](../../../requisitos/perfilDeUsuario.md) do Portal Sabin, garantindo a validade externa dos resultados obtidos.

---

## 4. Tarefas Executadas e Sumário dos Dados

### 4.1. Tarefas Avaliadas

Tabela 1 — Decomposição das tarefas avaliadas no protótipo

| ID | Tarefa Mapeada |
|----|--------|
| T1 | Autenticação via token SMS |
| T2 | Localização da notificação de exame liberado na Home |
| T3 | Navegação e filtragem na lista de resultados |
| T4 | Visualização dos detalhes do laudo (rastreador de status + tabela de resultados) |
| T5 | Seleção do PDF consolidado e download |

### 4.2. Sumário Quantitativo dos Dados

Tabela 2 — Sumário quantitativo da avaliação

| Métrica | Resultado |
|----------|-----------|
| Número de participantes | 3 |
| Tarefas concluídas sem auxílio | A preencher |
| Tarefas concluídas com auxílio | A preencher |
| Tarefas não concluídas | A preencher |
| Total de erros (cliques falhos/caminhos errados) | A preencher |
| Pontos de hesitação identificados | A preencher |
| Comentários relevantes registrados | A preencher |

### 4.3. Dificuldades Observadas por Tarefa

Tabela 3 — Dificuldades por tarefa

| Tarefa | Dificuldade Observada |
|--------|-----------------------|
| T1 | A preencher |
| T2 | A preencher |
| T3 | A preencher |
| T4 | A preencher |
| T5 | A preencher |

### 4.4. Comentários Relevantes dos Participantes

Tabela 4 — Comentários do entrevistado

| Participante | Comentário |
|-------------|------------|
| A preencher | "..." |

---

## 5. Relato da Interpretação e Análise dos Dados

### 5.1. Análise das Perguntas Exploratórias

| Pergunta Exploratória | Evidências Observadas | Conclusão |
|----------------------|----------------------|------------|
| O usuário concluiu a tarefa sem auxílio? | A preencher | A preencher |
| A notificação de exame liberado foi percebida na Home? | A preencher | A preencher |
| A opção de PDF consolidado foi compreendida e preferida? | A preencher | A preencher |
| O rastreador de status foi útil para orientação do usuário? | A preencher | A preencher |
| O compartilhamento integrado por WhatsApp atendeu a expectativa? | A preencher | A preencher |

### 5.2. Principais Achados

**Aspectos Positivos:**

- A preencher

**Dificuldades Encontradas:**

- A preencher

**Quebras de Expectativa:**

- A preencher

---

## 6. Lista dos Problemas Encontrados

Tabela 5 — Problemas de usabilidade identificados

| ID | Descrição do Problema | Tarefa | Frequência | Severidade | Impacto | Possível Causa | Prioridade |
|----|----------------------|--------|------------|------------|---------|----------------|------------|
| P01 | A preencher | A preencher | A preencher | A preencher | A preencher | A preencher | A preencher |

### 6.1. Critérios de Severidade

Os problemas foram classificados de acordo com a escala de severidade <span class="hover-image">(BARBOSA; SILVA, 2021, p. 284).<sup class="Print">[PRINT]</sup><img class= "img" src="../../../assets/escala-severidade.png"> </span>:

| Nível | Descrição |
|---------|------------|
| Cosmético | Pequeno desconforto sem impedir a realização da tarefa |
| Pequeno | Dificulta significativamente a execução da tarefa |
| Grande | Impede ou compromete fortemente a realização da tarefa |
| Catastrófico | Impede completamente a conclusão da atividade |

---

## 7. Planejamento para o Reprojeto Final

Com base nos problemas identificados, as seguintes melhorias são recomendadas para o refinamento final do protótipo <span class="hover-image">(BARBOSA; SILVA, 2021, p. 279).<sup class="Print">[PRINT]</sup><img class= "img" src="../../../assets/reprojeto-p279.png"> </span>:

### 7.1. Recomendações de Melhoria

| Problema Relacionado | Proposta de Melhoria | Justificativa |
|---------------------|---------------------|--------------|
| A preencher | A preencher | A preencher |

### 7.2. Priorização das Alterações

| Prioridade | Alteração Proposta | Problema Relacionado |
|------------|-------------------|---------------------|
| A preencher | A preencher | A preencher |

---

## Agradecimentos à IA

Gostaríamos de registrar nossos agradecimentos ao modelo de Inteligência Artificial Generativa Gemini, desenvolvido pelo Google, pelo auxílio na estruturação, revisão gramatical e padronização da formatação em Markdown dos artefatos deste projeto. A ferramenta foi utilizada estritamente como suporte técnico e operacional para refinar a apresentação da documentação. Ressaltamos que todo o planejamento, execução das metodologias, análise crítica de dados e tomadas de decisão descritas neste documento são de autoria e responsabilidade exclusiva dos membros da equipe.

---

## Referência Bibliográfica

> BARBOSA, S. D. J. et al. Interação Humano-Computador e Experiência do Usuário. 1. ed. Rio de Janeiro: Autopublicação, 2021.

---

## Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 22/06/2026 | Criação e estruturação do documento com dados da tarefa de Download de Laudos | [Ingrid Alves](https://github.com/alvesingrid) | - | - | - |
| 1.1 | 30/06/2026 | Adição das gravações das sessões de avaliação (3 participantes com nomes fictícios) | [Ingrid Alves](https://github.com/alvesingrid) | - | - | - |