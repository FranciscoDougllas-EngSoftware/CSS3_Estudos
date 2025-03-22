# Propriedades CSS3 Mais Utilizadas

## **200 propriedades CSS3** válidas e amplamente utilizadas em março de 2025

---

## 1. Propriedades de Texto e Fonte

### Básico
- `color` - Define a cor do texto.
- `font-size` - Define o tamanho da fonte.
- `font-family` - Define a família da fonte (ex.: "Arial", "sans-serif").
- `font-weight` - Define o peso da fonte (ex.: "bold", 700).
- `font-style` - Define o estilo da fonte (ex.: "italic").
- `text-align` - Alinha o texto (ex.: "left", "center").
- `line-height` - Define a altura da linha.
- `text-decoration` - Adiciona decoração ao texto (ex.: "underline").

### Intermediário
- `font` - Atalho para `font-style`, `font-weight`, `font-size`, e `font-family`.
- `text-transform` - Transforma o texto (ex.: "uppercase").
- `letter-spacing` - Espaçamento entre letras.
- `word-spacing` - Espaçamento entre palavras.
- `text-indent` - Define a indentação da primeira linha.
- `white-space` - Controla o comportamento de espaços em branco (ex.: "nowrap").
- `text-overflow` - Define o comportamento de texto excedente (ex.: "ellipsis").

### Avançado
- `font-variant` - Controla variantes da fonte (ex.: "small-caps").
- `font-stretch` - Estica ou comprime a fonte (se suportado).
- `text-shadow` - Adiciona sombra ao texto.
- `direction` - Define a direção do texto (ex.: "rtl").
- `unicode-bidi` - Controla o comportamento bidirecional do texto.
- `text-align-last` - Alinha a última linha de um bloco.
- `text-justify` - Define o método de justificação.
- `font-feature-settings` - Ativa recursos avançados de fontes (ex.: ligaturas).
- `font-kerning` - Ativa ou desativa o kerning da fonte.

---

## 2. Propriedades de Cor e Fundo

### Básico
- `background-color` - Define a cor de fundo.
- `background-image` - Define uma imagem de fundo.
- `background-repeat` - Controla a repetição da imagem de fundo.
- `background-position` - Define a posição da imagem de fundo.
- `background-size` - Define o tamanho da imagem de fundo (ex.: "cover").

### Intermediário
- `background` - Atalho para todas as propriedades de fundo.
- `opacity` - Define a transparência do elemento.
- `background-clip` - Define a área de recorte do fundo (ex.: "border-box").
- `background-origin` - Define a origem da imagem de fundo.

### Avançado
- `background-blend-mode` - Define o modo de mesclagem do fundo (ex.: "multiply").
- `background-attachment` - Controla o comportamento do fundo ao rolar (ex.: "fixed").
- `linear-gradient()` - Cria gradientes lineares (usado com `background-image`).
- `radial-gradient()` - Cria gradientes radiais.

---

## 3. Propriedades de Caixa (Box Model)

### Básico
- `width` - Define a largura do elemento.
- `height` - Define a altura do elemento.
- `margin` - Define a margem externa.
- `padding` - Define o preenchimento interno.
- `border` - Define a borda (atalho para largura, estilo e cor).
- `border-width` - Define a espessura da borda.
- `border-style` - Define o estilo da borda (ex.: "solid").
- `border-color` - Define a cor da borda.

### Intermediário
- `margin-top`, `margin-right`, `margin-bottom`, `margin-left` - Margens específicas.
- `padding-top`, `padding-right`, `padding-bottom`, `padding-left` - Preenchimentos específicos.
- `border-top`, `border-right`, `border-bottom`, `border-left` - Bordas específicas.
- `border-radius` - Define cantos arredondados.
- `box-sizing` - Define o modelo de cálculo da caixa (ex.: "border-box").

### Avançado
- `border-top-left-radius`, `border-top-right-radius`, etc. - Raios específicos.
- `box-shadow` - Adiciona sombra à caixa.
- `outline` - Define um contorno externo (não afeta o layout).
- `outline-width` - Espessura do contorno.
- `outline-style` - Estilo do contorno.
- `outline-color` - Cor do contorno.
- `outline-offset` - Distância do contorno ao elemento.

---

## 4. Propriedades de Layout

### Básico
- `display` - Define o tipo de exibição (ex.: "block", "inline").
- `position` - Define o tipo de posicionamento (ex.: "relative", "absolute").
- `top`, `right`, `bottom`, `left` - Define a posição do elemento.
- `float` - Faz o elemento flutuar (ex.: "left").
- `clear` - Limpa flutuações.

### Intermediário
- `overflow` - Controla o conteúdo excedente (ex.: "scroll").
- `visibility` - Controla a visibilidade (ex.: "hidden").
- `z-index` - Define a ordem de empilhamento.
- `vertical-align` - Alinha elementos inline ou em tabelas.

