# Burger Queen

![logo-burger-queen](https://user-images.githubusercontent.com/61169584/90281151-82aff980-de42-11ea-8ac5-b63345b5abd0.png)

### Acesse a página clicando [aqui](https://burger-queen-a7469.web.app/)

## Índice

* [1. Prefácio](#1-prefácio)
* [2. Planejamento do Projeto](#2-planejamento-do-projeto)
* [3. Prototipagem](#3-prototipagem)
* [4.Implementações Futuras](#4-Implementacoes-futuras)
* [5.Aprendizado](#5-aprendizado)
* [6. Tecnologias Utilizadas](#6-tecnologias-utilizadas)
* [Autoria](#autoria)

***

## 1. Prefácio

A aplicação Burger Queen oferece um produto digital para restaurantes. Nesta aplicação o cliente proporciona aos seus funcionários uma interface capaz de automatizar o fluxo de anotações de pedidos e envio da solicitação para a cozinha. O sistema conta com a tecnologia de privacidade na página de cada cargo, ou seja, o garçom/garçonete serão direcionados automaticamente para a página de anotação de pedidos e o cozinheiro terá acesso apenas a página de exibição das solicitações enviadas pelos funcionários do salão. 

## 2. Planejamento do projeto

A nível de organização, o nosso projeto foi dividido por sprints e para guiar nosso trabalho, contamos com a estruturação de Histórias de Usuário e só avançamos conforme a HU anterior estivesse totalmente usual e sem nenhum bug.

#### História 1
Como definição de pronto dessa primeira história, decidimos que o usuário poderia se cadastrar como Atendente ou como Cozinheiro.

Em ambos casos, na tela de registro o usuário pode definir o nome que irá aparecer no display.
Ele deve inserir um e-mail e uma senha válidos, caso algum dos campos esteja inválido, a página exibe uma mensagem de erro e solicita que o usuário tente novamente. Quando o cadastro do usuário é feito com sucesso, automaticamente ele é direcionado para a página de login. 

Na página de login, se o usuário insere algum e-mail inválido ou digita uma senha errada, novamente a página exibe uma mensagem de erro para que ele tente novamente. Quando obtém sucesso, o usuário é automaticamente direcionado para o página correspondente ao seu cargo.

#### História 2

As definições de pronto dessa história consistem no Atendente conseguir anotar o nome e a mesa do cliente, selecionar os produtos requeridos pelo cliente, verificar o resumo do pedido, tal como quantidade e preço e por fim, deletar pedidos antes de enviá-los para a cozinha caso seja solicitado pelo cliente. 

Além disso, após o envio ser feito com sucesso, os campos de inserção de nome e mesa são resetados e a página exibe um alerta informando o sucesso.

#### História 3
