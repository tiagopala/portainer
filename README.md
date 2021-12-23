# Portainer Project

# Name

## Description

Este projeto é composto por um arquivo do tipo docker-compose responsável por subir o portainer já se conectando com o ambiente de desenvolvimento local.

## Explanations

- O volume: ```/var/run/docker.sock:/var/run/docker.sock``` é responsável pelo compartilhamento do ambiente local de desenvolvimento. É devido a ele que podemos visualizar as informações referentes ao nosso docker dentro do portainer. 

- Já o segundo volume: ```/volume/data:/data``` é responsável por compartilhar os dados do portainer na pasta local do próprio computador.

## Usage

- Estar no diretório ```Portainer\``` e executar o seguinte comando ```docker-compose -f docker-compose.yml up -d```

## Authors

- Tiago Pala Baraúna
    - [Linkedin](linkedin.com/in/tiago-pala/)
    - [Twitter](https://twitter.com/tiagopala98)
    - [Gitlab](https://gitlab.com/tiagopala)