
# 📩 Notificação do Agendador de Tarefas - Microsserviços em Java

Este repositório faz parte do projeto **Agendador de Tarefas**, um sistema voltado para gerenciamento de usuários, criação de tarefas e envio de notificações automatizadas por e-mail.  

O módulo **Notificação** é responsável por enviar lembretes de tarefas cadastradas no sistema, garantindo que o usuário seja avisado antes do prazo definido.


## 📌 Status do Projeto

No momento, o projeto está em desenvolvimento.
Neste momento está sendo entregue o segundo microserviço **Agendador de tarefas**.

**Microsserviços planejados**:

- ✅ Cadastro de Usuário (finalizado)
- ✅ Agendador de Tarefas (finalizado)
- ✅ Notificação por Email (finalizado)
- ⏳ BFF (Back For Frontend) (em andamento)


## ⚙️ Tecnologias Utilizadas

- ☕ **Java 17**
- 🌱 **Spring Boot** (Web, Data JPA, Security, Validation)
- 📬 **Spring Mail + Thymeleaf** (Notificações por Email)
- 📬 **Postman** (testes de requisições HTTP)
- 🔄 **GitHub Actions** (CI/CD)
- 🛠️ **Maven** (build e gerenciamento de dependências)
- 🗂️ **Metodologias Ágeis** (Kanban, Git Flow com branches main, develop e feature)


## 🚀 Funcionalidades 

- Envio de notificações por e-mail para os usuários.
- Integração com o módulo de **Cadastro de Usuários**.
- Integração com o módulo de **Criação de Tarefas**.
- Automação dos disparos com base na data/hora definida para cada tarefa.
- 

 ## 📂 Estrutura do Projeto (parcial)

```bash
/notificacao
 ├── src/main/java          # Código principal
 │    └── com/...           # Pacotes de serviços, modelos e controladores
 ├── src/main/resources     # Configurações do projeto
 │    └── application.yml   # Configuração do banco e servidor
 └── pom.xml       
```

## ▶️ Como Rodar o Microsserviço de Usuário

**1.** Clone este repositório:
```bash
git clone https://github.com/LiaraFreitas/notificacao.git
```

**2.** Acesse a pasta:
```bash
cd notificacao

```
**3.** Configure as variáveis no application.yml:

```bash
spring:
  datasource:
    url: jdbc:postgresql://localhost:5432/agendador
    username: seu_usuario
    password: sua_senha
  mail:
    host: smtp.seuprovedor.com
    port: 587
    username: seu_email
    password: sua_senha

```

**4.** Execute o projeto:

```bash
   mvn spring-boot:run

```

## 👨‍💻 Autor

Desenvolvido por **Liara Freitas** no curso da Javanauta.
