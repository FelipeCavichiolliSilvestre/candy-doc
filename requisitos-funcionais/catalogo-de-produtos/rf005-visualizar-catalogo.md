# RF005 - Visualizar Catálogo

### Atores

* [x] Cozinheiro
* [ ] Entregador
* [ ] Cliente

### Prioridade

* [x] Essencial
* [ ] Importante
* [ ] Desejável

## Entradas

* Página

## Pré Condições

* Usuário deve estar _logado_.
* Usuário deve estar conectado à internet.

## Saídas

Uma lista com itens contendo:

* ID do produto
* Nome do produto
* Descrição do produto
* Fotos do produto
* Preço
* Estoque
* Unidades/Medida

## Pós Condições

Não há pós condições.

## Fluxo de Eventos Principal

Usuário selecionará o catálogo de produtos, uma tabela contendo as informação relevantes dos produtos será exibida, visando a performance a lista conterá até no máximo 20 itens, o usuários então poderá escolher avançar para a próxima página, caso exista uma, que conterá os próximos 20 produtos.

## Fluxo de Eventos Secundários

### Fluxo Secundário 1

Caso não haja nenhum produto cadastrado, uma mensagem será exibida no lugar da tabela.&#x20;
