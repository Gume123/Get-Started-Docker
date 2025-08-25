# 🚀 To-Do App com CRUD: Um Estudo de Containerização com Docker

Este projeto é um aplicativo simples de gerenciamento de tarefas, com funções **CRUD** (Criar, Ler, Atualizar, Deletar), feito para ser um **estudo prático** sobre a **containerização com Docker**.

Ele demonstra, de forma direta e sem complexidade, como você pode usar o **Docker** e o **Docker Compose** para isolar sua aplicação em um ambiente controlado, facilitando o desenvolvimento, o teste e a implantação.

-----

### 📚 O que este projeto ensina

O principal objetivo aqui não é o aplicativo em si, mas o processo por trás dele. Ao explorar este projeto, você aprenderá a:

  - **Empacotar uma aplicação:** Como criar uma imagem Docker a partir do código do seu projeto usando um `Dockerfile`.
  - **Orquestrar serviços:** Como usar o `docker-compose.yml` para definir e rodar a aplicação e o banco de dados juntos, garantindo que eles se comuniquem corretamente.
  - **Persistir dados:** Como gerenciar volumes para que os dados do seu banco de dados não sejam perdidos ao recriar ou parar os containers.

-----

### 🚀 Como começar

Para praticar com o projeto, siga estes passos:

1.  Tenha o **Docker** e o **Docker Compose** instalados na sua máquina.
2.  Clone este repositório.
3.  No terminal, na pasta do projeto, execute:
    ```bash
    docker-compose up --build
    ```
4.  Pronto\! O aplicativo estará acessível no seu navegador em `http://localhost:PORTA` (verifique a porta definida no seu arquivo `docker-compose.yml`).
