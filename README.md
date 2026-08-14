# 📧 Microsserviço de Notificação

Microsserviço responsável pelo **envio de notificações por e-mail** relacionadas às tarefas agendadas no sistema.

O serviço foi desenvolvido utilizando Java e Spring Boot, com integração com serviço de e-mail e utilização de templates para construção das mensagens.

## 🚀 Tecnologias

* Java 17
* Spring Boot
* Spring Mail
* Thymeleaf
* APIs REST
* Docker
* Gradle
* Git

## 📌 Responsabilidades

O microsserviço é responsável por:

* Receber solicitações de notificação
* Processar informações da tarefa
* Construir o conteúdo do e-mail
* Utilizar templates HTML
* Enviar notificações por e-mail

## ✉️ Envio de e-mails

O projeto utiliza **Spring Mail** para integração com o serviço de e-mail.

Os templates das mensagens são desenvolvidos utilizando **Thymeleaf**, permitindo a criação de e-mails com conteúdo dinâmico.

## 🏗️ Integração

O microsserviço faz parte da arquitetura do **Agendador de Tarefas** e é utilizado para realizar as notificações relacionadas às tarefas cadastradas.


## ▶️ Como executar

### Pré-requisitos

* Java 17
* Docker
* Docker Compose
* Git

Clone o projeto:

```bash
git clone https://github.com/LiaraFreitas/notificacao.git
```

Execute a aplicação utilizando sua IDE ou Gradle.

## 🔗 Projeto completo

Este microsserviço faz parte do projeto **Agendador de Tarefas**:

* [Agendador de Tarefas](https://github.com/LiaraFreitas/agendador-tarefas)
* [Usuario](https://github.com/LiaraFreitas/usuario)
* [BFF](https://github.com/LiaraFreitas/bff-agendador-tarefas)
