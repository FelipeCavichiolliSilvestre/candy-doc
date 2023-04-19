# RF004 - Atualizar Preço do Produto

Durante a atualização de preço é importante armazenar o histórico de tal mudança, para uma geração de relatório mais precisa.

### Atores

* [x] Cozinheiro
* [ ] Entregador
* [ ] Cliente

### Prioridade

* [x] Essencial
* [ ] Importante
* [ ] Desejável

## Entradas

* ID do produto
* Preço

## Pré Condições

* Produto deve existir
* Usuário deve estar _logado_.
* Usuário deve estar conectado à internet.

## Saídas

* ID do produto
* Preço

## Pós Condições

* Preço será atualizado no sistema
* Preço será atualizado no catálogo do WhatsApp business

## Fluxo de Eventos Principal

Usuário selecionará um produto, informará o novo preço e, ao confirmar a atualização, o sistema exibirá uma mensagem de sucesso.
