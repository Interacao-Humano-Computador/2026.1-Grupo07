# Planejamento da Avaliação da Análise de Tarefas - Agendamento de Exame no Site Sabin

## Tabela de Contribuição

|Artefato(s) | Autor(es)|
| --- | --- |
| Página de Planejamento da Avaliação da Tarefa de Agendamento de Exame | [Hugo Freitas Silva](https://github.com/HugoFreitass) |

# Introdução
Este documento estabelece o plano de avaliação específico para os artefatos de **Cenário**, **Análise de Tarefas (HTA e GOMS)** e o **Storyboard** associados à funcionalidade de **Agendamento de Exames Laboratoriais** do Portal Sabin. A metodologia segue a abordagem de investigação por meio de **Entrevistas**.

---

# 1. Preparação

Nesta etapa inicial, definem-se os elementos organizacionais, perfis e materiais necessários para a realização das sessões de avaliação.

* **Definição da Tarefa:**  
O usuário deverá realizar o processo completo de agendamento de um exame laboratorial no portal do Sabin, iniciando pelo acesso ao site, passando pela busca e seleção do exame desejado, escolha da unidade e do horário disponível, preenchimento ou validação dos dados pessoais e finalizando na confirmação do agendamento. O fluxo avaliado considera o caminho principal (“happy path”), assumindo que o usuário consegue concluir todas as etapas sem falhas críticas do sistema.

* **Definição do Perfil dos Participantes:**  
Os participantes selecionados deverão representar usuários reais do portal de exames laboratoriais, especialmente pessoas que já utilizam serviços de saúde digitais para marcação de consultas ou exames. O perfil priorizado inclui adultos com experiência intermediária no uso de sistemas web, que realizam exames laboratoriais com frequência ocasional ou recorrente. Também serão considerados participantes com menor familiaridade tecnológica para avaliar dificuldades relacionadas à busca de exames, compreensão do fluxo e preenchimento de formulários.

* **Preparação dos Artefatos:**  
Consolidação impressa ou digital dos seguintes modelos estruturais e conceituais para apresentação ao usuário:

    * *Cenário:* Descrição textual narrativa detalhada contextualizando um usuário que precisa agendar um exame laboratorial no portal Sabin devido a uma solicitação médica, considerando limitações de tempo, necessidade de encontrar rapidamente o exame correto e seleção de uma unidade conveniente.

    * *Storyboard:* Sequência visual ilustrando o usuário acessando o portal, buscando o exame, enfrentando dificuldades de identificação dos termos técnicos, escolhendo unidade e horário e concluindo o agendamento.

    * *HTA (Análise Hierárquica de Tarefas):* Diagrama contendo a decomposição hierárquica da tarefa “Agendar exame laboratorial online”, incluindo os subobjetivos de acesso ao site, busca de exames, escolha de unidade/horário, preenchimento de dados e confirmação.

    * *GOMS:* Modelo representando os objetivos, operadores, métodos e regras de seleção utilizados por usuários experientes durante a execução do fluxo de agendamento, incluindo a análise KLM estimando o tempo de execução da tarefa.

* **Execução do Teste-Piloto:**  
Será conduzida uma simulação completa da entrevista com um membro da equipe antes das sessões oficiais. Esta etapa servirá para validar a clareza dos modelos HTA e GOMS, a compreensão do cenário narrativo, a interpretação do storyboard e a objetividade das perguntas da entrevista. O teste-piloto também verificará se os participantes conseguem compreender os operadores e métodos descritos no modelo GOMS sem ambiguidades.

> O resultado do teste-piloto não será incorporado ao relatório final de resultados.

---

# 2. Coleta de Dados

A coleta de dados será realizada de forma **presencial**, em ambiente reservado para o usuário. Durante a sessão, o participante analisará os artefatos de forma sequencial enquanto responde a uma entrevista semiestruturada.

## Organização e Papéis da Equipe

* **Avaliador/Condutor:** [Hugo Freitas Silva](https://github.com/HugoFreitass)
* **Anotador:** [Philipe Amancio](https://github.com/Phill-Chill)
* **Cinegrafista:** Usaremos tripé

---

## Roteiro de Entrevista para a Coleta

### Fase A: Perfil e Aquecimento

1. Qual é o seu nome, idade e ocupação atual?
2. Como você avalia sua experiência com sistemas de agendamento online?
3. Com qual frequência você utiliza plataformas digitais para marcar exames, consultas ou procedimentos médicos?

---

### Fase B: Validação do Cenário

4. Ao ler este cenário de uso, a situação apresentada representa adequadamente a realidade de quem precisa agendar exames laboratoriais?
5. As dificuldades apresentadas no cenário, como encontrar o exame correto e escolher horários disponíveis, refletem problemas reais da sua experiência?
6. Você acredita que as motivações do personagem para usar o portal fazem sentido dentro do contexto de exames laboratoriais?

---

### Fase C: Validação do Storyboard

7. O storyboard representa adequadamente o fluxo de interação esperado para o agendamento de exames?
8. A sequência visual demonstra de forma clara as etapas mais importantes da tarefa?
9. Você identifica alguma etapa confusa, desnecessária ou ausente na representação visual?

---

### Fase D: Validação da HTA

10. A decomposição da tarefa “Agendar exame laboratorial online” em subetapas representa corretamente sua forma de pensar durante o processo?
11. A ordem das etapas parece lógica e natural?
12. Existe alguma etapa importante que deveria ter sido incluída na análise hierárquica?
13. Você considera alguma ação redundante, burocrática ou excessivamente complexa?

---

### Fase E: Validação do GOMS

14. O modelo apresentado representa corretamente como um usuário experiente executaria essa tarefa?
15. A etapa de busca do exame parece exigir esforço cognitivo elevado?
16. A escolha de unidade e horário exige muita atenção ou comparação de informações?
17. O preenchimento dos dados pessoais parece ser um ponto propenso a erros?
18. O fluxo descrito pelo modelo GOMS parece eficiente ou existem etapas que poderiam ser reduzidas?
19. O uso de preenchimento automático ajudaria significativamente nesse processo?
20. O feedback apresentado após a confirmação do agendamento parece suficiente para transmitir segurança ao usuário?

---

# 3. Interpretação

Logo após a realização de cada entrevista, os dados brutos coletados (anotações de campo e vídeos gravados) serão analisados de forma qualitativa pela equipe.

* **Listagem de Problemas:**  
A equipe deverá compilar todos os problemas identificados durante a validação dos artefatos, incluindo:

    * dificuldades de compreensão do cenário;
    * inconsistências no storyboard;
    * etapas ausentes ou mal estruturadas na HTA;
    * excesso de carga cognitiva identificado no GOMS;
    * problemas relacionados à busca de exames;
    * dificuldades na escolha de unidade e horário;
    * falhas de feedback do sistema;
    * etapas propensas a erro no preenchimento de dados.

* **Refinamento dos Modelos:**  
Caso os participantes apresentem críticas estruturais claras ou sugiram melhorias relevantes, os modelos serão refinados iterativamente pela equipe. As alterações poderão incluir:

    * reorganização das tarefas da HTA;
    * simplificação dos métodos do GOMS;
    * melhoria da narrativa do cenário;
    * ajustes no storyboard para representar melhor dificuldades reais de uso.

---

# 4. Consolidação dos Resultados

Nesta etapa, as observações individuais coletadas nas entrevistas serão unificadas para gerar insumos acionáveis direcionados ao time de engenharia de software e design de interface (UI).

* **Priorização das Correções:**  
Todos os problemas identificados serão classificados por severidade e impacto na experiência do usuário. Problemas relacionados à busca de exames, clareza do fluxo, excesso de cliques e carga cognitiva terão prioridade elevada devido ao impacto direto na eficiência da tarefa.

* **Sugestão de Correções:**  
Serão propostas melhorias como:

    * aprimoramento do mecanismo de busca de exames;
    * redução da quantidade de interações necessárias;
    * reorganização visual das opções de unidade e horário;
    * implementação de preenchimento automático;
    * melhoria dos feedbacks de confirmação;
    * simplificação das etapas críticas do fluxo.

---

# 5. Relato dos Resultados

Os achados finais serão estruturados em um relatório de resultados formalizado. Para garantir a conformidade metodológica em IHC, a estrutura do relato foi definida detalhadamente e pode ser encontrada neste documento: 

### Link para o planejamento do relato dos resultados:
[Planejamento do Relato dos Resultados da Avaliação da Análise de Tarefas](../PlanejamentoDosResultados.md)

---

# Cronograma das Sessões Oficiais

| Responsável pela Sessão | Participante | Data | Horário | Local de Realização |
| :--- | :--- | :--- | :--- | :--- |
| [Hugo Freitas Silva](https://github.com/HugoFreitass) | Pedro Henrique Ferreira Xavier | 26/05/2026| 12:10 - 12:40 | UnB - FCTE (sala s9) |

---

## Referências Bibliográficas

> BARBOSA, S. D. J. et al. Interação Humano-Computador e Experiência do Usuário. 1. ed. Rio de Janeiro: Autopublicação, 2021.

# Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 19/05/2026  | Criação do plano focado em Cenário, Storyboard, HTA e GOMS |  [Hugo Freitas Silva](https://github.com/HugoFreitass) | - | - | [Maria Laura Regis](https://github.com/Maria-Laura-Regis) |
| 1.1 | 23/05/2026  | Adição da tabela de contribuidores e referências para o planejamento do relato dos resultados |  [Hugo Freitas Silva](https://github.com/HugoFreitass) | 24/05/2026 | - | [Philipe Amancio](https://github.com/Phill-Chill) |