# Projeto de estudo dos fundamentos de NodeJS.

## Tópicos cobertos no projeto.

GET - Buscar uma informação no servidor
POST - Inserir uma informação no servidor
PUT - Alterar uma informação no servidor
PATCH - Alterar uma informação específica
DELETE - Deletar uma informação no servidor

Tipos de parâmetros:
Route Params => Identificar um recurso para buscar/editar/deletar informação.
Query Params => Paginação/Filtro (?page=1&order=desc)
Body Params => Os objetos para inserção/ alteração de recursos (JSON)


## FinApi - Financeia

### Requisitos

    [X] Deve ser possível criar umma conta
    [X] Deve ser possível buscar o extrato bancário do cliente
    [X] Deve ser possível realizar um depósito
    [X] Deve ser possível realizar um saque
    [X] Deve ser possível buscar o extrato bancário do cliente por data
    [X] Deve ser possível atualizar dados da conta do cliente
    [X] Deve ser possível obter dados da conta do cliente
    [X] Deve ser possível deletar uma conta
    [X] Deve ser possível retornar o balanço da conta.

### Regras de negócio

    [X] Não deve ser possível cadastrar uma conta com CPF já existente
    [X] Não deve ser possível fazer depósito em uma conta não existente
    [X] Não deve ser possível buscar extrato em uma conta não existente
    [X] Não deve ser possível fazer saque em uma conta não existente
    [X] Não deve ser possível fazer saque quando o saldo for insuficiente
    [X] Não deve ser possível excluir uma conta não existente

## Ferramenta Insomnia utilizada para testar as rotas.

