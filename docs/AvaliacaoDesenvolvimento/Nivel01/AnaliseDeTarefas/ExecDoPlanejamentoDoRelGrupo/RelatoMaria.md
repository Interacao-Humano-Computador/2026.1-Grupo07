# Relato dos Resultados: Pré-agendamento de exames

## Tabela de contribuição
| Artefato(s) | Autor(es) |
| --- | --- |
| Relato dos Resultados: Pré-agendamento | Maria Laura Regis Cabral Dias |

---

## 1. Introdução e Escopo da Tarefa

Este documento apresenta os resultados da avaliação conceitual referente à tarefa de **Pré-agendamento de exames**. A validação foi conduzida pela aluna **Maria Laura Regis Cabral Dias** com o objetivo de verificar se os artefatos construídos (**Cenário, Storyboard, CTT e GOMS**) refletem adequadamente o modelo mental e o fluxo real executado pelos usuários, focando na usabilidade e na eficiência da migração do fluxo automatizado para o atendimento humano.

O cenário avaliado descreve a jornada de um usuário que tenta realizar o pré-agendamento de forma automatizada, enfrentando desafios na leitura das instruções de preparo, o que o leva a considerar o atendimento humano. Foram apresentados à entrevistada o Cenário narrativo, o Storyboard visual, o diagrama CTT e a análise quantitativa GOMS para avaliação qualitativa e lógica.

### 1.1 Entrevista
A seguir está a gravação da entrevista:
<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/CBj7lopsQX4" title="Gravação da Entrevista" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---

## 2. Tarefas Executadas e Sumário dos Dados

### 2.1. Tarefas Avaliadas
A **Tabela 1** detalha a decomposição do objetivo principal da avaliação em tarefas menores.

Tabela 1 - Decomposição do objetivo em tarefas

| ID | Tarefa Mapeada (Artefato) |
|----|---------|
| [T1] | Iniciar a funcionalidade de pré-agendamento |
| [T2] | Realizar o envio das fotos das guias médicas |
| [T3] | Analisar as instruções de preparo (jejum) e verificar dúvidas |
| [T4] | Migrar para o atendimento humano (WhatsApp) em caso de necessidade |

### 2.2. Sumário Quantitativo dos Dados
A **Tabela 2** apresenta o sumário quantitativo dos dados consolidados a partir da sessão de avaliação.

Tabela 2 - Sumário da Validação dos Artefatos

| Métrica | Resultado |
|----------|-----------|
| Número de participantes | 1 |
| Passos sugeridos pelos usuários não previstos no modelo | 1 |
| Tarefas mapeadas consideradas irreais/desnecessárias pelos usuários | 2 |
| Inconsistências apontadas no Storyboard/Cenário | 0 |
| Comentários relevantes registrados | 4 |

### 2.3. Divergências e Inconsistências Observadas
A **Tabela 3** detalha os pontos em que o fluxo desenhado divergiu da realidade da usuária.

Tabela 3 - Inconsistências encontradas por tarefa/momento

| Momento da Tarefa (ID) | Divergência Apontada pelo Usuário |
|------------------|-----------------------|
| [CTT] | Excessividade de passos sequenciais no fluxo, sugerindo simplificação. |
| [HTA/Fluxo Geral] | Ausência de suporte inicial para usuários com baixa adesão tecnológica (seniores). |

### 2.4. Comentários Relevantes dos Participantes
A **Tabela 4** reúne as citações diretas da entrevistada Alessandra Peloso.

Tabela 4 - Comentários dos entrevistados

| Participante | Comentário |
|-------------|------------|
| Alessandra Peloso | "Geralmente busco ajuda humana (WhatsApp) ao agendar exames, pois me sinto mais segura." |
| Alessandra Peloso | "Preocupa-me o público sênior; mesmo conseguindo tirar uma foto, o fluxo complexo pode impedi-los de concluir." |
| Alessandra Peloso | "Sugiro um questionário de triagem inicial para direcionar leigos ou oferecer instruções básicas." |

