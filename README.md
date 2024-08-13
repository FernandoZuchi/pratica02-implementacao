# Documento de Requisitos do Sistema de Gerenciamento de Projetos (SGP) - Segunda Etapa

Este documento detalha os requisitos da segunda etapa do Sistema de Gerenciamento de Projetos (SGP), expandindo as funcionalidades já implementadas na primeira fase. O foco principal desta etapa é aprimorar a interface do usuário, integrar serviços externos, melhorar a segurança e a eficiência do sistema, além de introduzir novas funcionalidades de monitoramento e notificação.

## Objetivo

Nesta segunda etapa do desenvolvimento do Sistema de Gerenciamento de Projetos (SGP), o foco será na implementação de funcionalidades avançadas que aprimorem a interação do usuário, a integração com serviços externos, e a robustez da aplicação. O objetivo é elevar a experiência de gerenciamento de projetos, proporcionando uma interface interativa e a automação de processos.


## Tecnologias obrigatórias
- **Node JS (API REST, STREAMS, MIDDLEWARE)**
- **React JS (SPA)**
- **Typescript (Tipagem)**
- **MySQL**
- **JWT (Autenticação)**
- **GIT (Versionamento)**
- **Swagger/Postman (Documentação da API)**
- **Nodemailer/Ethereal (Serviço de E-mail)**  

## Estrutura do Projeto 

```
- 📂gerenciamento-projetos
  - 📂backend
    - Container(Caso utilize)
      - Middleware personalizado
      - Serviço de e-mail
      - Implementação de Streams
  - 📂frontend
    - Container(Caso utilize)
      - Dashboard interativo
      - Integração com APIs de terceiros
      - Filtros e bloqueios baseados em permissões
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

### **Middleware Personalizado**
- Descrição: Desenvolvimento de middlewares para manipulação de erros, validação de dados e autenticação. Esses middlewares garantirão uma camada adicional de segurança e controle, interceptando requisições antes de atingirem os endpoints principais.
- Local: Backend

### **Serviço de Envio de E-mails**
- Descrição: Implementação de um serviço de envio de e-mails para notificações automatizadas, como o envio de um link de boas-vindas para novos usuários cadastrados. O serviço será implementado usando bibliotecas como Nodemailer ou Ethereal.
- Local: Backend

### **Manipulação de Streams**
- Descrição: Implementação de funcionalidades que utilizam Streams do Node.js para upload e processamento de arquivos, como documentos anexados aos projetos.
- Local: Backend

### **Seed de Projetos em CSV**
- Descrição: Implementação de um mecanismo para importar projetos de um arquivo CSV, facilitando a inicialização do sistema com dados preexistentes.
- Local: Backend

### **Documentação da API**
- Descrição: Documentação completa da API utilizando Swagger ou Postman, facilitando o uso e a integração da API por outros desenvolvedores. A documentação incluirá detalhes sobre todos os endpoints, parâmetros aceitos, e exemplos de requisições.
- Local: Backend

### **Bloqueio de Gerenciamento por Permissão**
- Descrição: Implementação de bloqueios no gerenciamento de projetos baseados nas permissões do usuário, garantindo que apenas usuários autorizados possam realizar determinadas ações.
- Local: Backend

## **Entrega/Avaliação** 
No geral, tudo será avaliado. Porém nosso foco é descobrir como você aplica os conceitos da programação nos seus projetos, como você soluciona problemas e como irá gerar valor ao produto desenvolvido.

- Estrutura do Código: Manter a organização e clareza do código, com ênfase na aplicação dos conceitos de Clean Code.
- Cumprimento de Requisitos: Garantir que todas as funcionalidades descritas sejam implementadas conforme especificado.
- Lógica de Programação: Soluções eficientes e aplicadas conforme as melhores práticas.
- Metodologia Aplicada: Abordagem estruturada para resolução de problemas e entrega de valor ao produto final.
- Criatividade: Inovar nas soluções propostas, garantindo um produto final robusto e funcional.
- **OBS**: Faça commits claros e descritivos, estaremos atentos a cada detalhe do seu desenvolvimento.

## Checklist 📝

Abaixo estão as implementações que terão de ser feitas no seu projeto. Quanto mais itens você entregar, melhor será sua avaliação.

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
| [ ] | Serviço de Envio de E-mails         |    B  |
| [ ] | Manipulação de Streams             |   B  |
| [ ] | Documentação da API       |    B  |
| [ ] | Adicionar gráficos ao dashboard         |  F    |
| [ ] | Dashboard por usuário com filtro de data           |  F   |
| [ ] | Bloqueio de gerenciamento por permissão     |    B  |
| [ ] | Envio de e-mail ao cadastrar novo usuário          |    B  |
| [ ] | Seed de Projetos em CSV     |    B  |
| [ ] | Implementação de testes unitários e de Integração para novas funcionalidades                     |  F B  |


### Nível 2

|     | Descrição	                                            | Local |
| --- | ------------------------------------------------      | ----- |
| [ ] |	Otimização e melhoria de desempenho do sistema	    |  F B  |




