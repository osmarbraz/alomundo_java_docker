# Alomundo Java com Docker

Aplicação **Alomundo** desenvolvida em **Java** e executada em um container Docker.

## Sobre o projeto

- O projeto foi desenvolvido utilizando o **NetBeans**.
- O nome do projeto deve ser **alomundo_java_docker**.
- Utiliza o **Java 8**.
- Utiliza o **Apache Maven** para automatizar o processo de construção da aplicação.
- Utiliza o **Docker** para criar uma imagem e executar a aplicação em um container.

## Comandos Docker
 - Utilizer o terminal do powershel em modo administrador. 

### Construir a aplicação
 - docker build -t alomundo_java_docker .

### Rodar a aplicação
 - docker run --rm alomundo_java_docker

### Execução
 - A saída da aplicação é no próprio terminal.

### Remover imagem
 - docker rmi alomundo_java_docker
