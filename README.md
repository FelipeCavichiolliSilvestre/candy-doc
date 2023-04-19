---
description: >-
  Este documento especifica o sistema Candy, fornecendo aos desenvolvedores as
  informações necessárias para o projeto e implementação, assim como para a
  realização dos testes e homologação.
layout: landing
---

# Introdução

## Convenções, termos e abreviações

### Identificação dos Requisitos

Por convenção, a referência a requisitos é feita através do nome da subseção onde eles estão descritos, seguido do identificador do requisito, de acordo com o esquema abaixo:

\[nome da subseção.identificador do requisito]

Por exemplo, o requisito \[Recuperação de dados.RF016] está descrito em uma subseção chamada “Recuperação de dados”, em um bloco identificado pelo número \[RF016]. Já o requisito não funcional \[Confiabilidade.NF008] está descrito na seção de requisitos não funcionais de Confiabilidade, em um bloco identificado por \[NF008].

### Prioridades dos Requisitos

Para estabelecer a prioridade dos requisitos foram adotadas as denominações “essencial”, “importante” e “desejável”.

* Essencial é o requisito sem o qual o sistema não entra em funcionamento. Requisitos essenciais são requisitos imprescindíveis, que têm que ser implementados impreterivelmente.
* Importante é o requisito sem o qual o sistema entra em funcionamento, mas de forma não satisfatória. Requisitos importantes devem ser implementados, mas, se não forem, o sistema poderá ser implantado e usado mesmo assim.
* Desejável é o requisito que não compromete as funcionalidades básicas do sistema, isto é, o sistema pode funcionar de forma satisfatória sem ele. Requisitos desejáveis são requisitos que podem ser deixados para versões posteriores do sistema, caso não haja tempo hábil para implementá-los na versão que está sendo especificada.

## Descrição Geral do Sistema

Candy possui o objetivo de auxiliar uma doceria caseira à ser mais eficiente em suas vendas e mais precisas em seus relatórios, auxiliando o controle de estoques e a comunicação cliente-doceria.

Afim de alcançar este objetivo o software deverá permitir a gerência de produtos e seus respectivos estoques, assim como a venda online destes produtos para os clientes, é desejável que tal venda aconteça utilizando _bots_ da plataforma de comunicação 'WhatsApp Business'.

### Descrição dos Usuários

#### Cozinheiro

Os cozinheiros são os donos do negócio, também são os responsáveis pela manufaturação dos doces, desse modo, suas principais interações com o sistema são no tocante do catálogo de doces.

#### Cliente

Os clientes são as pessoas que desejam comprar algum produto, desejam que a sua experiência de pedido seja a mais fluída possível.

#### Entregador

Os entregadores são os responsáveis pela a entrega dos pedidos, possuem então a necessidade de visualizar os pedidos em andamento e os endereços atribuídos à eles.