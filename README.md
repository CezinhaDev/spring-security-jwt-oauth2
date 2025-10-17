# 🔐 Spring Security 6 + JWT + OAuth2 | Autenticação na Prática

Implementação prática de autenticação e autorização utilizando **Spring Security 6**, **JWT (JSON Web Token)** e **OAuth2**.  
O objetivo deste projeto é demonstrar como proteger rotas, autenticar usuários e gerenciar permissões de acesso em uma aplicação backend Java, seguindo boas práticas de segurança modernas.

---

## 📂 Estrutura do Projeto

SPRINGSECURITY
│
├── src
│ └── main
│ └── java
│ └── tech.buildrun.springsecurity
│ ├── entity
│ │ ├── Role.java
│ │ ├── Tweet.java
│ │ └── User.java
│ └── SpringsecurityApplication.java
│
├── resources
│
├── pom.xml
├── README.md
└── HELP.md

yaml


---

## ⚙️ Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot 3+**
- **Spring Security 6**
- **JWT (JSON Web Token)**
- **OAuth2**
- **JPA / Hibernate**
- **Maven**
- **H2 Database (ou outra de sua escolha)**

---

## 🔑 Funcionalidades

- Cadastro e autenticação de usuários com criptografia de senha  
- Geração e validação de tokens JWT  
- Proteção de rotas por roles (autorizações)  
- Integração com OAuth2 para autenticação segura  
- Exemplo prático de controle de acesso com anotações `@PreAuthorize`  

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU-USUARIO/spring-security-jwt-oauth2.git
Entre na pasta do projeto:

bash
Copiar código
cd spring-security-jwt-oauth2
Execute o projeto com Maven:


mvn spring-boot:run
Acesse no navegador:

arduino
Copiar código
http://localhost:8080
🧠 Conceitos Aplicados
Autenticação com JWT (Bearer Token)

Autorização baseada em roles e permissões

Filtros de segurança personalizados

Configuração do Spring Security moderna (sem WebSecurityConfigurerAdapter)

Boas práticas de segurança em APIs REST

👨‍💻 Autor
César Henrique Alves da Silva
Desenvolvedor Backend em formação | Java | Spring Boot | APIs REST
📫 LinkedIn • GitHub

