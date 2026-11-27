# Atividade 2 — Introdução ao Web Design e Controle de Versões

Primeira página web do semestre, usada para praticar **HTML + CSS + JavaScript** e os fundamentos de **Git/GitHub**.

## O que foi feito

- Página com título e um botão que **conta os cliques** e mostra a mensagem "Você clicou N" (toast).
- Três arquivos: `index.html` (estrutura), `style.css` (estilo) e `script.js` (interatividade).
- Versionamento no VS Code: `git init` → commit inicial (v1.0.0) → *Publicar Branch* no GitHub.
- Alteração do título e da cor do botão → novo commit → **tag semântica** `1.1.0`.

## Comandos Git usados

```bash
git init
git add .
git commit -m "primeiro commit - arquivos base"
git commit -am "Mudando cor do botão e trocando frase principal"
git tag 1.1.0
git push origin 1.1.0
```

## Conceitos praticados

| Conceito | Onde aparece |
|---|---|
| CSS externo (`<link>`) | `index.html` |
| JS externo (`<script src>`) | `index.html` / `script.js` |
| `getElementById`, `onclick`, `createElement` | `script.js` |
| `position: fixed`, `transform: translateX(-50%)` | `.toast` |
| `:hover` | `button:hover` |
| Versionamento semântico (MAJOR.MINOR.PATCH) | tag `1.1.0` |

## Arquivos

- [`index.html`](index.html) · [`style.css`](style.css) · [`script.js`](script.js)
- Relatório: [`../../relatorios/atividade-02-relatorio.pdf`](../../relatorios/atividade-02-relatorio.pdf)

> Código recuperado dos prints do relatório. Abra `index.html` no navegador para testar.
