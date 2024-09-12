# Documento de Requisitos do Sistema de Gerenciamento de Projetos (SGP) - Segunda Etapa

Este documento detalha os requisitos da segunda etapa do Sistema de Gerenciamento de Projetos (SGP), expandindo as funcionalidades já implementadas na primeira fase. O foco principal desta etapa é aprimorar a interface do usuário, integrar serviços externos, melhorar a segurança e a eficiência do sistema, além de introduzir novas funcionalidades.

## Objetivo

Nesta segunda etapa do desenvolvimento do Sistema de Gerenciamento de Projetos (SGP), o foco será na implementação de novas funcionalidades que aprimorem a interação do usuário, a integração com serviços externos, e a robustez da aplicação. O objetivo é elevar a experiência de gerenciamento de projetos.


## Tecnologias obrigatórias
- **Node JS (API REST, STREAMS, MIDDLEWARE, EXPRESS)**
- **React JS (SPA)**
- **Typescript (Backend & FrontEnd)**
- **MySQL**
- **JWT (Autenticação)**
- **GIT (Versionamento)**


## Estrutura do Projeto 

```
- 📂gerenciamento-projetos
  - 📂backend
  - 📂frontend
```

## **Novas Funcionalidades**

### **Dashboard Interativo**

- Descrição: Criação de uma interface de usuário interativa para gerenciar projetos e usuários, utilizando componentes funcionais e hooks do React. **O dashboard incluirá gráficos que apresentam uma visão geral dos projetos, tipos de projetos, e previsões de acordo com datas e usuários**.
- Local: Frontend

### **Dashboard com Gráficos**

- Descrição: Adição de gráficos ao dashboard para apresentar uma visão geral dos projetos, incluindo **tipos de projetos e previsões**. Esse recurso permitirá aos usuários visualizar rapidamente o progresso e as estatísticas relevantes.
- Local: Frontend

### **Dashboard de Projetos por Usuário com Filtro de Data**

- Descrição: Implementação de um dashboard que permita a visualização de projetos filtrados por usuário e data, proporcionando uma visão detalhada do envolvimento de cada usuário em diferentes projetos.
- Local: Frontend

### **Integração com APIs de Terceiros**
- Descrição: O sistema será integrado com APIs externas relevantes para gerenciamento de projetos. Seja criativo na escolha e implementação de APIs no seu projeto.
- Local: Frontend

### **Middlewares Personalizado**
- Descrição: Desenvolvimento de novos middlewares para manipulação de erros, validação de dados, autenticação, segurança e controle.
- Local: Backend

### **Manipulação de Streams**
- Descrição: Implementação de funcionalidades que utilizam Streams do Node.js para upload e processamento de arquivos.(Seed em CSV).
- https://drive.google.com/drive/folders/1WT9Q78-5cUrk_pUc5rWSf1S6iXedqsqv?usp=sharing - Link para arquivo CSV com 1000 projetos 
- Local: Backend

### **Bloqueio de Gerenciamento por Permissão**
- Descrição: Implementação de bloqueios no gerenciamento de projetos baseados nas permissões do usuário, garantindo que apenas usuários autorizados possam realizar determinadas ações.
- Local: Backend

### **Gerenciamento de Cache**
- Descrição: Implementação de uma solução de gerenciamento de cache tanto no frontend quanto no backend para otimizar o desempenho do Sistema
- Local: Frontend + Backend

## **Entrega/Avaliação** 
No geral, tudo será avaliado. Porém nosso foco é descobrir como você aplica os conceitos da programação nos seus projetos, como você soluciona problemas e como irá gerar valor ao produto desenvolvido.

- Estrutura do Código: Manter a organização e clareza do código, com ênfase na aplicação dos conceitos de Clean Code.
- Cumprimento de Requisitos: Garantir que todas as funcionalidades descritas sejam implementadas conforme especificado.
- Lógica de Programação: Soluções eficientes e aplicadas conforme as melhores práticas.
- Metodologia Aplicada: Abordagem estruturada para resolução de problemas e entrega de valor ao produto final.
- Criatividade: Inovar nas soluções propostas, garantindo um produto final robusto e funcional.
- **OBS**: Faça commits claros e descritivos, estaremos atentos a cada detalhe do seu desenvolvimento.

## Checklist 📝

Abaixo estão as implementações que terão de ser feitas no seu projeto. Quanto mais itens você entregar, melhor será sua avaliação. Considere os itens a partir do Nível 2 diferenciais.

---

**Legenda:**

- B -> Backend
- F -> Frontend

---

### Nível 1

|     | Descrição                  | Local |
| --- | -------------------------- | ----- |
| [ ] | Dashboard Interativo           |  F    |
| [ ] | Integração com APIs de Terceiros      |  F   |
| [ ] | Middleware Personalizado           |   B  |
| [ ] | Manipulação de Streams             |   B  |
| [ ] | Adicionar gráficos ao dashboard         |  F    |
| [ ] | Dashboard por usuário com filtro de data           |  F   |
| [ ] | Bloqueio de gerenciamento por permissão     |    B  |
| [ ] | Implementação de testes unitários e de Integração para novas funcionalidades                     |  F B  |
| [ ] |	Otimização e melhoria de desempenho do sistema	    |  F B  |


### Nível 2

|     | Descrição	                                            | Local |
| --- | ------------------------------------------------      | ----- |
| [ ] |	Gerenciamento de Cache	    |  F B  |
| [ ] | Adicionar busca via query para a listagem de projetos	|  F B  |
| [ ] | Adicionar busca via query para a listagem de usuários em projetos	|  F B  |
| [ ] | Ordenação das tabelas clicando no nome da coluna	    |   B  |






