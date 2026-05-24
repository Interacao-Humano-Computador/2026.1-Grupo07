# Princípios e Diretrizes Gerais do Projeto

## Tabela de contribuição
|Artefato(s) | Autor(es)|
| --- | --- |
| Página de Princípios e Diretrizes Gerais do Projeto | Maria Laura |


##  Introdução

Os princípios e diretrizes de projeto são fundamentais para guiar o design de Interação Humano-Computador. Como introduzido na literatura, princípios costumam representar objetivos gerais e de alto nível que auxiliam o design, embora não substituam a análise cuidadosa do problema e dos usuários <span class="hover-image">(BARBOSA et al., 2021, p. 237)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-1.jpeg" alt="Trecho da página 237"> </span>. 

Segundo Norman (1988), o modelo conceitual projetado deve facilitar a determinação das ações possíveis, tornar visíveis os resultados e avaliar o estado corrente do sistema de forma natural <span class="hover-image">(BARBOSA et al., 2021, p. 238)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-2.jpeg" alt="Trecho da página 238"> </span>.


Os princípios gerais de projeto são fundamentais para guiar o design de Interação Humano-Computador, auxiliando o usuário a compreender o sistema rapidamente. Segundo Norman (1988), o modelo conceitual projetado deve facilitar a determinação das ações possíveis, tornar visíveis os resultados e avaliar o estado corrente do sistema de forma natural <span class="hover-image">(BARBOSA et al., 2021, p. 238)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-2.jpeg" alt="Trecho da página 238"> </span>.


---

## Tópicos dos Princípios Gerais do Projeto

Com base na literatura, o projeto adota os seguintes princípios para fundamentar as decisões de design da interface:
<a id='correspondencia-expect'></a>
### 1. Correspondência com as expectativas dos usuários
Devemos explorar mapeamentos naturais e certificar-nos de que o usuário consegue determinar a relação entre suas intenções e as ações possíveis. A interface deve projetar a comunicação utilizando o idioma do usuário, com palavras e conceitos que lhe são familiares <span class="hover-image">(BARBOSA et al., 2021, 2010, p. 238-239)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-2.jpeg" alt="Texto da página 238"> </span>.

**Aplicação no portal do Sabin:**
O portal apresenta resultados parcialmente satisfatórios neste princípio. Os rótulos das seções principais — "Resultado de Exames", "Agendamentos", "Nossas Unidades" — utilizam linguagem  médico-laboratorial, o que dificultao entendimento do usuário e as ações disponíveis.

### 2. Simplicidade nas estruturas das tarefas
É necessário simplificar a estrutura das tarefas, reduzindo a quantidade de planejamento e resolução de problemas que elas requerem, utilizando a tecnologia para apoiar a aprendizagem e manter o usuário no controle <span class="hover-image">(BARBOSA et al., 2021, 2010, p. 239)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-3.jpeg" alt="Texto da página 239"> </span>.

**Aplicação no portal do Sabin:**
A tarefa de acessar resultados de exames apresenta complexidade desnecessária. O fluxo exige que o usuário: (1) localize a opção correta no menu; (2) seja redirecionado para um subdomínio diferente (laudos.sabin.com.br); e (3) insira credenciais que só recebe presencialmente. Esse redirecionamento para um domínio distinto quebra a continuidade da navegação e pode causar desconfiança no usuário. 
### 3. Equilíbrio entre controle e liberdade do usuário
O ambiente de trabalho "pertence" ao usuário. Devemos reduzir o número de opções e decisões a cada instante para evitar angústia, mas garantir "saídas de emergência" claras (como botões de cancelar ou voltar) para que o usuário navegue sem medo de cometer erros irreversíveis <span class="hover-image">(BARBOSA et al., 2021, 2010, p. 240-241)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-4.jpeg" alt="Texto da página 240"> </span>.

**Aplicação no portal do Sabin:**
O portal apresenta uma sobrecarga de opções na página inicial: serviços na loja virtual, banners promocionais, múltiplas categorias de exames, agendamentos, convênios, blog e outras funcionalidades são exibidos simultaneamente. Esse excesso de informação pode causar paralisia de decisão, especialmente em usuários que chegam ao site em contexto de urgência ou ansiedade — perfil comum entre os visitantes do portal. Por outro lado, o menu de navegação principal é fixo e acessível em todas as páginas, o que garante ao usuário sempre uma "saída" clara para as seções principais. 
<a id='conssistencia-pad'></a>
### 4. Consistência e padronização; promoção da eficiência do usuário
Ações relacionadas em situações semelhantes devem funcionar da mesma forma para facilitar o aprendizado. Além disso, o sistema deve focar na economia de tempo do usuário, mantendo-o produtivamente ocupado, fornecendo atalhos e aceleradores para usuários experientes <span class="hover-image">(BARBOSA et al., 2021, 2010, p. 242-243)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-6.jpeg" alt="Texto da página 242"> </span>.

