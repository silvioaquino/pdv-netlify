# Sistema PDV - Netlify

Sistema de PDV completo rodando na Netlify com funções serverless.

## Configuração

1. Faça o deploy no Netlify
2. Configure as variáveis de ambiente:
   - `DATABASE_URL`: URL de conexão com o NeonDB

## Estrutura

- Frontend: Arquivos estáticos em `/public`
- Backend: Função serverless em `/netlify/functions/api.js`

## URLs

- Frontend: `https://seusite.netlify.app`
- API: `https://seusite.netlify.app/api/*`
- Webhook: `https://seusite.netlify.app/api/webhook/vendas`