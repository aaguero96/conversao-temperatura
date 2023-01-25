# Projeto conversão de temperatura

### Sobre o projeto

O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto

A aplicação é exposta usando a porta 8080

### Rodar a aplicação (somente com imagem no DockerHub)

- Para rodar a aplicação basta rodar o comando: `docker run -d -p 8080:8080 aaguero96/conversao-temperatura:v1`

- Agora acesse a seguinte página: `http://localhost:8080/`

- Aproveite :)

### Rodar a aplicação (somente com repositório)

- Download do repositório HHTP: `git clone https://github.com/aaguero96/conversao-temperatura.git`

- Ou download do repositório SSH: `git clone git@github.com:aaguero96/conversao-temperatura.git`

- Entre na pasta /src: `cd /src`

- Construa a imagem do projeto substituindo IMAGEM_NAME pelo nome que deseja: `docker build -t IMAGEM_NAME .`

- Rode um docker para ter acesso a aplicação: `docker run -d -p 8080:8080 IMAGEM_NAME`

- Agora acesse a seguinte página: `http://localhost:8080/`

- Aproveite :)
