# 2024.1-Dnit-DOC

Repositório de documentação do DNIT 1 no semestre 2024.1

[Página de documentação](https://fga-eps-mds.github.io/2024.1-Dnit-DOC/)

[Repositório de documentação](https://github.com/fga-eps-mds/2024.1-Dnit-DOC)

[Front-End](https://github.com/fga-eps-mds/2024.1-Dnit-Front)

[Service: UpsService](https://github.com/fga-eps-mds/2024.1-Dnit-UpsService)

[Service: EscolaService](https://github.com/fga-eps-mds/2024.1-Dnit-EscolaService)

[Service: UsuarioService](https://github.com/fga-eps-mds/2024.1-Dnit-UsuarioService)

# Rodando o repositório localmente

-   **Requisitos:** Docker, Docker-compose, Git

Clone este repositório com o comando:

    git clone https://github.com/fga-eps-mds/2024.1-Dnit-DOC.git

Dentro do diretório do repositório, rode o seguinte comando para buildar a documentação:

    docker compose build

Feito isso, suba o serviço da página de documentação com o comando:

    docker compose up

Agora basta acessar pelo navegador o endereço http://localhost:3030/ para visualizar a página localmente.
