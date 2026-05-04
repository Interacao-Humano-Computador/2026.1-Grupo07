## Introdução

Uma **persona** é um personagem fictício e um arquétipo hipotético que representa um grupo de usuários reais, criada com o objetivo de descrever um usuário típico do sistema. Sua principal função é materializar o público-alvo durante as discussões de design, garantindo que toda a equipe técnica e de negócios mantenha o foco no mesmo alvo, evitando abstrações. Essas representações são construídas e definidas fundamentalmente por seus objetivos, que são lapidados por meio de refinamentos sucessivos durante a investigação do domínio do usuário <span class="hover-image">(BARBOSA et al., 2021)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/image-26.png" alt="Print"> </span>.

A criação de personas serve para combater o problema do "usuário elástico", um termo genérico e impreciso que frequentemente resulta em sistemas confusos, que tratam a mesma pessoa ora como iniciante, ora como especialista, conforme a conveniência da programação. Tentar ampliar a funcionalidade de um produto para agradar a todos os pontos de vista costuma colocar obstáculos na jornada, interferindo no desempenho e arruinando a experiência. Por isso, em vez de criar um sistema genérico que se diz "amigável para o usuário", o design eficiente exige projetar para uma persona bem específica, garantindo que o sistema se adapte às necessidades dela, e não o contrário <span class="hover-image">(BARBOSA et al., 2021)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/image-27.png" alt="Print"> </span>.



## Persona 1: 

> ### Roberto (Médico Clínico Geral)

| Categoria | Detalhes do Perfil |
| :--- | :--- |
|**Foto**| ![alt text](../assets/image-28.png){width="600"}|
| **Identidade** | **Nome:** Roberto <br> **Idade:** 36 anos <br> **Sexo:** Masculino <br> **Localização:** Brasília, DF <br> **Status Socioeconômico:** Classe Alta <br> **Status na Pesquisa:** Persona Primária |
| **Perfil Geral** | Médico clínico geral extremamente ocupado (atende 1 paciente a cada 20/30 min). Acessa o sistema durante a consulta, com o paciente à frente, para verificar exames e decidir a conduta médica de forma ágil e segura. |
| **Educação e Aprendizado** | **Formação:** Graduação em Medicina <br> **Nível de Leitura / Digital:** Alto / Alta facilidade <br> **Preferência de Aprendizado:** Explorar sozinho (Prático). <br> **Observação:** Exige sistemas intuitivos; delega o uso de manuais à secretária. |
| **Experiência Profissional** | **Cargo:** Clínico Geral (12 anos na área, 8 anos na clínica atual). <br> **Responsabilidades:** Diagnóstico, prescrição e acompanhamento de crônicos. <br> **Plano de Carreira:** Expandir pacientes particulares e focar em medicina preventiva. |
| **Relação com Tecnologia** | **Nível:** Médio a Alto (>10 anos de uso no trabalho). <br> **Dispositivos:** Smartphone, Notebook e Desktop de última geração. <br> **Sistemas:** Prontuário eletrônico, prescrição digital, WhatsApp. <br> **Conexão:** Wi-Fi de alta velocidade na clínica (não tem tempo para acionar suporte TI). |
| **Experiência com Sistemas** | **Uso Atual:** Acessa portais de laboratórios periodicamente ao longo do dia. <br> **Pontos Positivos:** Visualizadores DICOM rápidos direto no navegador. <br> **Frustrações:** Falta de responsividade celular, múltiplos cliques, reautenticação constante. <br> **Preferência:** Autenticação biométrica (FaceID) e botões de ação (ex: "Baixar Laudo") em destaque. |
| **Objetivos** | **Finais:** Acessar laudos 100% digitais, ver imagens em alta resolução e tomar decisões precisas. <br> **De Experiência:** Sentir-se ágil, moderno e sem estresse tecnológico (luta contra interface). <br> **De Vida:** Ser reconhecido como resolutivo e manter equilíbrio pessoal/profissional (não sair tarde do consultório por atrasos no sistema). |
| **Habilidades e Tarefas** | **Competências:** Interpretação clínica, patologia, radiologia e farmacologia (Autonomia Total). <br> **Tarefas Críticas:** Buscar pacientes por CPF/lista (Alta frequência) e analisar gráficos de evolução. <br> **Tarefas Secundárias:** Imprimir 2ª via de laudo. |
| **Relacionamentos** | **Interações:** Pacientes, especialistas e secretárias. <br> **Influência:** É um grande influenciador (Stakeholder indireto), pois indica aos pacientes o laboratório que possui o portal mais fácil para ele utilizar. |
| **Requisitos e Expectativas** | **Necessidades:** Acesso rápido, histórico do paciente, visualizador integrado e comparação lado a lado. <br> **Modelo Mental:** O sistema deve ser organizado na hierarquia *"Paciente > Histórico de Exames"* de carregamento instantâneo. |
| **Atitudes e Tolerância** | **Perfil:** Aberto a novas tecnologias, prefere simplicidade e controle avançado. <br> **Tolerância a falhas:** Baixíssima (Zero tolerância para inoperância comercial). <br> **Comportamento no Erro:** Impaciente. Se demorar, desiste e manda a secretária ligar para cobrar. |
| **Domínio e Vocabulário** | **Domínio do Tema:** Altíssimo (é a autoridade máxima na consulta). <br> **Idiomas:** Português nativo, Inglês técnico. <br> **Jargões:** CID-10, termos anatômicos, VHS, TGO, TGP. |
| **Citação Representativa** | *"Eu só preciso ver o resultado do hemograma e a imagem da ressonância agora. Se o sistema me pedir para trocar a senha ou preencher um formulário longo, eu perco o tempo da consulta."* |


