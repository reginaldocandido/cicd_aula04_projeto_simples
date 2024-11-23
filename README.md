# Projeto Base - Servidor Node.js

Este é um projeto base para a atividade com Docker.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/reginaldocandido/cicd_aula04_projeto_simples.git
   cd projeto-simples


2. Criar o Dockerfile

___________________________________________
3. construir a imagem Docker a partir do Dockerfile, usando o comando:
    ```bash
    docker build -t nome-da-imagem .

___________________________________________
4. executar um container a partir dela:
    ```bash
    docker run -p 3000:3000 nome-da-imagem

___________________________________________
5. Reconstruir a imagem:
    ```bash
    docker build -t nome-da-imagem .

___________________________________________
6. Executar novamente o container com a nova imagem:
    ```bash
    docker run -p 3000:3000 nome-da-imagem