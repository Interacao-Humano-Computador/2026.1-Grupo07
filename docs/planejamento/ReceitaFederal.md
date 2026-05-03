## Introdução
A seguinte avaliação por inspeção, tem como objetivo identificar problemas na interação e interface no site da <u>**Receita Federal**</u>, além de ser adequado para ser objeto de estudo para o presente projeto de planejamento e execução da análise da Interação Humano-Computador.

<br>

## Planejamento 
Vamos utilizar a avaliação de heurísticas para identificação de possíveis violações heurísticas, dividida em cinco atividades: Planejamento, Coleta de dados, Interpretação, Consolidação e Relato dos resultados — conforme descrito na **Figura I**. Este método foi escolhido devido à demanda de análises de uma lista de sites, dado seu baixo custo e velocidade de execução(BARBOSA et al., 2021. p. ).

<center>Figura - I Descrição das atividades da avaliação heurística </center>

![alt text](/assets/image-13.png)
<p style="font-size: 10pt;">Fonte: BARBOSA et al.(2021, p.)</p>

<br>

### Perfil de Usuário

 Com base no contexto brasileiro de uso do site, com base nos serviços oferecidos, e em avaliações no Google separamos os perfis de usuário em:

<br>
 
#### Perfis de Usuário

| Característica | Perfil 01: Jovens Adultos / Contribuintes Iniciantes | Perfil 02: Profissionais Autônomos / Pequenos Empreendedores |
| :--- | :--- | :--- |
| **Faixa Etária** | 18 a 30 anos. | 25 a 50 anos. |
| **Grau de Instrução Tecnológica** | Alto (nativos digitais, familiarizados com apps, autenticação digital e serviços online). | Médio a Alto (usuários habituados a sistemas de gestão, emissão de documentos e plataformas governamentais). |
| **Aparelhos Utilizados** | Majoritariamente Smartphone (Android/iOS), com uso ocasional de notebook. | Notebook/Desktop como principal, com apoio de Smartphone. |
| **Frequência de Uso do Site** | Baixa a média (acessam em períodos específicos, como declaração de IR, emissão de CPF ou consultas cadastrais). | Média a alta (acessos frequentes para obrigações fiscais e consultas empresariais). |
| **Objetivos Principais** | Consultar CPF, emitir comprovantes, acessar Meu Imposto de Renda, regularizar pendências e obter informações rápidas sobre tributos. | Consultar CNPJ, emitir certidões, acessar e-CAC, acompanhar parcelamentos, regularizar situação fiscal e utilizar serviços para MEI/Simples Nacional. |
| **Motivação** | Resolver obrigações burocráticas com rapidez, evitar filas presenciais e utilizar serviços públicos de forma digital e prática. | Manter negócio regularizado, cumprir exigências legais, economizar tempo com processos digitais e centralizar serviços tributários em um único portal. |

<br>

 Com base nesses dados, definimos as funcionalidades que apresentam problemas ao usuário durante a realização de suas atividades e que serão analisadas:

- Navegação
- Busca
- Disposição do conteúdo
- Formulários e serviços digitais



## Coleta de dados e Interpretação

#### Navegação

<fieldset markdown = "1">

<legend><b>Relatório de Avaliação Heurística</b></legend>

**Heurística(s) violada(s):** <u>Consistência e padronização | Reconhecimento em vez de memorização</u>  
**ID do Problema:** <u>#1</u>

| Item | Descrição / Opções |
| :--- | :--- |
| **Verificação** | Os menus e atalhos principais possuem organização clara e previsível? |
| **Grau de Severidade** | [ ] 0 - Sem importância <br> [ ] 1 - Cosmético <br> [x] 2 - Simples <br> [ ] 3 - Grave <br> [ ] 4 - Catastrófico |
| **Natureza do problema** | [ ] Barreira &nbsp;&nbsp;&nbsp; [ ] Obstáculo &nbsp;&nbsp;&nbsp; [x] Ruído |
| **Perspectiva do usuário** | [x] Problema Geral &nbsp;&nbsp;&nbsp; [ ] Problema Preliminar &nbsp;&nbsp;&nbsp; [ ] Problema Especial |
| **Perspectiva da tarefa** | [x] Problema Principal &nbsp;&nbsp;&nbsp; [ ] Problema Secundário |
| **Perspectiva do Projeto** | [ ] Problema Falso &nbsp;&nbsp;&nbsp; [ ] Problema Novo &nbsp;&nbsp;&nbsp; [x] Não se aplica |

---

#### Detalhamento do Problema

