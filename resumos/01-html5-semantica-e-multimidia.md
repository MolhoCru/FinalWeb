# Resumo 1 — HTML5: estrutura, semântica e multimídia

## Estrutura básica

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Título da página</title>
  <link rel="stylesheet" href="style.css">
</head>
<body> ... </body>
</html>
```

## Tags semânticas

| Tag | Uso |
|---|---|
| `header` | Cabeçalho da página ou de uma seção |
| `nav` | Menu de navegação |
| `main` | Conteúdo principal (um por página) |
| `section` | Seção temática |
| `article` | Conteúdo independente (post) |
| `aside` | Conteúdo complementar |
| `footer` | Rodapé |
| `figure` / `figcaption` | Imagem com legenda |
| `details` / `summary` | Bloco expansível |

**Por quê?** Código mais legível, acessível e melhor ranqueado (SEO).

## Texto

`h1`–`h6`, `p`, `strong`, `em`, `sub`, `sup`, `br`, `blockquote`, `span`, `div`.

## Links

- Simples: `<a href="url">texto</a>`
- Âncora interna: `<a href="#secao">` + `id="secao"`
- Nova aba: `target="_blank" rel="noopener noreferrer"`
- Imagem como link: `<a href><img></a>`

## Multimídia

- `<img src alt width height>` — sempre com `alt`
- `<video controls width poster><source src type></video>`
- `<audio controls><source src type></audio>`

## Listas e tabelas

- `ol` (ordenada), `ul` (não ordenada), `li`
- Tabela: `table > thead/tbody > tr > th/td`

## Formulários

`form`, `label for`, `input` (`text`, `email`, `checkbox`, `radio`, `submit`), `textarea`, `select`, `button`; atributo `required` para validação nativa.

## SEO básico

`<title>`, `meta description`, `keywords`, `robots`, `alt` nas imagens, hierarquia de títulos, HTML semântico.
