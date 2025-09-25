# Configuração Inicial

Este guia explica como configurar o ambiente para começar a usar o Meu Serviço API.

## Pré-requisitos

- Conta ativa no portal do Meu Serviço.
- Ferramenta para realizar requisições HTTP (ex.: Postman, cURL ou uma biblioteca como requests em Python).
- Chave de API (obtida no portal do usuário).

## Passos

1. Obtenha sua chave de API:
   - Acesse o portal do Meu Serviço.
   - Navegue até a seção "Credenciais" e gere uma chave de API.

2. Configure o ambiente:
   - Adicione a chave de API ao cabeçalho das requisições:
     ```
     Authorization: Bearer <sua-chave-de-api>
     ```

3. Teste a conexão:
   - Faça uma requisição GET para o endpoint de saúde:
     ```
     curl -H "Authorization: Bearer <sua-chave-de-api>" https://api.meuservico.com/v1/health
     ```
   - Resposta esperada:
     ```json
     {"status": "healthy"}
     ```

## Próximos Passos

Consulte a Referência da API para explorar os endpoints disponíveis.