# Selectors

Conecta um elemento HTML com o CSS

## Tipos 

* Global selector `*`
* Element/Type selector `h1, h2, p, div`
* ID Selector `#box, #container`
* Calss Selector `.red, .m-4`
* Attribute selector, pseudo-class, pseudo-element, e outros


* No HTML:
<div id="container" class="m-40">
    <h1>Título</h1>
    <h2>Subtitulo</h2>
</div>

* No CSS:

//O '*' serve para identificar uma variavel global
* {
  margin: 0;
}

// "#container" refere-se somente ao atributo ID: container
#container {
  width: 200px; -> largura
}

// ".m-40" refe-se somente ao atriburo classe: m-40
.m-40{
  margin: 40px; -> margem
}

// "h1, h2" refere-se a todas os elementos h1 e h2
h1, h2 {
  color: green;
  font-size: 60px;
  background: orange;
}