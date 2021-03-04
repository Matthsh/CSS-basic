# At-rules (@rules)

* Está relacionado ao comportamento do Calss
* começa com o sinal de `@` seguido do identificador e valor

## Exemplos comuns

- @import       /* incluir um CSS externo */
- @media        /* regras condicionais para dispositivos */
- @font-face    /* fontes externas */
- @keyframes    /* Animation */

```css
@import "http://local.com/style.css"; /* @import url("http://remote.com/style.css"); */

@media (min-width: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameOfAnimation {
    /* rules here */
}
```
