# Relatório de Avaliação de Sites  


## Lista de Sites Avaliados

- [Detran-PA](https://www.detran.pa.gov.br/index_.php)  
- [TRE-DF](https://www.tre-df.jus.br)  
- [TSE](https://www.tse.jus.br)  
- [Sistec/MEC](https://sistec.mec.gov.br/login/login)  
- [Plataforma Lattes](https://lattes.cnpq.br)  
- [CIEE](https://portal.ciee.org.br)  
- [OLX](https://www.olx.com.br)  
- [Craigslist Brasília](https://brasilia.craigslist.org)  
- [Arngren](https://www.arngren.net)  

---

## Critérios de Seleção e Parâmetros de Análise

Utilizamos à base do ciclo de vida de Mayhew, especificamente na Análise de Requisitos, e as 10 Heurísticas de Nielsen para nos ajudar à identificar, dentre todas opções apresentadas, qual tinha maior necessidade de aplicação do método que interferia diretamente na qualidade do sistema.

### Perfil do usuário
Identificação das necessidades, limitações e expectativas do público heterogêneo que utiliza os serviços do estado.

### Análise das tarefas e Funcionalidades
- Complexidade de execução  

### Características da Plataforma
- Para que serve?  

### Princípio geral  
- Entrega o que é proposto à entregar?  

### Usabilidade

### Acessibilidade

### Guia de Estilo
- Design Minimalista
- Padronização

---

## Site escolhido e por quê?

Escolhemos o portal do DETRAN-PA por ser um sistema de alta relevância social que lida com processos críticos e um público extremamente heterogêneo. A complexidade de sua arquitetura de informação e a coexistência de múltiplos sub-sistemas (ChatBot, Agendamentos, Infrações, Estatísticas, Ouvidoria etc.) oferecem o cenário ideal para aplicar análises detalhadas e propor melhorias que garantam que a tecnologia seja uma facilitadora, e não uma barreira, para o cidadão.

Contudo, o grupo selecionou um site para avaliar a necessidade de ajustes e a implementação de novas funcionalidades, visando uma análise detalhada de melhorias estruturais. O objetivo é aplicar os métodos ministrados em sala, evidenciando sua importância para que o usuário final disponha de um sistema que assegure qualidade, acessibilidade, usabilidade e segurança.

Sabemos que o conhecimento de critérios de qualidade e o rigor nos processos de desenvolvimento não garantem, por si só, um produto isento de falhas; detalhes podem passar despercebidos e comprometer a experiência final. Portanto, sob as perspectivas de quem concebe e de quem utiliza o sistema, a avaliação busca verificar se a interface apoia adequadamente os usuários no alcance de seus objetivos dentro de um contexto de uso real.

---

## Problemas Identificados

### Ouvidoria
A ouvidoria não serve o usuário da devida forma, posto que, ao invés de disponibilizar um campo para identificação e registro da reclamação, a página apresenta informações sobre o conceito de ouvidoria e disponibiliza meios de contato, como email e telefones, o que diminui muito a eficiência do uso e descontenta ainda mais o cliente já insatisfeito. Este problema se encaixa na heurística **“flexibilidade e eficiência de uso”** de Nielsen.

---

### ChatBot
O site apresenta um ChatBot para servir suporte ao usuário, entretanto o uso dele é dificultado por abrir uma segunda aba do navegador ao clicar nele, e solicitar uma identificação de diversos dados para iniciar o atendimento, a qual, em caso de falha por informações inválidas, a aba trava e se faz necessário a abertura de uma nova aba para recomeçar a identificação. Além disso, ele manda várias mensagens inúteis durante a interação no chat, e finaliza o atendimento subitamente após uma interação.

---

### Navegação
Ao navegar no site, não há meio de retornar à interface anterior, posto que o site é uma página estática sem encapsulamento, que abre diferentes interfaces sem mudar de URL, fazendo com que o usuário tenha que decorar os caminhos feitos anteriormente e recomeçar qualquer processo que tenha feito.

---

### Estatísticas
O site apresenta uma sessão de estatísticas, que disponibiliza dados sobre frota, condutores, acidentes e infrações. Entretanto, ao clicar em uma das opções, é aberta uma nova aba com um dashboard desorganizado, pesado e de carregamento lento, com uma interface completamente diferente do site anterior. As abas acidentes e infrações se encontram vazias, com uma mensagem de “Em desenvolvimento”.

---

### Habilitação (duplicidade)
Na barra de opções principal da página, é apresentada uma aba de “habilitação”, que se abre em cascata ao clicar, e apresenta, dentre muitas opções, a opção de “1° via da habilitação”. Ao clicar, a página muda de interface e vai para orientações sobre a primeira via.

Entretanto, ao rolar a página inicial, existe uma outra aba para o processo de habilitação. Ao clicar nela, o usuário é redirecionado para outro site, com domínio e estilo completamente diferentes, onde deve iniciar seu processo, caracterizando uma duplicação de funções.

---

### Licitação
A funcionalidade Licitação, quando clicada, apresenta frequentemente erro informando estar fora do ar, pedindo ao usuário para acessar posteriormente. Porém, quando retorna ao ar, ao ser selecionada, o site redireciona para o portal do governo do estado em uma tela sem relação com a licitação desejada inicialmente, não mostrando a funcionalidade correta.

---

## Referências Usadas e IA Generativas

> BARBOSA, S. D. J. et al. **Interação Humano-Computador e Experiência do Usuário**. 1. ed. Rio de Janeiro: Autopublicação, 2021.Cap 12. p. 282.

## Histórico de Versão
| Versão | Data | Descrição | Autor | Revisor |
| :--- | :--- | :--- | :--- | :--- |
| 1.0 | 11/04/2026 | Criação do documento  |[Vitor Evangelista  ](https://github.com/SemC0ndicao) | [Ingrid Alves](https://github.com/alvesingrid) |
| 1.1 | 22/04/2026 | Adição do historico de versão| [Ingrid Alves](https://github.com/alvesingrid) |[Hugo Freitas Silva](https://github.com/HugoFreitass) |
