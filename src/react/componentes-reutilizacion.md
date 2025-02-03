# React
## Componentes
### Reutilización

Los componentes React funcionan como etiquetas HTML (`<img>`, `<button>`, etc.) que pueden ser reutilizadas a lo largo de una página web y recibir atributos para hacerlos configurables. 

<iframe height="300" style="width: 100%;" scrolling="no" title="Reutilización componentes" src="https://codepen.io/-lvaro-Ruiz-Calzada/embed/zxOXXxg?default-tab=js%2Cresult&editable=true&theme-id=light" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/-lvaro-Ruiz-Calzada/pen/zxOXXxg">
  Reutilización componentes</a> by Álvaro Ruiz Calzada (<a href="https://codepen.io/-lvaro-Ruiz-Calzada">@-lvaro-Ruiz-Calzada</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

Los atributos de los componentes en React se llaman "props". Opcionalmente, pueden tener valores por defecto: `function NombreComponente({prop1 = valor, prop2, ...})`.

> **❓ Ejercicio 2:** _Modifica el componente `Figura` anterior para que muestre "Sin título" si no se le pasa ningún `caption`._

> **❓ Ejercicio 3:** _Modifica el ejemplo anterior para que, cuando no se pase `url`, se devuelva `<h1>⚠️</h1>` en vez de `<img...>`, utilizando el [operador condicional](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator) de JS._