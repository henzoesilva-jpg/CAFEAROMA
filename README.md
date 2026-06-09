````markdown
# ☕ Café Aroma e Sabor - Sistema de Controle de Estoque

Sistema web desenvolvido para gerenciamento de produtos e controle de movimentações de estoque de uma cafeteria, utilizando **Java**, **Spring Boot**, **Thymeleaf** e **MySQL**.

## 📋 Sobre o Projeto

O Café Aroma e Sabor é uma aplicação que permite o cadastro de produtos, controle de entradas e saídas de estoque e acompanhamento das movimentações realizadas no sistema.

O projeto foi desenvolvido seguindo o padrão MVC (Model-View-Controller), utilizando recursos do ecossistema Spring para facilitar o gerenciamento de dados e a construção da interface web.

---

## 🚀 Funcionalidades

### 📦 Gestão de Produtos
- Cadastro de produtos
- Listagem de produtos
- Edição de produtos
- Exclusão de produtos

### 📊 Controle de Estoque
- Registro de movimentações de estoque
- Controle de entradas e saídas
- Atualização automática da quantidade em estoque
- Histórico de movimentações

### 🖥️ Dashboard
- Página inicial do sistema
- Navegação entre módulos

### 🔒 Segurança
- Integração com Spring Security
- Controle de acesso às páginas da aplicação

---

## 🛠️ Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Spring Security
- Thymeleaf
- MySQL
- Maven
- HTML5
- CSS3

---

## 📂 Estrutura do Projeto

```text
src
├── main
│   ├── java
│   │   └── com.example.cafe
│   │       ├── config
│   │       │   └── SecurityConfig
│   │       ├── controller
│   │       │   ├── DashboardController
│   │       │   ├── EstoqueController
│   │       │   └── ProdutoController
│   │       ├── Model
│   │       │   ├── Produto
│   │       │   ├── Usuario
│   │       │   └── MovimentacaoEstoque
│   │       └── Repository
│   │           ├── ProdutoRepository
│   │           ├── UsuarioRepository
│   │           └── MovimentacaoRepository
│   └── resources
│       ├── templates
│       ├── static
│       └── application.properties
````

---

## ⚙️ Configuração do Banco de Dados

Configure o arquivo `application.properties` conforme seu ambiente:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/db_cafe_aroma?createDatabaseIfNotExist=true
spring.datasource.username=SEU_USUARIO
spring.datasource.password=SUA_SENHA

spring.jpa.hibernate.ddl-auto=update
```

> Recomenda-se não versionar credenciais reais no repositório.

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

* Java 17 ou superior
* Maven 3.8+
* MySQL

### Passos

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/cafe-aroma-e-sabor.git
```

2. Acesse a pasta do projeto:

```bash
cd Cafe
```

3. Configure o banco de dados no arquivo:

```text
src/main/resources/application.properties
```

4. Execute a aplicação:

```bash
./mvnw spring-boot:run
```

ou

```bash
mvn spring-boot:run
```

5. Acesse no navegador:

```text
http://localhost:8080
```

---

## 📸 Telas do Sistema

* Página Inicial
* Dashboard
* Cadastro de Produtos
* Listagem de Produtos
* Controle de Estoque
* Histórico de Movimentações

> Adicione capturas de tela aqui para melhorar a documentação.

---

## 🎯 Objetivos do Projeto

* Aplicar conceitos de desenvolvimento web com Spring Boot.
* Implementar operações CRUD.
* Utilizar persistência de dados com JPA/Hibernate.
* Trabalhar com autenticação e segurança.
* Desenvolver uma aplicação de gestão de estoque funcional.

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos e de aprendizado em desenvolvimento Java Web.

---

## 📄 Licença

Este projeto está disponível para fins educacionais.

```

**Sugestão:** antes de publicar no GitHub, remova do `application.properties` a senha do banco (`root / Senai@2024`) e substitua por valores genéricos ou utilize variáveis de ambiente.
```
