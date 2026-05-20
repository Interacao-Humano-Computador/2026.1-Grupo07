# Planejamento da Avaliação da Análise de Tarefas - Acompanhamento de Resultados e Download de Laudos

## Rastreabilidade
|Artefato(s) | Autore(s)|
| --- | --- |
| Página de Avaliação da Análise de Tarefas - Download de Laudos | Ingrid |

Este documento estabelece o plano de avaliação para os artefatos de **Cenário**, **Análise Hierárquica de Tarefas (HTA)** e **Análise GOMS (KLM)** associados à funcionalidade de **Visualização e Download de Laudos de Exame** do Portal Sabin. A metodologia segue a abordagem de investigação por meio de **Entrevistas**.

---

## 1. Preparação

Nesta etapa inicial, definem-se os elementos organizacionais, perfis e materiais necessários para a realização das sessões de avaliação.

* **Definição da Tarefa:** Fluxo de **Visualização e Download de Laudo de Exame**, compreendendo desde a autenticação no portal via Token SMS, a localização do exame de interesse na seção "Últimos Resultados", o download do PDF do laudo e o compartilhamento do documento com o profissional de saúde via aplicativo de mensagens.
* **Definição do Perfil dos Participantes:** Pacientes ou clientes do laboratório que realizam exames com frequência, possuem familiaridade alta com dispositivos móveis (smartphones) e que costumam acessar portais de laboratórios para consultar e baixar resultados de exames. O perfil ideal é de pessoas que já tenham vivenciado situações de acompanhamento recorrente (como pré-natal, tratamentos contínuos ou check-ups periódicos).
* **Preparação dos Artefatos:** Consolidação dos seguintes modelos conceituais para apresentação ao usuário:
    * *Cenário:* Descrição textual narrativa detalhada que contextualiza o ambiente, os atores (Camila Fernandes, gestante de 24 semanas), os objetivos e as motivações do mundo real que disparam o uso da funcionalidade de download de laudos.
    * *HTA (Análise Hierárquica de Tarefas):* Diagrama com o objetivo principal "Obter laudo de exame online" decomposto em subobjetivos (Autenticação, Localizar exame, Baixar PDF e Compartilhar documento), incluindo os planos de execução sequenciais e a tabela de problemas e recomendações.
    * *GOMS (KLM):* Análise quantitativa que estima o tempo de execução do fluxo de download de laudo (aproximadamente 8,50 segundos para um usuário já logado), detalhando cada operação primitiva adaptada para interação mobile.
* **Execução do Teste-Piloto:** Será conduzida uma simulação completa da entrevista com um membro da equipe antes das sessões oficiais. Esta etapa serve para validar a clareza de todos os artefatos (incluindo a narrativa do cenário), o vocabulário utilizado e o tempo de resposta do roteiro. *O resultado do teste-piloto não será incorporado ao relatório final de resultados.*

---

## 2. Coleta de Dados

A coleta de dados será realizada de forma **presencial**, em ambiente reservado para o participante. Durante a sessão, o participante analisará os artefatos de forma sequencial enquanto responde a uma entrevista semiestruturada.

### Organização e Papéis da Equipe
* **Avaliador/Condutor:** Ingrid Alves
* **Anotador:** [A definir]
* **Cinegrafista:** [A definir]

### Roteiro de Entrevista para a Coleta

#### Fase A: Perfil e Aquecimento
1. Qual seu nome, idade e ocupação atual?
2. Como você avalia sua experiência com portais de laboratórios para consulta de resultados de exames?
3. Com que frequência você acessa plataformas online para visualizar ou baixar laudos de exames?
4. Qual dispositivo você mais utiliza para acessar resultados de exames (celular, computador, tablet)?

#### Fase B: Validação do Cenário
5. Ao ler a descrição deste cenário de uso, essa situação — uma paciente frequente acessando o portal para conferir se o resultado de um exame importante já foi liberado — retrata com fidelidade uma experiência que você já viveu ou considera realista?
6. As motivações descritas para a atora (Camila), como a ansiedade pelo resultado e a necessidade de enviar o laudo para a médica rapidamente, condizem com sentimentos que você já experimentou ao aguardar resultados?
7. A frustração descrita no cenário, de precisar baixar múltiplos PDFs separados em vez de um arquivo único consolidado, é algo que você considera um problema real na sua experiência?