* **Contexto:** Ao acessar a página inicial, o usuário encontra muitos menus, links institucionais e áreas de serviço distribuídas em diferentes regiões da tela.
* **Causa:** Falta de hierarquia visual clara entre conteúdos informativos e serviços realmente importantes.
* **Efeito sobre o usuário:** Dificuldade para localizar rapidamente o serviço desejado.
* **Efeito sobre a tarefa:** Aumento do tempo de navegação e tentativas desnecessárias.
* **Correção possível:** Destacar serviços principais com categorias claras e reduzir elementos secundários da página inicial.

</fieldset>
<p style="font-size: 10pt;">Fonte: MACIEL et al. ([2004?], p. página).</p>

___

#### Busca

<fieldset markdown = "1">
<legend><b>Relatório de Avaliação Heurística</b></legend>

**Heurística(s) violada(s):** <u>Flexibilidade e eficiência de uso | Correspondência entre sistema e mundo real</u>  
**ID do Problema:** <u>#2</u>

| Item | Descrição / Opções |
| :--- | :--- |
| **Verificação** | O mecanismo de busca utiliza linguagem compreensível ao público geral? |
| **Grau de Severidade** | [ ] 0 - Sem importância <br> [ ] 1 - Cosmético <br> [ ] 2 - Simples <br> [x] 3 - Grave <br> [ ] 4 - Catastrófico |
| **Natureza do problema** | [ ] Barreira &nbsp;&nbsp;&nbsp; [x] Obstáculo &nbsp;&nbsp;&nbsp; [ ] Ruído |
| **Perspectiva do usuário** | [x] Problema Geral &nbsp;&nbsp;&nbsp; [ ] Problema Preliminar &nbsp;&nbsp;&nbsp; [ ] Problema Especial |
| **Perspectiva da tarefa** | [x] Problema Principal &nbsp;&nbsp;&nbsp; [ ] Problema Secundário |
| **Perspectiva do Projeto** | [ ] Problema Falso &nbsp;&nbsp;&nbsp; [ ] Problema Novo &nbsp;&nbsp;&nbsp; [x] Não se aplica |

---

#### Detalhamento do Problema

* **Contexto:** Usuários procuram serviços como CPF, imposto de renda ou MEI utilizando termos populares.
* **Causa:** Parte dos resultados utiliza nomenclaturas técnicas, siglas ou termos burocráticos.
* **Efeito sobre o usuário:** Confusão sobre qual resultado selecionar.
* **Efeito sobre a tarefa:** Erros de navegação ou abandono da busca.
* **Correção possível:** Implementar sinônimos, linguagem simples e sugestões automáticas baseadas em termos populares.

</fieldset>
<p style="font-size: 10pt;">Fonte: MACIEL et al. ([2004?], p. página).</p>

___

#### Disposição do Conteúdo

<fieldset markdown = "1">
<legend><b>Relatório de Avaliação Heurística</b></legend>

**Heurística(s) violada(s):** <u>Projeto estético e minimalista | Reconhecimento em vez de memorização</u>  
**ID do Problema:** <u>#3</u>

| Item | Descrição / Opções |
| :--- | :--- |
| **Verificação** | As páginas apresentam somente informações relevantes para a tarefa do usuário? |
| **Grau de Severidade** | [ ] 0 - Sem importância <br> [ ] 1 - Cosmético <br> [x] 2 - Simples <br> [ ] 3 - Grave <br> [ ] 4 - Catastrófico |
| **Natureza do problema** | [ ] Barreira &nbsp;&nbsp;&nbsp; [ ] Obstáculo &nbsp;&nbsp;&nbsp; [x] Ruído |
| **Perspectiva do usuário** | [x] Problema Geral &nbsp;&nbsp;&nbsp; [ ] Problema Preliminar &nbsp;&nbsp;&nbsp; [ ] Problema Especial |
| **Perspectiva da tarefa** | [ ] Problema Principal &nbsp;&nbsp;&nbsp; [x] Problema Secundário |
| **Perspectiva do Projeto** | [ ] Problema Falso &nbsp;&nbsp;&nbsp; [ ] Problema Novo &nbsp;&nbsp;&nbsp; [x] Não se aplica |

---

#### Detalhamento do Problema

* **Contexto:** Em páginas internas há excesso de textos institucionais, notícias e blocos informativos misturados com serviços.
* **Causa:** Ausência de separação clara entre conteúdo informativo e conteúdo operacional.
* **Efeito sobre o usuário:** Sobrecarga cognitiva e dificuldade de foco.
* **Efeito sobre a tarefa:** Mais tempo para identificar o próximo passo.
* **Correção possível:** Priorizar ações principais no topo e mover conteúdos complementares para áreas secundárias.

