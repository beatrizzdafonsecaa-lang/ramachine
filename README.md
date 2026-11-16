# Ramachine

Landing page criada para a Ramachine, empresa que realiza locação de máquina de ursinhos para aniversários, casamentos e confraternizações em São Paulo, Sorocaba e região.

Essa landing page foi criada com o objetivo de filtrar melhor os leads e de apresentar o serviço realizado pela empresa, tirando possíveis dúvidas.

No ar em https://www.ramachine.com.br

## Pastas

- `site/`: o site publicado. Um `index.html` com HTML, CSS e JavaScript puros, e a pasta `assets/` com imagens e vídeos. Sem framework e sem etapa de build.
- `marca/`: arquivos da marca (ursinho, selo, nome e garra) com fundo transparente.
- `servidor.js`: servidor local só para pré-visualizar o site.

## Ver no computador

```bash
node servidor.js
```

Abra http://localhost:8123 no Chrome. Abrir o `index.html` com dois cliques também funciona, mas o vídeo do topo só anda com o scroll quando a página é servida pelo servidor local.

## Publicar

O site fica na Vercel, no projeto `ramachine`. Dentro da pasta `site`:

```bash
npx vercel deploy --prod
```

`site/vercel.json` redireciona `ramachine.com.br` e `ramachine.vercel.app` para `www.ramachine.com.br`.

## Medição

Google Tag Manager `GTM-PNMFP8NK`, com Google Analytics 4 dentro. A medição só grava cookies depois que o visitante aceita no aviso de cookies.
