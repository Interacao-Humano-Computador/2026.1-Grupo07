# Análise de IHC: Beto Carrero World

## Introdução
A seguinte avaliação por inspeção, tem como objetivo identificar problemas na interação e interface no site do <u>**Beto Carrero World**</u>, além de ser adequado para ser objeto de estudo para o presente projeto de planejamento e execução da análise da Interação Humano-Computador.

<br>

## Planejamento
Vamos utilizar a avaliação de heurísticas para identificação de possíveis violações heurísticas, dividida em cinco atividades: Planejamento, Coleta de dados, Interpretação, Consolidação e Relato dos resultados — conforme descrito na **Figura I**. Este método foi escolhido devido à demanda de análises de uma lista de sites, dado seu baixo custo e velocidade de execução (BARBOSA et al., 2021. p. ).

<center>Figura - I Descrição das atividades da avaliação heurística </center>

![alt text](/assets/image-13.png)
<p style="font-size: 10pt;">Fonte: BARBOSA et al.(2021, p.)</p>


<br>

### Perfil de Usuário

 Com base em abas de Grupos e Grupo Escola do site, e em avaliações no Google separamos os perfis de usuário em:

<br>

#### Perfis de Usuário

| Característica | Perfil 01: Amigos | Perfil 02: Família |
| :--- | :--- | :--- |
| **Faixa Etária** | 18 a 30 anos | 28 a 65 anos |
| **Tecnologia** | Alto (Nativos Digitais) | Médio (Funcionais) |
| **Aparelhos** | Smartphone | Desktop / Smartphone |
| **Frequência** | Baixa (Pontual) | Média (Planejamento) |
| **Motivação** | Diversão e Tempo | Segurança e Conforto |


 Com base nesses dados, definimos as funcionalidades que apresentam problemas ao usuário durante a realização de suas atividades e que serão analisadas:
 
 - Aquisição de passagem de avião;
 - Aquisição de ingressos e alimentação;
 - Aquisção de hospedagem;
 - Navegação pelo site.



## Coleta de dados e Interpretação

<fieldset markdown = "1">
<legend><b>Relatório de Avaliação Heurística</b></legend>

**Heurística(s) violada(s):** <u>Consistência e padronização | Projeto estético e minimalista</u>

**ID do Problema:** <u>#1</u>

| Item | Descrição / Opções |
| :--- | :--- |
| **Verificação** | Todos os itens de navegação possuem comportamento bem definido? |
| **Grau de Severidade** | [ ] 0 - Sem importância <br> [ ] 1 - Cosmético <br> [x] 2 - Simples <br> [ ] 3 - Grave <br> [ ] 4 - Catastrófico |
| **Natureza do problema** | [ ] Barreira &nbsp;&nbsp;&nbsp; [ ] Obstáculo &nbsp;&nbsp;&nbsp; [x] Ruído |
| **Perspectiva do usuário** | [x] Problema Geral &nbsp;&nbsp;&nbsp; [ ] Problema Preliminar &nbsp;&nbsp;&nbsp; [ ] Problema Especial |
| **Perspectiva da tarefa** | [x] Problema Principal &nbsp;&nbsp;&nbsp; [ ] Problema Secundário |
| **Perspectiva do Projeto** | [ ] Problema Falso &nbsp;&nbsp;&nbsp; [ ] Problema Novo &nbsp;&nbsp;&nbsp; [ ] Não se aplica |

---

#### Detalhamento do Problema

* **Contexto:** Ao entrar no site o usuário for explorar para obter informações sobre o parque irá perceber que alguns itens da barra de navegação não são clicáveis, mas só  sendo ativado por *Hover*. E outros são redirecionáveis.
* **Causa:** Não há distinção entre os itens (além da escrita), inclusive em relação ao *Hover* os itens: Passaporte, Opcionais, Alimentação, Viagem e Combos mostram as mesmas opções.
* **Efeito sobre o usuário:** Frustração.
* **Efeito sobre a tarefa:** Redirecionamento acidental.
* **Correção possível:** Diferneciar em grupo os itens que redireciona dos que só mostrem outras opções de navegação. E retirar ou separar os que realizam a mesma funcionalidade.



</fieldset>
<!-- </div> -->
<p style="font-size: 10pt;">Fonte: MACIEL et al. ([2004?], p. página).</p>

___

#### Aquisição de passagem de avião
<fieldset markdown = "1">
<legend><b>Relatório de Avaliação Heurística</b></legend>

**Heurística(s) violada(s):** <u>Controle e liberdade do usuário</u>

**ID do Problema:** <u>#2</u>

| Item | Descrição / Opções |
| :--- | :--- |
| **Verificação** | Em todo o processo de compra das passagens aérias é possível retroceder em cada etapa em caso de erro? |
| **Grau de Severidade** | [ ] 0 - Sem importância <br> [ ] 1 - Cosmético <br> [x] 2 - Simples <br> [ ] 3 - Grave <br> [ ] 4 - Catastrófico |
| **Natureza do problema** | [x] Barreira &nbsp;&nbsp;&nbsp; [ ] Obstáculo &nbsp;&nbsp;&nbsp; [ ] Ruído |
| **Perspectiva do usuário** | [x] Problema Geral &nbsp;&nbsp;&nbsp; [ ] Problema Preliminar &nbsp;&nbsp;&nbsp; [ ] Problema Especial |
| **Perspectiva da tarefa** | [x] Problema Principal &nbsp;&nbsp;&nbsp; [ ] Problema Secundário |
| **Perspectiva do Projeto** | [ ] Problema Falso &nbsp;&nbsp;&nbsp; [ ] Problema Novo &nbsp;&nbsp;&nbsp; [ ] Não se aplica |

