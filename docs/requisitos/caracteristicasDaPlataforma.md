# Características da Plataforma

## Rastreabilidade
|Artefato(s) | Autore(s)|
| --- | --- |
| Página de Características da Plataforma | Ingrid |

## 1. Visão Geral
Este documento descreve as características da plataforma do portal web do **Laboratório Sabin**, que é o objeto de estudo deste projeto de Interação Humano-Computador (IHC). O objetivo é definir os requisitos não-funcionais, dispositivos suportados, navegadores compatíveis e restrições tecnológicas que impactam a experiência do usuário.

## 2. Plataforma Alvo
A plataforma principal de interação é a **Web**. O sistema foi concebido para ser acessado por meio de navegadores de internet, sem a necessidade de instalação de software adicional (com exceção de leitores de PDF para visualização de laudos).

### 2.1 Navegadores Suportados (Browsers)
Para garantir que a maior parte do público-alvo tenha uma experiência adequada, a plataforma deve ser compatível e apresentar um funcionamento consistente nos seguintes navegadores modernos:

- **Google Chrome** (versões recentes)
- **Mozilla Firefox** (versões recentes)
- **Safari** (para usuários do ecossistema Apple)
- **Microsoft Edge** (versões recentes)
- Navegadores mobile nativos (Chrome para Android, Safari para iOS)

## 3. Dispositivos Suportados
O acesso ao portal web abrange diferentes tipos de dispositivos, devendo empregar design responsivo para se adequar às diversas resoluções de tela:

- **Desktops e Notebooks**: Dispositivos com telas maiores (acima de 1024px), proporcionando uma visualização estendida e maior facilidade para preenchimento de formulários complexos e visualização detalhada de exames.
- **Tablets**: Dispositivos intermediários (telas entre 768px e 1024px), utilizados tanto na orientação vertical quanto horizontal. A interface deve manter botões acessíveis ao toque (touch).
- **Smartphones (Mobile)**: Dispositivos de telas menores (geralmente abaixo de 768px). A interface deve ser focada no acesso rápido às funcionalidades principais, como download de laudos, busca por unidades e agendamentos.

## 4. Requisitos e Restrições Tecnológicas

### 4.1 Conectividade
- O sistema depende de **conexão ativa com a internet** para autenticação de usuários, carregamento de dados em tempo real (como horários disponíveis) e download de laudos médicos. 
- O tempo de resposta para operações críticas não deve prejudicar a experiência em conexões móveis mais lentas (como 3G).

### 4.2 Segurança e Privacidade
- Sendo um portal da área da saúde, a plataforma lida com dados sensíveis (informações médicas, dados pessoais).
- Requer o uso de protocolos seguros (**HTTPS/SSL**) para tráfego de informações.
- Autenticação de usuário segura (login via e-mail/CPF e senha).

### 4.3 Tecnologias Adicionais
- **Visualizador de PDF**: Para o acesso aos laudos, o usuário deve ter um visualizador de PDF no navegador ou instalado no dispositivo.
- **JavaScript**: A plataforma requer a ativação de JavaScript no navegador para o funcionamento de componentes interativos da interface (validação de formulários, menus suspensos, carregamento dinâmico).


---
## Referência Bibliográfica

> BARBOSA, S. D. J. et al. Interação Humano-Computador e Experiência do Usuário. 1. ed. Rio de Janeiro: Autopublicação, 2021.

____

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :---: | :---: | :--- | :--- | :--- |
| 1.0 | 11/05/2026 | Criação do documento de características da plataforma | [Ingrid Alves](https://github.com/alvesingrid) | [Hugo Freitas Silva](https://github.com/HugoFreitass) |
| 1.1 | 15/05/2026 | Adição da rastreabilidade dos autores dos artefatos | [Philipe Amancio](https://github.com/Philipe-Chill) | [Ingrid Alves](https://github.com/alvesingrid) |