## Persona 2: 

> ### Márcia (Mãe e Gestora da Saúde Familiar)

| Categoria | Detalhes do Perfil |
| :--- | :--- |
|**Foto**| ![alt text](../assets/image-marcia.png){width="600"}|
| **Identidade** | **Nome:** Márcia <br> **Idade:** 55 anos <br> **Sexo:** Feminino <br> **Localização:** Brasília, DF <br> **Status Socioeconômico:** Classe Média Alta <br> **Status na Pesquisa:** Persona Primária |
| **Perfil Geral** | Servidora pública e mãe. É a principal organizadora da rotina médica da casa. Acessa a plataforma do Sabin para agendar exames para si, para o marido e para os pais idosos, conferir coberturas de plano de saúde e baixar resultados para as consultas. |
| **Educação e Aprendizado** | **Formação:** Ensino Superior Completo <br> **Nível de Leitura / Digital:** Alto / Médio <br> **Preferência de Aprendizado:** Visual e prático. <br> **Observação:** Prefere ser guiada pelo sistema passo a passo, sem precisar deduzir o funcionamento da interface. |
| **Experiência Profissional** | **Cargo:** Servidora Pública (20+ anos de carreira). <br> **Responsabilidades:** Rotinas burocráticas e gestão administrativa. <br> **Plano de Carreira:** Manter a estabilidade até a aposentadoria e focar no bem-estar familiar. |
| **Relação com Tecnologia** | **Nível:** Intermediário (sabe usar o essencial muito bem). <br> **Dispositivos:** Smartphone (uso contínuo) e Notebook (uso focado). <br> **Sistemas:** WhatsApp, aplicativos bancários, redes sociais e portais de serviços públicos. <br> **Conexão:** Wi-Fi residencial e 4G/5G. |
| **Experiência com Sistemas** | **Uso Atual:** Acessa o Sabin periodicamente, em épocas de check-up da família. <br> **Pontos Positivos:** Confiança na marca e centralização do histórico. <br> **Frustrações:** Ter que fazer múltiplos logins para acessar laudos de dependentes diferentes e falta de clareza imediata sobre o tempo de jejum. <br> **Preferência:** Uma área "Família" unificada e agendamento prático via envio de foto da guia médica. |
| **Objetivos** | **Finais:** Marcar exames ou coletas domiciliares de forma ágil e sem erros no preparo. <br> **De Experiência:** Sentir-se no controle, resolvendo a saúde da família rapidamente pelo celular. <br> **De Vida:** Garantir a saúde preventiva de todos os seus entes queridos sem sacrificar seu pouco tempo livre. |
| **Habilidades e Tarefas** | **Competências:** Excelente capacidade de organização de agendas complexas. <br> **Tarefas Críticas:** Pré-agendamento de exames, verificação de preparo (jejum) e download de laudos em PDF. <br> **Tarefas Secundárias:** Pesquisar unidades do Sabin próximas e consultar vacinas disponíveis. |
| **Relacionamentos** | **Interações:** Familiares (marido, filhos, pais), médicos e atendentes. <br> **Influência:** É a principal tomadora de decisão (Stakeholder direto). Ela escolhe o laboratório com base na praticidade do agendamento e repassa as instruções para o restante da família. |
| **Requisitos e Expectativas** | **Necessidades:** Clareza nas informações de plano de saúde, instruções exatas de preparo em destaque e fácil transição entre perfis de dependentes. <br> **Modelo Mental:** O sistema deve seguir o fluxo: *"Envio a guia > Confirmo a unidade e horário > Recebo o preparo exato e o lembrete no WhatsApp"*. |
| **Atitudes e Tolerância** | **Perfil:** Prática, focada em conveniência e resolução de problemas. <br> **Tolerância a falhas:** Baixa (Não tem tempo a perder com travamentos). <br> **Comportamento no Erro:** Abandona o site imediatamente e procura o ícone do WhatsApp para resolver o agendamento com um atendente humano. |
| **Domínio e Vocabulário** | **Domínio do Tema:** Intermediário (entende a rotina de check-ups, mas não é da área da saúde). <br> **Idiomas:** Português nativo. <br> **Jargões:** Entende termos comuns, mas trava em siglas médicas complexas se não houver uma explicação breve. |
| **Citação Representativa** | *"Eu preciso marcar os exames de sangue da família toda para sábado de manhã. Se o aplicativo me deixar enviar a foto do pedido médico e me disser o jejum de cada um, já resolve a minha vida."* |




