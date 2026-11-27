# Projeto Grão & Aroma — landing page de cafeteria artesanal

Atividade prática: **HTML5 + CSS externo + Git/GitHub**, sem nenhuma linha de JavaScript.

## Requisitos da atividade

| # | Requisito | Como foi atendido |
|---|---|---|
| 1 | `index.html` + `style.css` com CSS externo via `<link>` | `<link rel="stylesheet" href="style.css">` no `<head>`; sem CSS interno ou inline |
| 2 | Propriedades CSS vistas em aula | Marcadas com `[AULA]` nos comentários |
| 3 | Pelo menos 10 propriedades extras | 25 propriedades/recursos marcados com `[EXTRA]` |
| 4 | Git no VS Code + GitHub | Commits e publicação pelo painel Source Control |
| 5 | `index.html` > 300 linhas e `style.css` > 200 | 694 e 1.739 linhas |
| 6 | Código comentado + documentação | Comentários em todas as seções + relatório em PDF |

## Seções da página

Cabeçalho fixo (menu hambúrguer no celular) · Hero · Sobre · Diferenciais · Cardápio (abas) · Galeria (CSS Grid) · Depoimentos · Horários · Planos (Clube do Café) · FAQ · Contato · Rodapé

## Interatividade sem JavaScript

- **Menu hambúrguer:** `<input type="checkbox">` + `:checked ~ .menu`
- **Abas do cardápio:** `<input type="radio">` + `#aba-x:checked ~ #painel-x { display: grid; }`
- **FAQ:** `<details>` / `<summary>` + `.faq__item[open]`
- **Hover:** cards que sobem, ícones que giram, legendas da galeria
- **Rolagem:** barra de progresso e botão "voltar ao topo" com `animation-timeline: scroll()`

## Responsividade

| Ponto de quebra | Mudança |
|---|---|
| ≤ 992px | Grades de 2 colunas viram 1; galeria com 2 colunas |
| ≤ 768px | Menu vira hambúrguer; formulário em 1 coluna |
| ≤ 480px | Galeria em 1 coluna; botões do banner em largura total |

Também: `clamp()`, `min()`, `repeat(auto-fit, minmax())`.

## 25 propriedades e recursos extras

1. Variáveis CSS · 2. Gradientes · 3. `transition` · 4. `transform` · 5. `@keyframes` · 6. `@media` · 7. `position: sticky` · 8. `backdrop-filter` · 9. `filter` · 10. `clamp()`/`min()` · 11. `aspect-ratio` · 12. `auto-fit`/`minmax` · 13. `scroll-behavior` · 14. `:checked` + `~` · 15. `::before`/`::after` · 16. `box-sizing` · 17. `user-select` · 18. `accent-color`/`caret-color` · 19. `:focus-visible` · 20. `:user-invalid` · 21. `resize` · 22. `isolation`/`inset` · 23. `animation-timeline` · 24. `prefers-reduced-motion`/`print` · 25. `::selection`

## Prints

As capturas de tela do site (computador e celular) ficam na pasta [`prints/`](prints/). Veja também o relatório completo: [`atividade-05-grao-e-aroma-relatorio.pdf`](../../relatorios/atividade-05-grao-e-aroma-relatorio.pdf).

## Arquivos que faltam copiar

O relatório descreve `index.html` (694 linhas) e `style.css` (1.739 linhas) nos Apêndices A e B, mas o PDF enviado não inclui esses apêndices. Copie os dois arquivos originais do projeto do grupo para **esta pasta** antes de publicar, junto com as imagens da pasta `prints/`.

```
projetos/grao-e-aroma/
├── index.html   ← copiar do projeto original
├── style.css    ← copiar do projeto original
└── prints/      ← 14 capturas de tela
```
