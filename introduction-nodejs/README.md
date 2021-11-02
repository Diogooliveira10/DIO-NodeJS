## Conhecendo Node.JS
    O NodeJs é um ambiente de execução do JavaScript em server-side. Ele nos dá a possibilidade de rodar localmente o JavaScript fora do navegador.
    
    Todo navegador possui um Interpretador de JavaScript rodando ali por trás dos panos para fazer as coisas funcionarem:
        *   Safari - Nitro
        *   Mozilla - SpiderMonkey
        *   Edge - Chakra
        *   Chrome - V8

    Em 2009 um estudante chamado Ryan Dahl criou o Node.js a partir do interpretador do navegador Chrome, o famoso JavaScript Engine V8. Com isso temos a possibilidade de rodar o JavaScript fora do navegador,diminuindo o processamento e trabalhando com interpretação em tempo real.

## Como o Node.js funciona?
    O node.js trabalha com single-thread, as requisições no node são assíncronas, agilizando assim a entrega.
    ex:
       function eventLoop() {
           var a = 1
           var b = 2
           var c = 3

           console.log(a)

           setTimeout(() => {
               console.log(b)
           }, 1000)

           console.log(c)
       } 

       eventLoop()

* Blocking - Síncrono, pois a entrega depende que todas as requisições estejam prontas.
* Non-blocking - Assíncrono, pois a entrega é feita mesmo sem todas as requisições estarem prontas. (Trabalha com o Event-loop).
* Event-loop - execução das requisições de forma assíncrona.

## Vantagens do Node.js
    *   Flexibilidade;
    *   Leveza;
    *   Escalabilidade;
    *   Redução de custos;
    *   Maior repositório do mundo - NPM;
    *   Mesma linguagem no Front-End e Back-End.

## NPM (Node package manager)
    Com a criação do NodeJS também surgiu o NPM. que é uma ferramenta de gerenciamento de pacotes do Node, serve pra gente dar um upgrade nos nossos projetos usando frameworks e bibliotecas.