## Persona 3: 

> ### Ayla (Estudante de direito e estágiaria)

| Categoria | Detalhes do Perfil |
| :--- | :--- |
|**Foto**| ![alt text](../assets/image-62.png){width="600"}|
| **Identidade** | **Nome:** Ayla <br> **Idade:** 28 anos <br> **Sexo:** Feminino <br> **Localização:** Brasília, DF <br> **Status Socioeconômico:** Classe Média <br> **Status na Pesquisa:** Persona Primária |
| **Perfil Geral** | Estudante de direito com um estágio na área, utiliza a plataforma do Sabin para agendar exames para si mesma e baixar os resultados, utilizando somente conforme a própria nescessidade. |
| **Educação e Aprendizado** | **Formação:** Ensino médio completo e cursando direito <br> **Nível de Leitura / Digital:** Alto <br> **Preferência de Aprendizado:** Visual e intuitivo. <br> **Observação:** Prefere sistemas intuitivos e faceis de navegar, com exploração de interface simplificada. |
| **Experiência Profissional** | **Cargo:** Estudante(penultimo semestre de direito) e estagiária. <br> **Responsabilidades:** Rotinas de estudo e estágio . <br> **Plano de Carreira:** Finalizar sua graduação e conseguir um emprego na área. |
| **Relação com Tecnologia** | **Nível:** Médio a alto (usa com frequência tanto no cotidiano quanto para estudo). <br> **Dispositivos:** Smartphone e notebook. <br> **Sistemas:** Whatsapp, redes sociais, plataformas de estudo, aplicativos bancários. <br> **Conexão:** Wi-Fi residencial e 4G/5G. |
| **Experiência com Sistemas** | **Uso Atual:** Acessa o portal do Sabin para marcar exames para si quando necessário. <br> **Pontos Positivos:** Variedade de exames e resultados no proprio site. <br> **Frustrações:** Tempo de resposta do site, Jornada exaustiva para marcar os exames (muitos cliques). <br> **Preferência:** Agendamento mais prático e mais clareza sobre a disponibilidade de exames. |
| **Objetivos** | **Finais:** Agendar exames e acessar fácilmente os resultados. <br> **De Experiência:** Sentir-se no controle sobre os horarios de seus exames e evitar frustrações por remarcações ou perda de horários . <br> **De Vida:** Garantir sua saúde preventiva evitando perdas de tempo extensas ou estresse desnecessário |
| **Habilidades e Tarefas** | **Competências:** Organização de horários e aprendizado de sistemas simples. <br> **Tarefas Críticas:** Agendamento de exames, baixar laudos, preparos para o exame, buscar unidades. <br> **Tarefas Secundárias:** Consultar convênios |
| **Relacionamentos** | **Interações:** Médicos e atendentes. <br> **Influência:** É a principal organizadora dos prórpios exames (stakeholder direto). Escolhe unidades e agendamento com base em sua própria disponibilidade. |
| **Requisitos e Expectativas** | **Necessidades:** Clareza no preparo para os exames e facilidade no acesso e download de resultados. <br> **Modelo Mental:** O sistema deve seguir o fluxo: *Escolha do exame > Marcação e confirmação da unidade > Lembrete do exame por email ou Whatsapp. |
| **Atitudes e Tolerância** | **Perfil:** Prefere simplicidade e praticidade, mas aceita novas soluções se forem intuitivas. <br> **Tolerância a falhas:** Mediana (A pesar de ter algum tempo, prefere não gastar muito dele com informações incompletas ou travamentos). <br> **Comportamento no Erro:** Frustração, se demorar muito com algum agendamento ou preparação específico, prefere recorrer ao atendimento humano. |
| **Domínio e Vocabulário** | **Domínio do Tema:** Mediano (Sabe o básico sobre saúde preventiva e exames). <br> **Idiomas:** Português nativo. <br> **Jargões:** Termos básicos de saúde. |
| **Citação Representativa** | *"Preciso marcar meu hemograma pra esse fim de semana, espero que o site tenha as informações sobre o jejum."* |

## Persona 4:

> ### Mariana Alves Souza (Paciente Particular / Analista)

