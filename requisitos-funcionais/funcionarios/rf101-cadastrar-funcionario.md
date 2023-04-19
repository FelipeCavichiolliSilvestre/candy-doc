# RF101 - Cadastrar Funcionário

### Atores

* [x] Cozinheiro
* [ ] Entregador
* [ ] Cliente

### Prioridade

* [ ] Essencial
* [x] Importante
* [ ] Desejável

## Entradas

* Nome
* Senha
* Função (Cozinheiro, Entregador)

## Pré Condições

* Um funcionário com mesmo nome não deve estar cadastrado.
* Usuário deve estar _logado_.
* Usuário deve estar conectado à internet.

## Saídas

* ID do funcionário
* Nome
* Função

## Pós Condições

* Funcionário será cadastrado no sistema

## Fluxo de Eventos Principal

Usuário deverá inserir os dados descritos em “Entradas e pré condições” e confirmar a criação do funcionário. O sistema então exibirá um mensagem de sucesso e o funcionário recém criado.

## Fluxo de Eventos Secundários

### Fluxo Secundário 1

Caso já haja um funcionário cadastrado com o nome inserido, exibir uma mensagem de erro informando o usuário e permitir a repetição da ação.
