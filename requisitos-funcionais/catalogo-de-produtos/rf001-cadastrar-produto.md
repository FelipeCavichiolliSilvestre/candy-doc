# RF001 - Cadastrar Produto

### Atores

* [x] Cozinheiro
* [ ] Entregador
* [ ] Cliente

### Prioridade

* [x] Essencial
* [ ] Importante
* [ ] Desejável

## Entradas

* Nome do produto
* Descrição do produto (opcional)
* Fotos do produto
* Preço
* Estoque
* Unidades/Medida

## Pré Condições

* Um produto com mesmo nome não deve estar cadastrado.
* Usuário deve estar _logado_.

## Saídas

* ID do produto
* Nome do produto
* Descrição do produto
* Fotos do produto
* Preço
* Estoque
* Unidades/Medida

## Pós Condições

* Produto será cadastrado no sistema.
* Produto será cadastrado no catálogo do WhatsApp Business

## Fluxo de Eventos Principal

Usuário deverá inserir os dados descritos em “Entradas e pré condições” e confirmar a criação do produto. O sistema então exibirá um mensagem de sucesso e o produto recém criado.

## Fluxo de Eventos Secundários

### Fluxo Secundário 1

Caso já haja um produto cadastrado com o nome inserido, exibir uma mensagem de erro informando o usuário sobre a duplicidade e permitir a repetição da ação.