| Categoria | Detalhes do Perfil |
| :--- | :--- |
|**Foto**| ![alt text](../assets/image-marina-nova.webp){width="600"}|
| **Identidade** | **Nome:** Mariana Alves Souza <br> **Idade:** 34 anos <br> **Sexo:** Feminino <br> **Localização:** Brasília, DF <br> **Status Socioeconômico:** Classe Média <br> **Status na Pesquisa:** Persona Primária |
| **Perfil Geral** | Profissional ativa que valoriza praticidade no dia a dia. Trabalha em horário comercial e possui uma rotina corrida, conciliando trabalho, cuidados com a saúde e compromissos pessoais. Utiliza frequentemente serviços digitais para otimizar seu tempo. |
| **Educação e Aprendizado** | **Formação:** Ensino Superior Completo em Administração <br> **Nível de Leitura / Digital:** Alto / Alto <br> **Preferência de Aprendizado:** Aprende explorando as interfaces por conta própria. <br> **Observação:** Não gosta de ler instruções longas; prefere conteúdos objetivos e interfaces intuitivas. |
| **Experiência Profissional** | **Cargo:** Analista Administrativa (6 anos na função; experiência anterior como assistente). <br> **Responsabilidades:** Organização de processos internos, uso de sistemas corporativos e controle de documentos. <br> **Plano de Carreira:** Crescimento para cargos de coordenação. |
| **Relação com Tecnologia** | **Nível:** Médio a Alto. <br> **Dispositivos:** Smartphone (dispositivo principal) e Notebook (trabalho e uso pessoal). <br> **Sistemas:** Uso diário de aplicativos bancários, e-commerce e sistemas corporativos. <br> **Preferência:** Exige interfaces rápidas e diretas. |
| **Experiência com Sistemas** | **Uso Atual:** Acessa sites de laboratórios e convênios periodicamente para agendamento de exames e consulta de resultados. <br> **Pontos Positivos:** Consegue resolver problemas simples sozinha. <br> **Frustrações:** Dificuldade para encontrar informações, interfaces confusas e lentidão no processo de agendamento. |
| **Objetivos** | **Finais:** Agendar exames de forma rápida, acessar resultados sem complicação e encontrar unidades próximas. <br> **De Experiência:** Sentir que está no controle da situação, não perder tempo e não cometer erros durante o uso. <br> **De Vida:** Manter a saúde em dia e ter uma rotina organizada e eficiente. |
| **Habilidades e Tarefas** | **Competências:** Boa familiaridade com sistemas digitais e alta autonomia de resolução básica. <br> **Tarefas Críticas:** Agendar exames online (baixa frequência, mas alta importância) e consultar resultados (média frequência). <br> **Tarefas Secundárias:** Buscar instruções de preparo (eventual). |
| **Relacionamentos** | **Interações:** Atendentes de laboratório (apenas quando estritamente necessário) e profissionais de saúde. <br> **Influência:** Pode atuar como facilitadora, auxiliando familiares menos experientes com tecnologia a realizarem seus agendamentos. |
| **Requisitos e Expectativas** | **Necessidades:** Interface simples e direta, processo de agendamento ágil e informações claras sobre o preparo de exames. <br> **Modelo Mental:** Acredita fortemente que tarefas simples devem ser concluídas em poucos passos, exigindo organização e intuição do sistema. |
| **Atitudes e Tolerância** | **Perfil:** Aberta a novas tecnologias (desde que sejam fáceis de usar), valoriza eficiência e evita sistemas complicados. <br> **Tolerância a falhas:** Baixa. <br> **Comportamento no Erro:** O impacto percebido do erro é muito alto (medo de perder o horário do exame ou fazer o preparo incorreto). Por isso, espera sempre uma confirmação clara das ações realizadas na tela. |
| **Domínio e Vocabulário** | **Domínio do Tema:** Básico a intermediário (conhece sua saúde, mas não os jargões). <br> **Idiomas:** Português fluente. <br> **Jargões:** Compreende termos básicos de saúde, mas não possui familiaridade com linguagem técnica avançada. |
| **Citação Representativa** | *"Quero resolver tudo rápido, sem precisar ficar procurando informação."* |


## Histórico de Versão
| Versão | Data | Descrição | Autor | Revisor |
| :--- | :--- | :--- | :--- | :--- |
| 1.0 | 1/05/2026 | Criação do documento e adição da persona "Roberto" |[Philipe Amancio](https://github.com/Phill-Chill)| Maria Laura |
| 1.1 | 1/05/2026 | Adição da persona "Marcia" e "Mariana" |[Maria Laura Regis](https://github.com/Maria-Laura-Regis)|  |
| 1.2 | 2/05/2026 | Adição da persona "Ayla |[Nathan Pontes Romão](https://github.com/nathanpromao)|  |