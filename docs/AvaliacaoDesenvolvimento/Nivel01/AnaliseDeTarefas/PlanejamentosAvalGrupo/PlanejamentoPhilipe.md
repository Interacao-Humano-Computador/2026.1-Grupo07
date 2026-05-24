
# Planejamento da Avaliação da Análise de Tarefas - Visualizador DICOM

Este documento estabelece o plano de avaliação específico para os artefatos de **Cenário**, **Análise de Tarefas (HTA e CTT)** e o **Storyboard** associados à funcionalidade do Visualizador DICOM web do Portal Sabin. A metodologia segue a abordagem de investigação por meio de **Entrevistas**.

## Tabela de contribuição
|Artefato(s) | Autor(es)|
| --- | --- |
| Página de Avaliação da Análise de Tarefas  | [Philipe Amâncio](https://github.com/Phill-Chill) |

---

## 1. Preparação

Nesta etapa inicial, definem-se os elementos organizacionais, perfis e materiais necessários para a realização das sessões de avaliação.

* **Definição da Tarefa:** Utilizar o Visualizador DICOM web de forma fluida no Portal Sabin (caminho feliz / fluxo de sucesso), realizando a manipulação básica de imagens médicas (como rolagem de fatias e ajuste de contraste) para apoiar a tomada de decisão clínica.
* **Definição do Perfil dos Participantes:** Médicos clínicos ou especialistas que utilizem exames de imagem de alta resolução (Ressonância Magnética ou Tomografia Computadorizada) para fechar diagnósticos.
* **Preparação dos Artefatos:** Consolidação impressa ou digital dos seguintes modelos estruturais e conceituais para apresentação ao usuário:
    * *Cenário:* Descrição textual narrativa detalhada que contextualiza o ambiente, os atores, os objetivos e as motivações do mundo real que disparam o uso da funcionalidade.
    * *Storyboard:* Sequência em quadrinhos ilustrando visualmente o fluxo de uso do DICOM pelo médico durante a consulta.
    * *HTA (Análise Hierárquica de Tarefas):* Diagrama com objetivos, subobjetivos e planos de execução sequenciais da tarefa.
    * *CTT (ConcurTaskTrees):* Diagrama detalhando a concorrência e a distribuição de tarefas lógicas entre o médico e o sistema.
* **Execução do Teste-Piloto:** Será conduzida uma simulação completa da entrevista com um membro da equipe antes das sessões oficiais. Esta etapa serve para validar a clareza de todos os artefatos (incluindo a narrativa do cenário), o vocabulário técnico e o tempo de resposta do roteiro. *O resultado do teste-piloto não será incorporado ao relatório final de resultados.*

---

## 2. Coleta de Dados

A coleta de dados será realizada de forma **presencial**, em ambiente reservado para o profissional de saúde. Durante a sessão, o participante analisará os artefatos de forma sequencial enquanto responde a uma entrevista semiestruturada.

### Organização e Papéis da Equipe
* **Avaliador/Condutor:** Philipe Amancio 
* **Anotador:** [?]
* **Cinegrafista:** [?] 

### Roteiro de Entrevista para a Coleta

#### Fase A: Perfil e Aquecimento
1. Qual é o seu nome, idade e especialidade médica atual?
2. Como você avalia a sua experiência com prontuários eletrônicos e sistemas hospitalares no seu dia a dia clínico?
3. Com qual frequência você precisa analisar exames de imagem diretamente em portais de laboratórios durante seus atendimentos?

#### Fase B: Validação do Cenário
4. Ao ler a descrição em texto deste cenário de uso, essa situação de atendimento, o ambiente da clínica e a pressão de tempo do médico retratam com fidelidade a realidade da sua rotina de trabalho?
5. As motivações e necessidades descritas para o ator (Dr. Roberto) ao buscar as imagens condizem com os gatilhos reais que fazem você abrir um exame DICOM no meio de uma consulta?

#### Fase C: Validação do Storyboard
6. Ao observar esta história em quadrinhos que ilustra graficamente a utilização do visualizador DICOM, reflete o fluxo ideal para as suas consultas?
7. A forma como o médico interage visualmente com a interface do portal e com o paciente, mostrando o exame diretamente na tela do computador, condiz com o que você espera na prática?

#### Fase D: Validação de HTA
8. Analisando a divisão do objetivo "Utilizar o DICOM" nestes subpassos e planos sequenciais, essa decomposição hierárquica reflete a sua linha de raciocínio clínico?
9. Há alguma ação apresentada nesta hierarquia que você considera redundante, burocrática ou desnecessária?
10. Sente falta de algum passo ou verificação intermediária essencial que esquecemos de incluir no fluxo lógico?

#### Fase E: Validação de CTT
11. Neste modelo CTT, indicamos que você pode alternar livremente entre "Ler Laudo" e "Visualização da imagem" a qualquer momento (representado pelo símbolo |||). Na sua rotina diagnóstica, você costuma analisar ambos simultaneamente/alternadamente ou prefere focar em um de cada vez?
12. Mapeamos que, após "Ativar o DICOM", você pode usar as ferramentas de "Ajustar Contraste", "Dar zoom" e "Realizar Medições" em qualquer ordem e de forma livre. Na prática, existe alguma dessas ações que você faz obrigatoriamente antes das outras (ex: sempre ajustar o contraste primeiro), ou o uso é realmente independente?
13. Nós colocamos a ação de "Encerrar" podendo interromper a visualização dos dados a qualquer momento. Você sente falta de alguma ação que devesse acontecer antes de fechar a tela, como salvar as medições realizadas ou exportar uma imagem?

---

## 3. Interpretação

Logo após a realização de cada entrevista, os dados brutos coletados (anotações de campo e vídeos gravados) serão analisados de forma qualitativa pela equipe.

* **Listagem de Problemas:** O avaliador e o anotador devem compilar todas as quebras de expectativa identificadas pelo médico (ex: inadequações no contexto do cenário, termos clínicos ambíguos, passos invertidos na árvore HTA ou lógica de concorrência falha no CTT).
* **Refinamento dos Modelos:** Caso o participante apresente uma crítica estrutural clara ou sugira uma melhoria óbvia, o texto do Cenário, os quadrinhos do Storyboard e os diagramas HTA e CTT serão refinados de maneira imediata e iterativa pela equipe no papel antes da consolidação final.

---

## 4. Consolidação dos Resultados

Nesta etapa, as observações individuais coletadas nas entrevistas são unificadas para gerar insumos acionáveis direcionados ao time de engenharia de software e design de interface (UI).

* **Priorização das Correções:** Todos os problemas de usabilidade, inadequações de contexto do cenário ou falhas na lógica de tarefas encontrados serão tabulados e classificados por severidade. É dever crítico da equipe **priorizar a correção dos problemas que não foram resolvidos** durante a fase de refinamento imediato.
* **Sugestão de Correções:** Proposição de modificações claras na narrativa do cenário ou na estrutura de tarefas (ex: agrupar ferramentas de manipulação afins, simplificar os cliques necessários para entrar em modo tela cheia) com base nas evidências empíricas coletadas.

---

## 5. Relato dos Resultados

Os achados finais serão estruturados em um relatório de resultados formalizado. Para garantir a conformidade metodológica em IHC, a estrutura do relato conterá obrigatoriamente:

1. Os objetivos gerais da avaliação;
2. A descrição detalhada do método de investigação utilizado (Entrevista baseada em Modelos);
3. O número exato e o perfil dos avaliadores e dos participantes clínicos envolvidos;
4. Os cenários e as tarefas apresentados aos participantes;
5. Uma lista detalhada e hierarquizada de todos os problemas encontrados (separados por artefato: Cenário, Storyboard, HTA ou CTT);
6. O feedback geral e qualitativo fornecido pelos usuários.

## Cronograma das Sessões Oficiais
| Responsável pela Sessão | Participante | Tarefa | Data | Horário | Local de Realização |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Philipe Amancio** | [Nome do Médico] | Utilizar o Visualizador DICOM | DD/MM/AAAA | 00:00 - 00:00 | [Ex: Consultório do Participante] |

## Referências Bibliográficas

* **BARBOSA, S. D. J.; SILVA, B. S. (2011).** *Interação Humano-Computador*. Rio de Janeiro: Elsevier.

## Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 19/05/2026 | Criação do plano específico com validação de cenário | [Philipe Amancio](https://github.com/Phill-Chill) | 19/05/2026 | Revisão da estrutura inicial e adequação ao framework DECIDE | [Hugo Freitas Silva](https://github.com/HugoFreitass) |