# Solução de Problemas

Este guia aborda problemas comuns ao usar o Meu Serviço API e como resolvê-los.

## Problemas Comuns

### 1. Erro 401: Unauthorized
- Causa: Chave de API inválida ou ausente.
- Solução:
  - Verifique se a chave de API está correta.
  - Confirme que o cabeçalho Authorization está formatado como Bearer <sua-chave-de-api>.
  - Gere uma nova chave no portal, se necessário.

### 2. Erro 429: Too Many Requests
- Causa: Limite de requisições excedido.
- Solução:
  - Aguarde o período de reset da cota (geralmente 1 hora).
  - Considere otimizar a frequência das requisições.
  - Entre em contato com o suporte para aumentar os limites, se aplicável.

### 3. Resposta Inesperada ou Erro 500
- Causa: Problema no servidor ou requisição malformada.
- Solução:
  - Valide o formato da requisição (ex.: corpo JSON correto).
  - Tente novamente após alguns minutos.
  - Contate o suporte com detalhes do erro.

## Suporte

Se o problema persistir, envie um e-mail para suporte@meuservico.com com:
- Descrição do problema.
- Código da requisição e resposta recebida.
- Horário do ocorrido.