**Aplicação no portal do Sabin:**
Uma inconsistência relevante é o redirecionamento do usuário ao subdomínio `laudos.sabin.com.br` ao acessar resultados de exames. Esse portal de laudos apresenta identidade visual e estrutura diferentes da página principal, desorientando o usuário e podendo gerar a percepção de que ele saiu do ambiente do Sabin. 

### 5. Antecipação das necessidades do usuário
O software deve prever o que o usuário quer e precisa, fornecendo as ferramentas necessárias para cada passo do processo antes mesmo que o usuário precise buscá-las, assumindo uma postura proativa na interação <span class="hover-image">(BARBOSA et al., 2021, p. 243-244)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-8.jpeg" alt="Texto da página 244"> </span>.

**Aplicação no portal do Sabin:**
O Sabin demonstra esforços neste princípio com funcionalidades como a página de "Preparo de Exames", que antecipa a necessidade do paciente de saber como se preparar antes da coleta. No entanto, ao acessar o portal, o usuário que aguarda um resultado não encontra um caminho imediato e destacado para essa tarefa — que é a ação mais provável e urgente para grande parte dos visitantes.

### 6. Visibilidade e reconhecimento
O designer deve tornar as coisas visíveis, encurtando os golfos de execução e avaliação. O sistema não deve exigir que o usuário memorize informações de uma tela para a outra; as opções devem estar prontamente disponíveis para reconhecimento visual <span class="hover-image">(BARBOSA et al., 2021, p. 244-245)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-9.jpeg" alt="Texto da página 245"> </span>.

**Aplicação no portal do Sabin:**
O portal apresenta uma violação clara deste princípio no fluxo de acesso a resultados: o usuário precisa memorizar — ou ter em mãos — o número do protocolo de atendimento, fornecido somente de forma física no momento da coleta. 

<a id='conteudo-relevante'></a>
### 7. Conteúdo relevante e expressão adequada
A interface deve seguir a máxima da quantidade ("menos é mais"), onde os diálogos não devem conter informações irrelevantes ou raramente necessárias. Mensagens devem ser concisas e a apresentação gráfica deve garantir legibilidade <span class="hover-image">(BARBOSA et al., 2021, p. 246-247)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-10.jpeg" alt="Texto da página 246"> </span>.

**Aplicação no portal do Sabin:**
A página inicial do Sabin concentra grande volume de conteúdo promocional — banners de vacinas, loja virtual, campanhas de saúde — que compete visualmente com as tarefas primárias do usuário. Para um paciente que acessa o site exclusivamente para consultar um resultado ou agendar um exame, esse excesso de conteúdo constitui ruído visual que aumenta o tempo de tarefa e a carga cognitiva, contrariando a máxima da quantidade descrita por Barbosa e Silva (2010).

### 8. Projeto para erros
O designer deve assumir que qualquer erro potencial será cometido e, em primeiro lugar, tentar evitar que eles ocorram. Caso ocorram, o sistema deve ajudar o usuário a se recuperar facilmente, tornando ações perigosas reversíveis e oferecendo mensagens de erro expressas em linguagem simples e construtiva, sem códigos indecifráveis <span class="hover-image">(BARBOSA et al., 2021, 2010, p. 247)<sup class="Print">[PRINT]</sup><img class= "img" src="../../assets/cap10-11.jpeg" alt="Texto da página 247"> </span>.

**Aplicação no portal do Sabin:**
O portal apresenta lacunas neste princípio. O fluxo de recuperação de protocolo perdido — situação de erro bastante comum — não é suficientemente visível ou guiado. A orientação disponível direciona o usuário ao WhatsApp ou ao balcão físico, o que representa uma quebra do fluxo digital e aumenta o esforço necessário para se recuperar do erro.

___

## Referência Bibliográfica
> BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação Humano-Computador*. 1. ed. Rio de Janeiro: Elsevier, 2010.

---
## Histórico de Versão

| Versão | Data | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores |
| :---: | :---: | :--- | :--- | :---: | :--- | :--- |
| 1.0 | 09/05/2026 | Criação do documento | [Maria Laura Regis](https://github.com/Maria-Laura-Regis) | 09/05/2026 | Revisão da estrutura inicial e do conteúdo base dos princípios e diretrizes gerais | [Philipe Amancio](https://github.com/Phill-Chill) |
| 1.1 | 11/05/2026 | Remocção da seção de características da plataforma (informação duplicada) | [Hugo Freitas Silva](https://github.com/HugoFreitass) | 11/05/2026 | Checagem da remoção de conteúdo duplicado e da manutenção da coerência do documento | [Philipe Amancio](https://github.com/Phill-Chill) |
| 1.2 | 15/05/2026 | Adição da rastreabilidade dos autores dos artefatos | [Philipe Amancio](https://github.com/Phill-Chill) | 15/05/2026 | Validação dos links e créditos de autoria nos princípios e diretrizes gerais | [Maria Laura Regis](https://github.com/Maria-Laura-Regis) |

---

