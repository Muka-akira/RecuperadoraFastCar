# Recuperadora Fastcar — site

Site estático: um único `index.html`, sem build e sem dependências.

## Estrutura

```
index.html          página completa (HTML + CSS + JS)
fotos/              fachada e antes/depois
frames/desktop/     95 quadros do hero (carro_001.webp … carro_095.webp)
frames/mobile/      95 quadros do hero para celular
```

Mantenha as pastas `fotos/` e `frames/` ao lado do `index.html`; os caminhos são relativos.

## Rodar no VS Code

Abra a pasta no VS Code e use a extensão **Live Server** (botão "Go Live").
Abrir o arquivo direto com duplo clique também funciona, mas um servidor local é mais fiel ao site publicado.

## Publicar

Envie a pasta inteira para qualquer hospedagem estática (Netlify, Vercel, GitHub Pages, Hostinger etc.).
