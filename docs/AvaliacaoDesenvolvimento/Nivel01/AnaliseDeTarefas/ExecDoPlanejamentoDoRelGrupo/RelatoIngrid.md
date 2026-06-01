# Relato dos Resultados: Obter laudo de exame online

## Tabela de contribuição

| Artefato(s) | Autor(es) |
| --- | --- |
| Relato dos Resultados: Obter laudo de exame online | [Ingrid Alves Rocha](https://github.com/indalvess) |

---

## 1. Introdução

Este documento apresenta os resultados da avaliação conceitual referente à tarefa de **Obter laudo de exame online**. A validação foi conduzida pela avaliadora **Ingrid Alves** com o objetivo de verificar se os artefatos construídos (Análise de Tarefas HTA, Cenários e modelos GOMS/KLM) refletem adequadamente o modelo mental e o fluxo real executado pelos usuários.

O escopo desta avaliação focou no cenário em que o usuário acessa o portal aguardando um resultado importante. A avaliação foi realizada com três participantes, todos estudantes de Engenharia de Software: Yara Xavier de Sousa (22 anos), William Bernardo da Silva (23 anos) e Leonardo Gonçalves Machado (23 anos). É importante registrar que a equipe possui a gravação em vídeo apenas da entrevista realizada com a participante Yara. O foco destas entrevistas foi validar o cenário de uma paciente que acessa o portal aguardando um resultado importante, bem como a eficiência do fluxo mapeado.

### 1.1 Entrevista
A seguir está a gravação da entrevista realizada com a participante Yara Xavier de Sousa:
<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/" title="Gravação da Entrevista" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---

## 2. Tarefas Executadas e Sumário dos Dados

### 2.1. Tarefas Avaliadas
A **Tabela 1** detalha a decomposição do objetivo principal da avaliação em tarefas menores, validadas a partir do diagrama HTA.

Tabela 1 - Decomposição do objetivo em tarefas

| ID | Tarefa Mapeada (Artefato) |
| --- | --- |
| T1 | Autenticação no portal de resultados |
| T2 | Localizar exame desejado |
| T3 | Baixar arquivo PDF do laudo |
| T4 | Compartilhar o documento |

### 2.2. Sumário Quantitativo dos Dados
A **Tabela 2** apresenta o sumário quantitativo dos dados consolidados a partir das sessões de avaliação. Essas métricas fornecem uma visão objetiva sobre a precisão dos modelos construídos, quantificando divergências, sugestões de adição e níveis de concordância:

Tabela 2 - Sumário da Validação dos Artefatos

| Métrica | Resultado |
| --- | --- |
| Número de participantes | 3 |
| Passos sugeridos pelos usuários não previstos no modelo | 2 (Compartilhamento nativo e notificação na interface) |
| Tarefas mapeadas consideradas irreais/desnecessárias pelos usuários | 0 |
| Inconsistências apontadas no Storyboard/Cenário/Eficiência | 2 (Ansiedade divergente no cenário e estimativa GOMS) |
| Comentários relevantes registrados | 6 |

### 2.3. Divergências e Inconsistências Observadas
A **Tabela 3** detalha os pontos em que o fluxo desenhado divergiu da realidade de uso observada, revelando contrastes entre os perfis entrevistados:

Tabela 3 - Inconsistências encontradas por tarefa/momento

| Momento da Tarefa (ID) | Divergência Apontada pelo Usuário |
| --- | --- |
| Fase B (Cenário - Emoções) | A motivação de ansiedade extrema da personagem Camila condiz com as vivências da Yara, mas não retrata os sentimentos habituais do William e do Leonardo ao aguardarem laudos. |
| Fase D (GOMS/KLM - Eficiência) | A estimativa de tempo de 8,5 segundos para localizar e baixar o exame foi considerada irreal pela Yara, enquanto William e Leonardo a consideraram condizente e válida. |
| Fase C (T4 - Compartilhamento) | O fluxo atual depende do sistema nativo do celular para envio via WhatsApp. William acha essa dependência nativa satisfatória, mas Yara e Leonardo preferem que a funcionalidade seja integrada ao portal. |
| Fase D (Visibilidade da Interface) | Yara e Leonardo exigem a seção "Últimos Resultados" imediatamente na primeira tela sem rolagem, ou acompanhada de notificações. William considera que a necessidade de estar logo na primeira tela depende da situação. |

### 2.4. Comentários Relevantes dos Participantes
A **Tabela 4** reúne citações diretas expressivas feitas pelos participantes durante as validações:

Tabela 4 - Comentários dos entrevistados

| Participante | Comentário |
| --- | --- |
| Yara Xavier de Sousa | "Com certeza, sempre" (sobre a fidelidade do cenário de ansiedade por um laudo) |
| Yara Xavier de Sousa | "Não tem que ser o mais simples possível" (sobre a não inclusão de novos passos no fluxo) |
| William Bernardo | "É satisfatório o sistema nativo do celular" (sobre a etapa de compartilhamento) |
| William Bernardo | "No carregamento de páginas e geração do PDF" (sobre o gargalo de tempo do sistema) |
| Leonardo Gonçalves | "Baixar o PDF passa mais tempo procurando — está errado" (sobre gargalos na eficiência) |
| Leonardo Gonçalves | "Sim, ou uma notificação sobre ter os resultados." (sobre os últimos resultados na home) |

---

## 3. Relato da Interpretação e Análise dos Dados

Nesta seção são apresentados os resultados obtidos durante a avaliação conceitual e sua relação com os objetivos definidos no planejamento.

### 3.1. Análise das Perguntas Exploratórias

| Pergunta Exploratória | Evidências Observadas na Entrevista | Conclusão |
| --- | --- | --- |
| **Fase A: Perfil e Aquecimento** | | |
| Qual é o seu nome, idade e profissão? | Yara Xavier (22 anos), William Bernardo (23 anos) e Leonardo Gonçalves (23 anos), todos estudantes de Engenharia de Software. | Respondida |
| **Fase B: Validação do Cenário** | | |
| O cenário reflete com fidelidade as motivações e sentimentos do usuário? | Todos consideraram a situação realista. Contudo, a motivação emocional de ansiedade não é um consenso, sendo validada por apenas um perfil. | Respondida parcialmente |
| **Fase C: Validação do Storyboard/Compartilhamento** | | |
| O fluxo de compartilhamento do documento condiz com a realidade? | William acha o sistema nativo satisfatório; Yara e Leonardo preferem integração nativa ao portal. | Respondida parcialmente |
| **Fase D: Validação de HTA e GOMS/KLM** | | |
| A decomposição do fluxo no HTA está coerente com a prática? | O raciocínio em sequência (autenticação → localizar → baixar → compartilhar) reflete perfeitamente as ações dos três participantes, sem etapas redundantes. | Respondida |
| O tempo de execução do modelo GOMS é realista? | A métrica gerou opiniões divididas. É realista para 2 usuários, mas subestimada para 1 usuária que aponta lentidão sistêmica. | Respondida parcialmente |
| A seção "Últimos Resultados" deve estar visível sem rolagem na tela inicial? | Yara e Leonardo exigem a seção imediatamente sem rolagem ou com notificações. William considera que depende da situação. | Respondida parcialmente |

### 3.2. Principais Achados

#### Aspectos Positivos (Validados)

* A frustração de precisar baixar múltiplos PDFs separados em vez de um arquivo consolidado é um problema real enfrentado por todos os usuários.
* A estrutura da Árvore de Tarefas (HTA) não possui redundâncias e cobre o fluxo fundamental da atividade corretamente.

#### Divergências Encontradas (Refutações)

* A ansiedade não é uma regra geral. O modelo mental varia de usuários que ficam muito ansiosos por resultados a usuários extremamente casuais e tranquilos.
* Há divergência na percepção de gargalos: para alguns, o problema é a geração do PDF e carregamento (sistema); para outros, o obstáculo é procurar a informação (interface).

#### Novos Descobrimentos (Omissões)

* Além de ter os "Últimos Resultados" na primeira tela, a interface poderia implementar um sistema de notificação para agilizar a localização.
* Uma opção de compartilhamento integrada no portal beneficiaria a maioria dos perfis entrevistados.

### 3.3. Considerações Gerais
Os resultados corroboram a estabilidade do fluxo de tarefas (HTA). As divergências focam na eficiência (GOMS/KLM) e no design da interface. A prototipação deve absorver as sugestões de otimizar o tempo de busca visual, seja movendo os resultados recentes para o topo (above the fold) ou inserindo notificações, e deve prever a integração de funções de compartilhamento sem retirar a simplicidade da tarefa.

---

## 4. Lista de Problemas de Modelagem Encontrados

| ID | Descrição da Inconsistência | Artefato Afetado | Frequência | Severidade | Impacto na Modelagem | Possível Causa | Prioridade |
| --- | --- | --- | --- | --- | --- | --- | --- |
| P01 | Modelo de eficiência GOMS/KLM subestima gargalos reais (carregamento/busca) | GOMS / KLM | 1 participante | Grande | Modelo de tempo preditivo falho em cenários adversos | Omissão de operadores de tempo de resposta adequados (R) | Alta |
| P02 | Ausência de prioridade visual para resultados ou notificações de novos laudos | Cenário / Interface | 2 participantes | Pequeno | Maior esforço cognitivo e rolagem desnecessária | Falha de hierarquia visual | Alta |
| P03 | Cenário não abrange a variedade emocional dos usuários (focado apenas em ansiedade) | Cenário de Uso | 2 participantes | Pequeno | Limita a empatia do desenvolvedor para perfis casuais | Foco excessivo em apenas um perfil (Persona primária) | Média |
| P04 | Omissão de ferramenta de compartilhamento nativa no escopo | HTA | 2 participantes | Pequeno | Dependência do SO e aumento de passos fora do portal | Escopo contido | Média |

### 4.1. Critérios de Severidade (Adaptados para Validação de Artefatos)
Os problemas encontrados nos modelos foram classificados adaptando a escala de severidade para o contexto de validação conceitual <span class="hover-image">(BARBOSA; SILVA, 2021, p. 284).<sup class="Print">[PRINT]</sup><img class= "img" src="../../../../assets/escala-severidade.png"> </span>

* **Cosmético:** Erro de digitação, falha visual no storyboard ou nomenclatura estranha que não invalida o fluxo.
* **Pequeno:** Omissão de um detalhe menor ou passo opcional na árvore de tarefas.
* **Grande:** Omissão de um passo fundamental, ordem incorreta de execução, ou cenário que reflete mal o contexto de uso real.
* **Catastrófico:** O diagrama ou narrativa não representa em absolutamente nada a forma como o usuário realiza a tarefa na vida real. Artefato inválido.

### 4.2. Priorização das Correções
Com base na severidade e no impacto na modelagem, as ações de correção foram priorizadas da seguinte forma:

1. **Prioridade Alta (P01):** Recalcular o modelo GOMS/KLM com variações de tempo de R (Response). Essa correção é urgente, pois o gargalo de carregamento afeta diretamente o tempo final da tarefa.
2. **Prioridade Alta (P02):** Especificar nos requisitos que a área "Últimos Resultados" deve ser acompanhada de uma notificação na tela principal. Essa lacuna afeta o esforço cognitivo do usuário.
3. **Prioridade Média (P03):** Expandir o Cenário para incluir uma narrativa secundária contemplando perfis casuais.
4. **Prioridade Média (P04):** Adicionar subpasso opcional no HTA para compartilhamento via link nativo do portal.

---

## 5. Planejamento para o Refinamento dos Artefatos

Nesta seção são apresentadas as propostas de correção e atualização dos documentos conceituais (Análise de Tarefas, Cenários e Storyboards) com base nas validações feitas pelos usuários <span class="hover-image">(BARBOSA; SILVA, 2021, p. 279).<sup class="Print">[PRINT]</sup><img class= "img" src="../../../../assets/reprojeto-p279.png"> </span>

### 5.1. Recomendações de Ajuste

| Inconsistência Relacionada | Refinamento Proposto | Justificativa |
| --- | --- | --- |
| P01 | Recalcular o modelo GOMS/KLM. Adicionar variações com diferentes tempos de R (Response) para simular carregamento pesado. | Avaliações mistas indicam que o gargalo de carregamento afeta fortemente o tempo final da tarefa. |
| P02 | Especificar nos requisitos que a área "Últimos Resultados" deve ser acompanhada de uma notificação na tela principal (home). | Otimiza o tempo de busca visual, atendendo à demanda dos participantes por não precisar procurar o exame. |
| P03 | Expandir o documento de Cenários para incluir uma narrativa secundária ou ajustar a narrativa atual. | O contexto atual não abrange pacientes esporádicos e casuais, identificados nas entrevistas. |
| P04 | Adicionar subpasso opcional no HTA: "Compartilhar através de ferramenta interna". | A maioria apontou a funcionalidade como um diferencial para melhorar a integração. |

### 5.2. Ajustes nos Modelos de Tarefas (HTA/CTT)

* Inserir um plano condicional/opcional no nível T4 do HTA, derivando para dois caminhos: a) Compartilhar via sistema operacional (existente); b) Compartilhar via link nativo do portal (novo).
* A base central do HTA permanece rigorosamente inalterada.