</fieldset>
<p style="font-size: 10pt;">Fonte: MACIEL et al. ([2004?], p. página).</p>

___

#### Formulários e Serviços Digitais

<fieldset markdown = "1">
<legend><b>Relatório de Avaliação Heurística</b></legend>

**Heurística(s) violada(s):** <u>Prevenção de erros | Ajudar usuários a reconhecer, diagnosticar e recuperar erros</u>  
**ID do Problema:** <u>#4</u>

| Item | Descrição / Opções |
| :--- | :--- |
| **Verificação** | Os formulários explicam claramente erros de preenchimento e como corrigi-los? |
| **Grau de Severidade** | [ ] 0 - Sem importância <br> [ ] 1 - Cosmético <br> [ ] 2 - Simples <br> [x] 3 - Grave <br> [ ] 4 - Catastrófico |
| **Natureza do problema** | [ ] Barreira &nbsp;&nbsp;&nbsp; [x] Obstáculo &nbsp;&nbsp;&nbsp; [ ] Ruído |
| **Perspectiva do usuário** | [x] Problema Geral &nbsp;&nbsp;&nbsp; [ ] Problema Preliminar &nbsp;&nbsp;&nbsp; [ ] Problema Especial |
| **Perspectiva da tarefa** | [x] Problema Principal &nbsp;&nbsp;&nbsp; [ ] Problema Secundário |
| **Perspectiva do Projeto** | [ ] Problema Falso &nbsp;&nbsp;&nbsp; [ ] Problema Novo &nbsp;&nbsp;&nbsp; [x] Não se aplica |

---

#### Detalhamento do Problema

* **Contexto:** Ao preencher serviços digitais vinculados ao Gov.br ou Receita, o usuário pode cometer erros cadastrais ou de autenticação.
* **Causa:** Mensagens de erro nem sempre são objetivas ou orientadas à solução.
* **Efeito sobre o usuário:** Insegurança e repetição de tentativas.
* **Efeito sobre a tarefa:** Interrupção do processo e possível abandono.
* **Correção possível:** Exibir mensagens claras, indicar campo incorreto e fornecer instruções imediatas de correção.

</fieldset>
<p style="font-size: 10pt;">Fonte: MACIEL et al. ([2004?], p. página).</p>

___



## Consolidação e Relato dos resultados

A avaliação heurística do portal da **Receita Federal** identificou problemas de usabilidade relacionados à navegação, busca, organização do conteúdo e interação com formulários digitais. Embora o sistema ofereça ampla variedade de serviços importantes, sua estrutura dificulta a experiência do usuário, principalmente para acessos rápidos e esporádicos.

Os principais problemas estão na **encontrabilidade da informação**. A página inicial e páginas internas apresentam excesso de links, menus e conteúdos institucionais, o que reduz a clareza da interface e aumenta o esforço para localizar serviços como CPF, comprovantes e consultas fiscais.

Também foram observadas limitações no **mecanismo de busca** e na linguagem utilizada. O uso de siglas, termos técnicos e vocabulário burocrático pode gerar dúvidas, especialmente para usuários com menor familiaridade tributária.

Nos **formulários e processos de autenticação**, foram identificadas falhas relacionadas à prevenção e recuperação de erros. Mensagens pouco claras podem causar frustração, repetição de tentativas e abandono da tarefa.

Quanto à severidade, predominam problemas entre simples e graves. Não foram encontradas falhas catastróficas, porém os obstáculos reduzem a eficiência e a satisfação do usuário.

Como melhorias, recomenda-se reorganizar a arquitetura da informação, simplificar menus, reduzir ruído visual, adotar linguagem mais clara, aprimorar a busca e reformular mensagens de erro.

Conclui-se que o portal cumpre sua função institucional, mas ajustes de usabilidade podem melhorar significativamente a eficiência, acessibilidade e experiência geral dos usuários.

## Histórioco de versões

| Data | Versão | Descrição | Autores | Data Revisão | Descrição Revisão | Revisores | 
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|19/04/2026| 1.0 | Realização da análise | Hugo | 19/04/2026 | Revisão de conteúdo e estrutura | Philipe |


## Referências

 BARBOSA, S. D. J. et al. **Interação Humano-Computador e Experiência do Usuário**. 1. ed. Rio de Janeiro: Autopublicação, 2021.


 MACIEL, C. et al. **Avaliação heurística de sítios na web**. Niterói: Instituto de Computação - Universidade Federal Fluminense (UFF), [2004?]. 