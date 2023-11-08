# fullcyle

Pasta DesafioGO

Desafio FullCycle - Docker Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go! Você terá que publicar uma imagem no docker hub. Quando executarmos:

docker run ronanrj/fullcycle

Temos que ter o seguinte resultado: Full Cycle Rocks!!

Se você perceber, essa imagem apenas realiza um print da mensagem como resultado final, logo, vale a pena dar uma conferida no próprio site da Go Lang para aprender como fazer um "olá mundo".

Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

https://hub.docker.com/r/ronanrj/fullcycle

docker pull ronanrj/fullcycle



Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:
Full Cycle Rocks!

    Lista de nomes cadastrada no banco de dados.

Gere o docker-compose de uma forma que basta apenas rodarmos: docker-compose up -d que tudo deverá estar funcionando e disponível na porta: 8080.

Suba tudo em um repositório e faça a entrega.

    A linguagem de programação para este desafio é Node/JavaScript.
