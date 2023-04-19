# RF002 - Atualizar Informação do Produto

### Atores

* [x] Cozinheiro
* [ ] Entregador
* [ ] Cliente

### Prioridade

* [x] Essencial.
* [ ] Importante.
* [ ] Desejável.

## Entradas

* ID do produto.
* Nome do produto (opcional).
* Descrição do produto (opcional).
* Fotos do produto (opcional).
* Unidades/Medida (opcional).

## Pré Condições

* Produto deve existir.
* Um produto com mesmo nome não deve estar cadastrado.
* Usuário deve estar _logado_.

## Saídas

* ID do produto.
* Nome do produto.
* Descrição do produto.
* Fotos do produto.

## Pós Condições

* Produto será atualizado no sistema.
* Produto será atualizado no catálogo do WhatsApp Business.

## Fluxo de Eventos Principal

Usuário selecionará um produto à ser editado, alterará os dados necessários especificados em “Entradas e pós condições”, e confirmará a edição, após isso o sistema exibirá uma mensagem de sucesso.

## Fluxo de Eventos Secundários

### Fluxo Secundário 1

Caso já haja um produto cadastrado com o nome inserido, exibir uma mensagem de erro informando o usuário sobre a duplicidade e permitir a repetição da ação.
