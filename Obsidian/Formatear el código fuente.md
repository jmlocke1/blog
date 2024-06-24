Para insertar código fuente de un programa se usan las triples comillas invertidas ([acento grave francés](https://www.alianzafrancesamx.edu.mx/la-alianza/articulos-sobre-el-frances/2-los-acentos-en-frances))
````
```
cd ~/Desktop
```
````
Se puede añadir resaltado de código en bloque de código añadiendo el código de lenguaje después de el primer conjunto de comillas invertidas
````md
```js
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
````

```js
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
Obsidian usa Prism para el resaltado de código. Consulta [Lenguajes soportados](https://prismjs.com/#supported-languages)