#### Fase C: Validação da HTA
8. Analisando a decomposição do objetivo "Obter laudo de exame online" nos subpassos apresentados (autenticação → localizar exame → baixar PDF → compartilhar), essa sequência reflete a sua linha de raciocínio ao buscar um resultado?
9. Há alguma etapa apresentada nesta hierarquia que você considera redundante ou desnecessária na prática?
10. Sente falta de algum passo ou verificação intermediária essencial que não foi incluído no fluxo? Por exemplo, alguma ação que você costuma realizar entre localizar o exame e baixá-lo?
11. A etapa de "Compartilhar o documento" (selecionar opção de compartilhamento e enviar via WhatsApp) deveria ser uma funcionalidade integrada ao próprio portal, ou o fluxo atual via sistema nativo do celular é satisfatório?

#### Fase D: Validação de GOMS / KLM (Eficiência)
12. Apresentamos uma estimativa de tempo de aproximadamente 8,5 segundos para a tarefa de localizar um exame recente e baixar o PDF (considerando o usuário já logado). Essa estimativa parece condizente com a sua experiência real ao realizar essa tarefa?
13. Em sua opinião, o principal gargalo de tempo nesse fluxo está na resposta do sistema (carregamento de páginas e geração do PDF) ou na dificuldade de encontrar as informações na tela?
14. Você considera que a seção "Últimos Resultados" deveria estar visível logo na primeira tela após o login, sem necessidade de rolar a página?

---

## 3. Interpretação

Logo após a realização de cada entrevista, os dados brutos coletados (anotações de campo e vídeos gravados) serão analisados de forma qualitativa pela equipe.

* **Listagem de Problemas:** O avaliador e o anotador devem compilar todas as quebras de expectativa identificadas pelo participante (ex: frustração com múltiplos PDFs, dificuldade de localizar a seção de resultados, insatisfação com a falta de status visual claro do exame, problemas na etapa de compartilhamento).
* **Refinamento dos Modelos:** Caso o participante apresente uma crítica estrutural clara ou sugira uma melhoria, o texto do Cenário e os diagramas HTA serão refinados de maneira iterativa pela equipe com base nos feedbacks coletados.

---

## 4. Consolidação dos Resultados

Nesta etapa, as observações individuais coletadas nas entrevistas são unificadas para gerar insumos acionáveis.

* **Priorização das Correções:** Todos os problemas de usabilidade, inadequações de contexto do cenário ou falhas na lógica de tarefas encontrados serão tabulados e classificados por severidade. É dever crítico da equipe **priorizar a correção dos problemas que não foram resolvidos** durante a fase de refinamento imediato.
* **Sugestão de Correções:** Proposição de modificações claras na narrativa do cenário ou na estrutura de tarefas (ex: consolidação de downloads em arquivo único, reposicionamento da seção de resultados na primeira dobra da tela, adição de botão de compartilhamento integrado) com base nas evidências empíricas coletadas.

---

## 5. Relato dos Resultados

Os achados finais serão estruturados em um relatório de resultados formalizado. Para garantir a conformidade metodológica em IHC, a estrutura do relato conterá obrigatoriamente:

1. Os objetivos gerais da avaliação;
2. A descrição detalhada do método de investigação utilizado (Entrevista baseada em artefatos);
3. O número exato e o perfil dos avaliadores e dos participantes envolvidos;
4. Os cenários e as tarefas apresentados aos participantes;
5. Um sumário dos dados (comparativo entre a estimativa GOMS/KLM e a experiência real do usuário);
6. Uma lista detalhada e hierarquizada de todos os problemas encontrados (separados por artefato: Cenário, HTA ou KLM);
7. O feedback geral e qualitativo fornecido pelos usuários.

## Cronograma das Sessões Oficiais
| Responsável pela Sessão | Participante | Tarefa | Data | Horário | Local de Realização |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Ingrid Alves** | [Nome do Participante] | Visualização e Download de Laudo | DD/MM/AAAA | 00:00 - 00:00 | [Presencial - Local a definir] |

## Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 19/05/2026 | Criação do plano de avaliação focado em Cenário, HTA e GOMS/KLM | [Ingrid Alves](https://github.com/alvesingrid) | 19/05/2026 | Ajuste do padrão do histórico de versão | [Hugo Freitas Silva](https://github.com/HugoFreitass) |