# apresentacoes

Apresentações HTML estáticas hospedadas via GitHub Pages.

**URL base:** https://gabrielferreirab7-coder.github.io/apresentacoes/

## Como funciona

- Cada apresentação é um arquivo `.html` único e autossuficiente (CSS/JS inline, sem build).
- Os decks ficam organizados em pastas por cliente/projeto.
- A `index.html` na raiz lista tudo com link.

## Estrutura

```
apresentacoes/
├── index.html                         # página índice (lista os decks)
└── fast/                              # cliente Fast Sistemas Construtivos
    └── falta-de-resposta-varejo.html
```

## Adicionar um novo deck

1. Coloque o HTML na pasta do cliente (crie a pasta se não existir): `cliente/nome-do-deck.html`
2. Adicione um link no `index.html`, na seção do cliente.
3. Commit e push:
   ```bash
   git add .
   git commit -m "add: <nome do deck>"
   git push
   ```
4. Em ~1 minuto o link já está no ar:
   `https://gabrielferreirab7-coder.github.io/apresentacoes/cliente/nome-do-deck.html`

## Observações

- Repositório público (necessário para GitHub Pages no plano gratuito).
- Não suba nada sensível: tudo aqui fica acessível por quem tiver o link.
- O `index.html` usa `noindex` para não aparecer em buscas.