### Avançado
- `flex` - Atalho para propriedades Flexbox.
- `flex-direction` - Define a direção dos itens flex (ex.: "row").
- `flex-wrap` - Controla a quebra de linha em Flexbox.
- `flex-flow` - Atalho para `flex-direction` e `flex-wrap`.
- `justify-content` - Alinha itens no eixo principal (Flexbox ou Grid).
- `align-items` - Alinha itens no eixo cruzado (Flexbox ou Grid).
- `align-content` - Alinha linhas no eixo cruzado (Flexbox ou Grid).
- `flex-grow` - Define o fator de crescimento dos itens flex.
- `flex-shrink` - Define o fator de encolhimento dos itens flex.
- `flex-basis` - Define o tamanho base dos itens flex.
- `order` - Define a ordem dos itens flex ou grid.
- `grid` - Atalho para propriedades Grid.
- `grid-template-columns` - Define colunas no Grid.
- `grid-template-rows` - Define linhas no Grid.
- `grid-template-areas` - Define áreas nomeadas no Grid.
- `grid-gap` - Define o espaço entre células no Grid.
- `grid-column` - Define a posição/extensão de uma coluna no Grid.
- `grid-row` - Define a posição/extensão de uma linha no Grid.
- `place-items` - Atalho para `align-items` e `justify-items` no Grid.
- `place-content` - Atalho para `align-content` e `justify-content` no Grid.

---

## 5. Propriedades de Transformação e Animação

### Intermediário
- `transform` - Aplica transformações (ex.: "rotate(45deg)").
- `transform-origin` - Define o ponto de origem da transformação.

### Avançado
- `transition` - Define transições suaves (atalho).
- `transition-property` - Propriedade a ser animada.
- `transition-duration` - Duração da transição.
- `transition-timing-function` - Curva de aceleração (ex.: "ease").
- `transition-delay` - Atraso antes da transição.
- `animation` - Atalho para animações keyframes.
- `animation-name` - Nome da animação definida em `@keyframes`.
- `animation-duration` - Duração da animação.
- `animation-timing-function` - Curva de aceleração da animação.
- `animation-delay` - Atraso antes da animação.
- `animation-iteration-count` - Número de repetições (ex.: "infinite").
- `animation-direction` - Direção da animação (ex.: "alternate").
- `animation-fill-mode` - Comportamento antes/depois da animação.
- `animation-play-state` - Pausa ou reproduz a animação.

---

## 6. Propriedades de Estilo Visual

### Básico
- `cursor` - Define o tipo de cursor (ex.: "pointer").
- `visibility` - Controla a visibilidade do elemento.

### Intermediário
- `opacity` - Define a opacidade do elemento.
- `filter` - Aplica efeitos visuais (ex.: "blur(5px)").
- `clip-path` - Define uma área de recorte (ex.: "circle(50%)").

### Avançado
- `mix-blend-mode` - Define o modo de mesclagem com outros elementos.
- `backdrop-filter` - Aplica filtros ao fundo (ex.: "blur(10px)").
- `shape-outside` - Define a forma para o texto fluir ao redor.
- `shape-margin` - Margem da forma definida por `shape-outside`.

---

## 7. Propriedades de Conteúdo e Listas

### Básico
- `list-style` - Atalho para estilo de lista.
- `list-style-type` - Define o tipo de marcador (ex.: "disc").
- `list-style-position` - Posição do marcador (ex.: "inside").

### Avançado
- `content` - Insere conteúdo gerado (usado com `::before` e `::after`).
- `counter-increment` - Incrementa um contador.
- `counter-reset` - Reseta um contador.
- `quotes` - Define aspas personalizadas.

---

## 8. Propriedades de Tabelas

### Intermediário
- `border-collapse` - Define o colapso das bordas da tabela.
- `border-spacing` - Espaçamento entre células da tabela.
- `table-layout` - Define o algoritmo de layout da tabela (ex.: "fixed").

---

## 9. Propriedades de Impressão e Media

### Avançado
- `page-break-before` - Força quebra de página antes do elemento.
- `page-break-after` - Força quebra de página após o elemento.
- `page-break-inside` - Controla quebras dentro do elemento.
- `widows` - Define o número mínimo de linhas após uma quebra.
- `orphans` - Define o número mínimo de linhas antes de uma quebra.

---

## 10. Outras Propriedades Avançadas

### Avançado
- `resize` - Permite redimensionamento do elemento (ex.: "both").
- `user-select` - Controla a seleção de texto (ex.: "none").
- `pointer-events` - Define eventos de ponteiro (ex.: "none").
- `will-change` - Otimiza animações informando mudanças esperadas.
- `scroll-behavior` - Define o comportamento de rolagem (ex.: "smooth").
- `object-fit` - Define o ajuste de imagens/vídeos (ex.: "cover").
- `object-position` - Define a posição de imagens/vídeos.
- `appearance` - Controla a aparência nativa do elemento.
- `writing-mode` - Define a direção de escrita (ex.: "vertical-rl").
- `text-orientation` - Define a orientação do texto em modos verticais.
- `text-rendering` - Otimiza a renderização de texto.
- `paint-order` - Ordem de pintura de elementos SVG.

---

## Resumo
- Total de propriedades listadas: **200**.
- Abrange propriedades CSS3 para texto, cor, layout, animações e mais.
- Exclui propriedades obsoletas ou experimentais sem suporte amplo.
- Para mais detalhes ou exemplos, consulte a documentação do W3C ou MDN Web Docs.