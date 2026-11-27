# Resumo 2 — CSS

## Formas de aplicar CSS

| Forma | Exemplo | Quando usar |
|---|---|---|
| Inline | `<p style="color:red">` | Casos pontuais (evitar) |
| Interno | `<style>...</style>` | Página única |
| **Externo** | `<link rel="stylesheet" href="style.css">` | **Recomendado** |

## Seletores

`tag`, `.classe`, `#id`, `a:hover`, `li:nth-child(2n)`, `input:focus`, `:checked`, `::before`, `::after`, seletores `+` (irmão adjacente) e `~` (irmão geral).

## Propriedades essenciais

- **Texto:** `color`, `font-family`, `font-size`, `font-weight`, `font-style`, `text-align`, `text-decoration`, `text-transform`, `letter-spacing`, `line-height`
- **Fundo e bordas:** `background-color`, `border`, `border-radius`, `box-shadow`
- **Box model:** `width`, `height`, `max-width`, `margin`, `padding`, `box-sizing: border-box`
- **Exibição:** `display` (`block`, `inline-block`, `flex`, `grid`, `none`), `opacity`, `overflow`
- **Posicionamento:** `position` (`static`, `relative`, `absolute`, `fixed`, `sticky`), `top/left`, `z-index`
- **Outros:** `cursor`, `list-style`, `border-collapse`

## Flexbox (1 dimensão)

```css
.linha { display: flex; justify-content: space-between; align-items: center; gap: 16px; flex-wrap: wrap; }
```

## Grid (2 dimensões)

```css
.cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 20px; }
.destaque { grid-column: span 2; grid-row: span 2; }
```

## Recursos modernos

- **Variáveis:** `:root { --cor: #c68b59; }` → `color: var(--cor);`
- **Gradientes:** `linear-gradient`, `radial-gradient`
- **Transições e transformações:** `transition`, `transform`
- **Animações:** `@keyframes` + `animation`
- **Funções:** `clamp()`, `min()`, `calc()`
- **Acessibilidade:** `:focus-visible`, `prefers-reduced-motion`

## Responsividade

```css
@media (max-width: 768px) { .grade { grid-template-columns: 1fr; } }
```

Não esquecer: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
