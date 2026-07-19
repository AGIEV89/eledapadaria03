# Compras da Padaria

Sistema simples para cadastrar insumos e montar o checklist de compras da padaria.

## Vercel

Use a pasta do projeto como raiz do deploy.

Arquivos importantes:

- `public/index.html`: pagina servida pelo Vercel.
- `index.html`: copia da pagina na raiz.
- `vercel.json`: redireciona as rotas para a pagina principal.

Se o Vercel pedir configuracao manual, use:

- Framework Preset: Other
- Build Command: deixe vazio
- Output Directory: public
