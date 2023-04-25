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

* ID do pedido.
* Motivo da rejeição.

## Pré Condições

* Pedido deve existir e estar pendente.
* Usuário deve estar _logado_.
* Usuário deve estar conectado à internet.

## Saídas

Não há saídas.

## Pós Condições

* Estado do pedido no sistema será alterado.
* Reenbolso será realizado.

## Fluxo de Eventos Principal

Usuário selecionará o pedido à ser rejeitado e insirirá então um motivo para a rejeição do mesmo. Uma mensagem de sucesso então aparecerá.