---

## 3. Relato da Interpretação e Análise dos Dados

### 3.1. Análise das Perguntas Exploratórias

| Pergunta Exploratória | Evidências Observadas na Entrevista | Conclusão |
|----------------------|----------------------|------------|
| O cenário e storyboard refletem a realidade? | Compreendidos e validados pela usuária. | Respondida |
| O fluxo CTT condiz com a prática do usuário? | Validado, com ressalva para simplificação. | Respondida |
| O tempo GOMS faz sentido na percepção da usuária? | Validado; a frustração com falhas foi confirmada. | Respondida |

### 3.2. Principais Achados

#### Aspectos Positivos (Validados)
* O Cenário e o Storyboard foram bem compreendidos e aceitos como representações fiéis da tentativa de uso.
* A análise GOMS refletiu a realidade de frustração enfrentada pelo usuário ao lidar com falhas do sistema.

#### Divergências Encontradas (Refutações)
* O diagrama CTT possui etapas que a usuária considerou burocráticas ou desnecessárias.

#### Novos Descobrimentos (Omissões)
* Necessidade crítica de um "questionário de triagem" para orientar usuários leigos ou seniores antes do fluxo principal.

### 3.3. Considerações Gerais
A avaliação validou a estrutura lógica dos artefatos. No entanto, o feedback trouxe um ponto crucial: a acessibilidade. Os artefatos devem ser mantidos, mas a inclusão da etapa de triagem é necessária para garantir a inclusão de usuários com menor afinidade tecnológica.

---

## 4. Lista de Problemas de Modelagem Encontrados

| ID | Descrição da Inconsistência | Artefato Afetado | Frequência | Severidade | Impacto na Modelagem | Possível Causa | Prioridade |
|----|----------------------|------------------------|------------|------------|----------------------------------|----------------|------------|
| [P01] | Complexidade para público sênior | Cenário/Fluxo | 1 | Alta | Fluxo restritivo | Foco em usuários nativos digitais | Alta |
| [P02] | Redundância de passos | CTT | 1 | Baixa | Burocracia no fluxo | Excesso de passos sequenciais | Média |

### 4.1. Critérios de Severidade
* **Cosmético:** ...
* **Pequeno:** ...
* **Grande:** Omissão de passo fundamental (Triagem).
* **Catastrófico:** ...

### 4.2. Priorização das Correções
1. Inclusão da triagem para acessibilidade (Problema P01).
2. Simplificação do fluxo no CTT (Problema P02).

---

## 5. Planejamento para o Refinamento dos Artefatos

### 5.1. Recomendações de Ajuste

| Inconsistência Relacionada | Refinamento Proposto | Justificativa |
|---------------------|---------------------|--------------|
| [P01] | Adicionar passo de "Triagem Inicial" | Permitir orientação antes do fluxo principal. |
| [P02] | Simplificar a árvore CTT | Remover passos desnecessários para agilizar a tarefa. |

### 5.2. Ajustes nos Modelos de Tarefas (CTT)
Reorganizar a hierarquia removendo passos redundantes conforme o feedback da participante.

### 5.3. Ajustes nos Cenários e Storyboards
Adicionar um quadro que exemplifique a opção de "Ajuda/Triagem", tornando o cenário mais inclusivo.

### 5.4. Priorização das Refatorações
| Prioridade | Artefato a ser Atualizado | Problema Relacionado |
|------------|-------------------|---------------------|
| Alta | Fluxo/HTA | [P01] - Inclusão da Triagem |
| Média | Diagrama CTT | [P02] - Redução de redundância |

---

## Referência Bibliográfica
> BARBOSA, S. D. J. et al. Interação Humano-Computador e Experiência do Usuário. 1. ed. Rio de Janeiro: Autopublicação, 2021.

---

## Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 31/05/2026 | Criação do relato sobre Pré-agendamento | Maria Laura Regis Cabral Dias | 31/05/2026 | Philipe Amâncio | - |
