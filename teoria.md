1. ¿Que diferencia una variable creada con `let` de una creada con `const`?
2. ¿Qué diferencia hay entre `==` y `===`?
3. Analiza el siguiente código, ¿qué valor se mostrará en la consola?
```js
let a = 1;

function mi_funcion() {
    let a = 2;
}

mi_funcion();
console.log(a);
```
4. ¿Qué es el DOM? Explícalo brevemente.
5. ¿Este código es correcto? Si no lo es, ¿por qué?
```js
const boton = document.querySelector('button');
function saluda() {
    console.log('Hola');
}
boton.addEventListener('click', saluda());
```