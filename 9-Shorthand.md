# Shorthand

* junção de propriedades
* resumivel
* legível

```css
{
    /* background properties */
    background-color: #000;
    background-image: url(images/bg.gif);
    background-repeat: no-repeat;
    background-position: left top;

    /* background shorthand */
    background: #000 url(images/bg.gif) no-repeat left top;

    /* font properties */
    font-style: italic;
    font-weight: bold;
    font-size: .8em;
    line-height: 1.2;font-family: Arial, sans-serif;

    /* font shorthand */
    font: italic bold .8em/1.2 Arial, sans-serif;
}
```

## Detalhes

* Não ira considerar propriedades anteriores (cascading)
* Valores não especificados irão assumir o valor padrão
* Geralmente a ordem escrita não importa, mas, se houver muitas propriedades com valores semelhantes, poderemos encontrar problemas

## Propriedades que aceitam Shorthand

animation, background, border, border-bottom, border-color, border-left,
border-radius, border-rightm border-style, border-top, boder-width,
column-rule, columns, flex, flex-flow, font, grid, grid-area, grid-column,
grid-low, grid-template, list-style, margim, offset, outline, overflow, padding,
place-content, place-item, place-self, text-decoration, transition

**https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties**