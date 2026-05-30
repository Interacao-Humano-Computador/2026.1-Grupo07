# Planejamento da Avaliação da Análise de Tarefas - Visualizador DICOM

Este documento estabelece o plano de avaliação específico para os artefatos de Cenário, Análise de Tarefas (HTA e CTT) e o Storyboard associados à funcionalidade do Visualizador DICOM web do Portal Sabin. A metodologia segue a abordagem de investigação por meio de Entrevistas.

## Tabela de contribuição
| Artefato(s) | Autor(es) |
| :--- | :--- |
| Página de Avaliação da Análise de Tarefas | Philipe Amâncio |

## 1. Preparação
Nesta etapa inicial, definem-se os elementos organizacionais, perfis e materiais necessários para a realização das sessões de avaliação.

* **Definição da Tarefa:** Utilizar o Visualizador DICOM web de forma fluida no Portal Sabin, acessando as imagens do próprio exame para visualização pessoal utilizando navegação básica (como rolagem e zoom).
* **Definição do Perfil dos Participantes:** Pacientes (usuários leigos) que já realizaram exames de imagem de alta complexidade (Ressonância Magnética ou Tomografia Computadorizada) e possuem o hábito de acessar resultados online.
* **Preparação dos Artefatos:** Consolidação impressa ou digital dos modelos para apresentação ao usuário:
    * **Cenário:**Descrição textual focada na jornada do paciente em casa. Abordará a curiosidade ao receber a notificação de que o exame está pronto e a vontade de se informar melhor para a consulta de retorno. O foco será no novo comportamento de acessar os resultados completos (o laudo em texto e as imagens) para submetê-los a ferramentas de Inteligência Artificial, buscando um pré-entendimento para acompanhar e compreender com clareza as explicações que o médico dará.
    * **Storyboard:** Ilustrando visualmente a curiosidade do paciente ao tentar visualizar a imagem do exame após ler o pré-diagnóstico.
    * **HTA e CTT:** Diagramas detalhando a interação direta do usuário com a interface do visualizador, mapeando a alternância entre as tarefas de análise e a utilização concorrente das ferramentas de manipulação em tela.
* **Execução do Teste-Piloto:** Será conduzida uma simulação completa da entrevista com um membro da equipe antes das sessões oficiais. Esta etapa serve para validar a clareza de todos os artefatos, garantir que a linguagem não está técnica demais para um leigo e cronometrar o roteiro. O resultado não será incorporado ao relatório final.

## 2. Coleta de Dados
A coleta de dados será realizada de forma **presencial**. Durante a sessão, o participante analisará os artefatos de forma sequencial enquanto responde a uma entrevista semiestruturada.

**Organização e Papéis da Equipe**

* **Avaliador/Condutor:** Philipe Amancio

**Roteiro de Entrevista para a Coleta**

**Fase A: Perfil e Aquecimento**

* Qual é o seu nome, idade e profissão?
* Como você avalia a sua facilidade no uso de tecnologia, sites e aplicativos de saúde no seu dia a dia?
* Quando você faz um exame, você costuma acessar o portal do laboratório para ver o resultado antes de voltar ao médico, ou prefere esperar a consulta?

**Fase B: Validação do Cenário**

* Ao ler a descrição em texto deste cenário, a situação descrita retrata a realidade da sua rotina?
* O cenário cita o uso de Inteligência Artificial para ajudar a "traduzir" o laudo. Esse novo comportamento de usar a IA incentiva você a acessar suas próprias imagens e resultados antes de falar com o médico? 

**Fase C: Validação do Storyboard**

* Ao observar esta história em quadrinhos que ilustra o paciente acessando e tentando entender a imagem do exame, ela reflete o que você faria na prática?
* A forma como o personagem interage com o portal para baixar ou salvar a imagem para levar na próxima consulta condiz com a sua expectativa?

**Fase D: Validação de HTA (Análise Hierárquica de Tarefas)**

* Analisando o passo a passo que desenhamos para "Acessar a Imagem do Exame", essa sequência lógica parece natural para você como paciente?
* Há alguma etapa, como "instalar plugin" ou "ajustar configurações avançadas", que você acharia muito complicada ou desnecessária para o seu uso?
* Você sente falta de algum passo essencial?

**Fase E: Validação de CTT (ConcurTaskTrees)**

* Neste diagrama, indicamos que você pode alternar entre "Ler o Laudo (texto)" e "Visualizar a Imagem" a qualquer momento. Na prática, você costuma ler o laudo primeiro para tentar entender, ou vai direto olhar a imagem?
* Mapeamos que ferramentas como "Dar zoom" e "Ajustar Contraste" estão disponíveis. Como paciente, você usaria essas ferramentas por curiosidade, ou acha que elas deveriam ficar escondidas apenas para o médico usar?
* Ao terminar de ver a imagem, nós colocamos a ação de simplesmente "Fechar". Você sentiria a necessidade de um aviso confirmando que "O arquivo já está salvo no seu histórico"?

## 3. Interpretação
Logo após a realização de cada entrevista, os dados brutos coletados (anotações de campo e vídeos gravados) serão analisados pela equipe.

* **Listagem de Problemas:** O avaliador e o anotador devem compilar todas as quebras de expectativa identificadas pelo paciente (ex: jargões médicos incompreensíveis, excesso de opções técnicas na tela que geram confusão, passos invertidos no HTA).
* **Refinamento dos Modelos:** Caso o participante apresente uma crítica clara (ex: "eu não sei o que é DICOM, deveria se chamar 'Ver Imagem'"), o texto do Cenário, o Storyboard e os diagramas HTA/CTT serão refinados de maneira iterativa.

## 4. Consolidação dos Resultados
Nesta etapa, as observações são unificadas para gerar insumos acionáveis focados em acessibilidade leiga.

* **Priorização das Correções:** Todos os problemas de usabilidade, como barreiras de entendimento técnico ou falhas na lógica de navegação do paciente, serão tabulados e classificados por severidade.
* **Sugestão de Correções:** Proposição de modificações claras na estrutura, como ocultar ferramentas clínicas complexas (medição, densidade) do perfil de paciente e destacar botões úteis (como "Download PDF" ou "Compartilhar").

## 5. Relato dos Resultados
Os achados finais serão estruturados em um relatório de resultados formalizado, contendo obrigatoriamente:

* Os objetivos gerais da avaliação focada no paciente;
* A descrição detalhada do método de investigação utilizado;
* O número exato e o perfil dos pacientes participantes;
* Os cenários e as tarefas apresentados;
* Uma lista detalhada de todos os problemas encontrados (separados por artefato);
* O feedback geral sobre a curva de aprendizado da ferramenta pelo leigo.