# RF105 - Login

### Atores

* [x] Cozinheiro
* [x] Entregador
* [ ] Cliente

### Prioridade

* [x] Essencial
* [ ] Importante
* [ ] Desejável

## Entradas

Entradas:

* Nome do funcionário.
* Senha.

## Pré Condições

* Funcionário deve existir.

## Saídas

* ID do funcionário.
* Nome.
* Função.
* JWT (Json Web Token).

## Pós Condições

Não há pós condições.

## Fluxo de Eventos Principal

Usuário insere o nome do funcionário e a senha correspondente e confirma o login, após isso é redirecionado para à pagina inicial.

## Fluxo de Eventos Secundários

### Fluxo Secundário 1

Caso não haja um funcionário com o nome inserido, exibir uma mensagem de erro informando o usuário, e permitir a repetição da ação.

### Fluxo Secundário 2

Caso a senha estiver incorreta, exibir uma mensagem de erro informando o usuário, e permitir a repetição da ação.
