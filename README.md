<div align="center">
    <h1 align="center">DSList Backend 🎮</h1>
</div>

O **DSList Backend** é uma API RESTful desenvolvida em **Java** com **Spring Boot**, baseada no projeto do professor Nélio Alves da **DevSuperior**. O objetivo do projeto é gerenciar uma lista de jogos, permitindo que os usuários visualizem, organizem e personalizem seus jogos favoritos.

Este projeto foi aprimorado para fins educacionais e profissionais, com boas práticas de desenvolvimento, estrutura organizada e documentação clara.

## 🛠️ Tecnologias Utilizadas
- **Java 21**
- **Spring Boot 3.4.2**
- **Spring Data JPA / Hibernate**
- **Banco de Dados H2 / PostgreSQL**
- **Docker para containerização**

## 🚀 Funcionalidades
- ✅ Listagem de jogos
- ✅ Organização de jogos por categoria
- ✅ Ordenação personalizada de jogos dentro das listas

## ⚙️ Como Executar o Projeto
### 📌 Pré-requisitos
Antes de começar, certifique-se de ter instalado na sua máquina:
- [JDK 21](https://www.oracle.com/java/technologies/downloads/#java21)
- [Maven](https://maven.apache.org/download.cgi)
- [PostgreSQL](https://www.postgresql.org/download/) (opcional caso utilize H2)
- [Docker](https://www.docker.com/) (caso deseje rodar o banco de dados via container)

### 🚀 Passos para execução
1. **Clone o repositório:**
  ```bash
    git clone https://github.com/seu-usuario/dslist-backend.git
  ```

2. **Acesse o diretório do projeto:**
  ```bash
    cd dslist-backend
  ```

3. Configure as **variáveis de ambiente** no arquivo application.properties ou application.yml (se estiver usando PostgreSQL)

4. Execute a aplicação:
  ```bash
    ./mvnw spring-boot:run
  ```
A API estará disponível em **http://localhost:8080**.

🔗 Conecte-se comigo no [LinkedIn](www.linkedin.com/in/marcelobezerrambj) e veja mais projetos no meu [GitHub](https://github.com/marcelobezerrajr).
