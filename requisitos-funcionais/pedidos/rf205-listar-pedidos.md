# RF205 - Listar Pedidos

### Atores

* [x] Cozinheiro
* [x] Entregador
* [ ] Cliente

### Prioridade

* [x] Essencial
* [ ] Importante
* [ ] Desejável

## Entradas

* Página.
* Data do pedido (opcional).
* Estado do pedido (opcional).

## Pré Condições

* Usuário deve estar _logado_.
* Usuário deve estar conectado à internet.

## Saídas

Uma lista com itens contendo:

* ID do pedido.
* Nome/número do cliente.
* Destino.
* Produtos comprados.
* Preço total.
* Estado.

## Pós Condições

Não há pós condições.

## Fluxo de Eventos Principal

Usuário selecionará a listagem de pedidos, uma tabela contendo os dados especificados em [Saídas](#saídas) será exibida.

## Fluxo de Eventos Secundários

### Fluxo Secundário 1

Caso não haja nenhum pedido com as propriedades estipuladas em [Entradas](#entradas), uma mensagem será exibida no lugar da tabela.&#x20;