### 5.3. Ajustes nos Cenários e Storyboards
Descrever melhorias para tornar as narrativas mais coerentes com o contexto, motivação e reações reais observadas nas entrevistas.

* **Melhoria no Cenário:** Alterar o desfecho/narrativa para incluir um indicativo visual claro (como um alerta/sino) logo após o login da Camila, reforçando como a descoberta do botão alivia o esforço mental.
* **Cenário Alternativo:** Redigir um breve "Cenário Alternativo" abordando um usuário com check-up de rotina sem urgência médica, contemplando os relatos casuais validados.

### 5.4. Priorização das Refatorações

| Prioridade | Artefato a ser Atualizado | Problema Relacionado |
| --- | --- | --- |
| Alta | Revisão Matemática do Modelo GOMS/KLM | P01 |
| Alta | Proposta Visual/Cenário ("Últimos Resultados" + Notificações) | P02 |
| Média | Criação de Cenário Secundário (Perfil Casual) | P03 |
| Média | Refatoração da Ramificação T4 no HTA | P04 |

### 5.5. Considerações Finais
As três entrevistas confirmaram que o modelo primário proposto na Análise de Tarefas é funcional e reflete corretamente a jornada da maioria. Entretanto, identificou-se que o usuário valoriza soluções que economizam busca visual e minimizem atrasos de carregamento. As atualizações nos documentos refletirão um leque mais abrangente de emoções e garantirão que a etapa de prototipação seja embasada por requisitos de visibilidade mais rígidos.

---

## Referência Bibliográfica

> BARBOSA, S. D. J. et al. Interação Humano-Computador e Experiência do Usuário. 1. ed. Rio de Janeiro: Autopublicação, 2021.

---

## Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 31/05/2026 | Criação do relato sobre obtenção de laudo de exame online contemplando três participantes | Ingrid Alves Rocha | - | Revisão do relato | - |