---

#### Detalhamento do Problema

* **Contexto:** Ao consultar datas, preço e companhias disponíveis o usuário pode selecionar uma das opções dessa pesquisa, o que abrirá um pop-up perguntado se o usuário gostaria de já adicionar os ingressos nesse compra e nesse janela não há uma "saída de emergência" só pode continuar a compra com ou sem os ingressos.
* **Causa:** Janela modal que limita a escolha do usuário.
* **Efeito sobre o usuário:** Frustração e sobrecarga.
* **Efeito sobre a tarefa:** Terá que ser refieta a pesquisa.
* **Correção possível:** Adicionar um mecanismo de retorno ou implementar junto a próxima etápa de compra.

</fieldset>
<p style="font-size: 10pt;">Fonte: MACIEL et al. ([2004?], p. página).</p>

___

### Aquisição de ingressos e alimentação


<fieldset markdown = "1">
<legend><b>Relatório de Avaliação Heurística</b></legend>

**Heurística(s) violada(s):** <u>Correspondência entre o sistema e o mundo real | Visibilidade do estado do sistema</u>

**ID do Problema:** <u>#3</u>

| Item | Descrição / Opções |
| :--- | :--- |
| **Verificação** | Os tipos de produtos e serviços estão disposto de mainera que o usuário entenda o que cada categoria representa? Além de mostra a quantidade  que foi adicionada em cada actegoria ao carrinho?|
| **Grau de Severidade** | [ ] 0 - Sem importância <br> [ ] 1 - Cosmético <br> [x] 2 - Simples <br> [ ] 3 - Grave <br> [ ] 4 - Catastrófico |
| **Natureza do problema** | [ ] Barreira &nbsp;&nbsp;&nbsp; [ ] Obstáculo &nbsp;&nbsp;&nbsp; [x] Ruído |
| **Perspectiva do usuário** | [ ] Problema Geral &nbsp;&nbsp;&nbsp; [x] Problema Preliminar &nbsp;&nbsp;&nbsp; [ ] Problema Especial |
| **Perspectiva da tarefa** | [x] Problema Principal &nbsp;&nbsp;&nbsp; [ ] Problema Secundário |
| **Perspectiva do Projeto** | [ ] Problema Falso &nbsp;&nbsp;&nbsp; [ ] Problema Novo &nbsp;&nbsp;&nbsp; [ ] Não se aplica |

---

#### Detalhamento do Problema

* **Contexto:** O título azul "Passaportes" permanece estático no topo, não deixando claro se o que vemos abaixo é o conteúdo da aba selecionada ou se todo o bloco é uma coisa só. O sistema falha em dar o feedback visual de "onde eu estou" e "o que este botão faz em relação aos outros".
* **Causa:** Falha na arquitetura de informação e na hierarquia visual, onde o rótulo principal "PASSAPORTES" engloba categorias semanticamente distintas (Alimentação, Opcionais) e um botão de ação (Finalizar Compra) com o mesmo peso visual.
* **Efeito sobre o usuário:** Consequência (sobrecarga, desorientação, etc).
* **Efeito sobre a tarefa:** Aumento do tempo de execução e risco de erro.
* **Correção possível:** Substituir o título estático "PASSAPORTES" por um indicador dinâmico que mostre em qual categoria o usuário está (ex: "Você está em: Alimentação").

</fieldset>
<p style="font-size: 10pt;">Fonte: MACIEL et al. ([2004?], p. página).</p>



## Consolidação e Relato dos resultados

A avaliação heurística do site do **Beto Carrero World** identificou problemas de usabilidade relacionados à navegação, organização das informações e fluxo de compra. Embora o portal reúna diversos serviços importantes, algumas inconsistências dificultam a interação do usuário.

Na **navegação**, observou-se falta de padronização no menu principal, pois alguns itens redirecionam páginas e outros apenas exibem opções adicionais. Isso pode gerar confusão e cliques acidentais.

No processo de **compra de passagens aéreas**, foram encontrados problemas de controle do usuário, já que determinadas janelas interrompem o fluxo e oferecem poucas opções de retorno ou cancelamento.

Na área de **ingressos e alimentação**, a principal falha está na hierarquia visual e na clareza das categorias. Alguns elementos aparecem agrupados de forma pouco intuitiva, dificultando o entendimento sobre a seção atual e aumentando o tempo de navegação.

Os problemas identificados possuem severidade predominantemente simples, porém afetam tarefas centrais do site, como compra e planejamento da visita.

Como melhorias, recomenda-se padronizar menus, reorganizar categorias, oferecer feedback visual mais claro e tornar os fluxos de compra mais flexíveis.

Conclui-se que o site cumpre seu papel comercial, mas ajustes de usabilidade podem melhorar significativamente a experiência do usuário e facilitar a conversão de vendas.


## Histórioco de versões

| Data | Versão | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores | 
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|18/04/2026| 1.0 | Realização da análise | Philipe | 19/04/2026 | Revisão de conteúdo e estrutura | Hugo |
|19/04/2026| 1.1 | Consolidação e relato dos resultados + adicionar o histórico de versões | Hugo | - | - | - |

## Referências

 BARBOSA, S. D. J. et al. **Interação Humano-Computador e Experiência do Usuário**. 1. ed. Rio de Janeiro: Autopublicação, 2021.


 MACIEL, C. et al. **Avaliação heurística de sítios na web**. Niterói: Instituto de Computação - Universidade Federal Fluminense (UFF), [2004?]. 