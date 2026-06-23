# Portfólio — Gabriel Silva

Site pessoal de Gabriel Silva, desenvolvedor back-end. Página única, estática, sem etapa de build.

## Stack

- HTML + runtime `dc` (`support.js`) — React/ReactDOM são carregados automaticamente via CDN
- GSAP + ScrollTrigger (em `vendor/`) para as animações de scroll

## Rodar localmente

Por usar `fetch`, precisa de um servidor HTTP (abrir o arquivo via `file://` não funciona):

```bash
npx serve .
# ou
python -m http.server
```

Depois acesse `http://localhost:3000` (ou a porta indicada).

## Deploy na Vercel

Projeto estático — **nenhuma configuração de build necessária**.

1. Importe o repositório na Vercel
2. Framework Preset: **Other** (sem build command, sem output directory)
3. Deploy

A Vercel serve `index.html` na raiz automaticamente.
