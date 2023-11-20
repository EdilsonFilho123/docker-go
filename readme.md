# Desafios Full Cycle 3.0 - Docker: Desafio Go

## Desafio Proposto (Resumo) :

1) Criar e subir uma imagem no docker hub que ao executar: " <i>docker run < seu-user >/fullcycle</i> ", exibir o resultado: "Full Cycle Rocks!!"

2) Criar o arquivo responsável de exibir o "Full Cycle Rocks!!" utilizando a linguagem <b>Go</b>

3) A imagem do projeto Go precisa ter menos de 2MB


## Desenvolvimento

Através do uso Multistage Building no Dockerfile, a primeiro uma imagem do golang foi usado para compilar o nosso arquivo go responsável pela mensagem "Full Cycle Rocks!!" e depois passar esse arquivo para uma nova imagem de SO leve e que permita execução de arquivos binários (no caso, scratch)!


## Link Docker - Hub

<b>Link: </b> <a href='https://hub.docker.com/r/edilsonfilho/fullcycle'>https://hub.docker.com/r/edilsonfilho/fullcycle</a>

