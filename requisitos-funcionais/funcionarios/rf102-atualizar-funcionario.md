# RF102 - Atualizar Funcionário

### Atores

* [x] Cozinheiro
* [ ] Entregador
* [ ] Cliente

### Prioridade

* [ ] Essencial
* [ ] Importante
* [x] Desejável

## Entradas

* ID do funcionário.
* Nome (Opcional).
* Senha (Opcional).
* Função (Cozinheiro, Entregador; Opcional).

## Pré Condições

* Funcionário deve existir.
* Um funcionário com mesmo nome não deve estar cadastrado.
* Usuário deve estar _logado_.
* Usuário deve estar conectado à internet.

## Saídas

* ID do usuário.
* Nome.
* Função.

## Pós Condições

* Funcionário será atualizado no sistema.

## Fluxo de Eventos Principal

Usuário selecionará um funcionário à ser editado, alterará os dados necessários especificados em “Entradas e pós condições”, e confirmará a edição, após isso o sistema exibirá uma mensagem de sucesso.

## Fluxo de Eventos Secundários

### Fluxo Secundário 1

Caso já haja um funcionário cadastrado com o nome inserido, exibir uma mensagem de erro informando o usuário e permitir a repetição da ação.

####
