# Ignite_node

## O que é o ``node.js``?
* Plataforma open-source permite execução da linguagem javascript do lado do servidor.
* Utiliza o um motor v8 que é um interpretador de ``javascript`` criado pela **Google** que acompanha.

## Características do ``node.js``
* Baseado em uma arquitetura Event loop
   * escutando eventos junto com uma **Call Stack**("uma pilha de funções").
* Single - Thread.
* Non-blocking I/O.
* Módulo próprio
   * http
   * dns
   * fs
   * buffer
   ...

## Gerenciadores de pacote
* NPM e Yarn
   * são ferramentas que auxiliam um desenvolvedor a fazer o download de pacotes/libs/frameworks e inserir no seu projeto web.
* Yarn <- Utilizado nessa aplicação

## Frameworks
   * Express <- Utilizado nesa aplicação
   * Egg.js
   * Nest.js
   * Adonis.js
   ...

# API Rest

## O que é API?
   * É o acrônimo para Application Programming Interface(Interface de Programação de Aplicativos).
   * É um conjunto de especificaçoes de possiveis interações entre aplicações.
## O que é Rest?
   * É o acrônimo para Representation State Transfer(Transferência Representacional de Estado).
   * É um modelo de arquitetura.
   * 6 regras:
      1. Client-Server
      2. Stateless
      3. Cache-Control
      4. Interface Uniforme
         * Identificação dos recursos
            * http://enderecoservidor.com.br/products <- exemplo
         * Representação dos recursos
         * Mensagens auto-descritivas
         * HATEOAS(Hypertext As The Engine Of Application State) exemplo:
         ```js
         {
            "id": 1,
            "user": "FulanoSilva",
            "created_at": "2020-10-10",
            "commentsLink": "api/users/1/comments"
         }
         ```
      5. Camadas
      6. Código Sob Demanda
