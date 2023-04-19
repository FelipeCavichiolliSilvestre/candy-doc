# RF203 - Rejeitar pedido simples

### Atores

* [ ] Cozinheiro
* [x] Entregador
* [ ] Cliente

### Prioridade

* [ ] Essencial
* [x] Importante
* [ ] Desejável

## Entradas

Entradas:

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

## Fluxo de Eventos Principal

Usuário selecionará o pedido à ser confirmado e insirirá um tempo estimado de entrega. Uma mensagem de sucesso então aparecerá.

