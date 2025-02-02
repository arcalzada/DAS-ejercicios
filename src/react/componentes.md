# React
## Componentes

Son pequeñas piezas interactivas que conforman la interfaz de usuario. Se implementan como **funciones** que devuelven código **JSX** representando su aspecto visual. Dentro del código JSX se puede incluir JS entre llaves (`{...}`).

<iframe height="400" width="100%" scrolling="no" title="React Component" src="https://codepen.io/-lvaro-Ruiz-Calzada/pen/zxOXLEy" frameborder="no" loading="lazy"></iframe>

> 🔍 **Nota:** _[JSX](https://en.wikipedia.org/wiki/JSX_(JavaScript)) es un lenguaje muy similar a [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) pero este último no se puede mezclar con JS. Este sería el código HTML + JS (DOM) equivalente:_
> <details><summary>Pulsa para mostrar...</summary>
> <div class="sandpack" data-template="vanilla" data-width="55" data-height="200px"><pre data-file="index.js">
> const nombre = 'React';
> const h1 = document.createElement('h1');
> h1.textContent = 
>   `¡Hola ${nombre.toUpperCase()}!`;
> document.getElementById('root').appendChild(h1);
> </pre><pre data-file="index.html">
> &lt;!DOCTYPE html>
> &lt;html>
> &lt;body>
>   &lt;div id="root">&lt;/div>
>   &lt;script src="index.js">&lt;/script>
> &lt;/body>
> &lt;/html>
> </pre></div></details><br/>

> **❓ Ejercicio 1:** _Modifica el ejemplo anterior para que el componente React también muestre la [imagen](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img) de esta URL: `https://picsum.photos/200`. Si tienes dificultades puedes usar este conversor [HTML➜JSX](https://transform.tools/html-to-jsx)._

