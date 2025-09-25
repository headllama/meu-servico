# Referência da API

Esta seção descreve os endpoints disponíveis no Meu Serviço API.

## Endpoint: /v1/users

### GET /v1/users
Retorna a lista de usuários.

- Cabeçalho: Authorization: Bearer <sua-chave-de-api>
- Parâmetros: Nenhum
- Resposta:
  ```json
  [
    {
      "id": 1,
      "name": "João Silva",
      "email": "joao@exemplo.com"
    }
  ]
  ```

### POST /v1/users
Cria um novo usuário.

- Cabeçalho: Authorization: Bearer <sua-chave-de-api>
- Corpo:
  ```json
  {
    "name": "João Silva",
    "email": "joao@exemplo.com"
  }
  ```
- Resposta:
  ```json
  {
    "id": 1,
    "name": "João Silva",
    "email": "joao@exemplo.com"
  }
  ```

## Endpoint: /v1/health
Verifica a saúde do serviço.

- Método: GET
- Cabeçalho: Authorization: Bearer <sua-chave-de-api>
- Resposta:
  ```json
  {"status": "healthy"}
  ```