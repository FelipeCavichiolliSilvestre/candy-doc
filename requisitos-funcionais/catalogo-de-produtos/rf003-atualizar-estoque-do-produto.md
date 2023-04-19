# RF003 - Atualizar Estoque do Produto

Em uma atualização de estoque há dois motivos principais para a ação:&#x20;

* Uma recontagem foi feita e o estoque diferiu do esperado.
* Um produto atingiu sua data de validade.

Ambos motivos necessitam ser especificados, já que possuem implicações diferentes ao negócio.

### Atores

* [x] Cozinheiro
* [ ] Entregador
* [ ] Cliente

### Prioridade

* [x] Essencial
* [ ] Importante
* [ ] Desejável

## Entradas

* ID do produto.
* Motivo.
* Estoque.

## Pré Condições

* Produto deve existir.
* Usuário deve estar _logado_.

## Saídas

* ID do produto.
* Estoque.

## Pós Condições

* Estoque será atualizado no sistema.
* Caso estoque caia para 0, esconde o produto no catálogo do WhatsApp.

## Fluxo de Eventos Principal

Usuário selecionará um produto, informará o motivo de atualização de estoque (Recontagem ou Vencimento) e o novo estoque, ao confirmar a atualização, o sistema exibirá uma mensagem de sucesso.
