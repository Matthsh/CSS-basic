# A cascata (Cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras,
para o mesmo elemento.

* seu estilo é lido de cima para baixo.

É leva em consideração três fatores.

1.Origem do estilo
2.Especificidade
3.Importancia

### Origem do estilo

 * inline > tag style > tag link

<style>
  h1{ color: gray }
  h1{ color: black}
</style>
<h1 style="color: green"> Título </h1>
<p>paragrafo</p>

```CSS
h1 {color: red;}
h1 {color: blue;}
```

### Especificidade

 * É um calculo matemático, onde, cada tipo de seletor e origem de estilo, possuem valores a serem considerados.

0. Universal selector, combinator e negation pseudo-class (:not()) -> relevancia = 0
1. Element type selector e pseudo-elements (::before, ::after) -> relevancia = 1
10. Classes e attribute selectors ([type="radio"]) -> relevancia = 10
100. ID selector -> relevancia = 100
1000. Inline -> relevancia = 1000

### A regra !important

* cuidado, evite o uso
* não é considerado uma boa prática
* quebra o fuxo natural de cascata
```css
h1 {color: red !important;}