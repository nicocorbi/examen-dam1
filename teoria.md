# Teoria

Realiza el examen directamente sobre el archivo!

Este examen solo muestra algunos conceptos al azar que me parecen importantes, hay muchos!

Intenta añadir código cuando lo necesites utilizando

```lenguaje
codigo
```

1. ¿Que diferencia una variable creada con `let` de una creada con `const`?
let es una variable que puede ser cambiada por ejemplo: let = 0,luego puedes cambiar ese 0 a 1 por ejemplo
const es una variable que no se puede cambiar 
2. ¿Qué es un dato primitivo? ¿y un objeto?
un string por ejemplo
2. ¿Qué diferencia hay entre `==` y `===`? 
3. Analiza el siguiente código, ¿qué valor se mostrará en la consola? 1 ya que cuando llamas al a estamos llamando al que hay fuera de la funcion
```js
let a = 1;

function mi_funcion() {
    let a = 2;
}

mi_funcion();
console.log(a);
```
4. ¿Qué es el DOM? Explícalo brevemente.
el dom es una interfaz que sirve para estructurar un documento de HTML como un arbol de nodos
5. ¿Este código es correcto? Si no lo es, ¿por qué? Depende,en el caso de que queramos que al darle click ejecute el saluda una vez entonces sera correcto, si queremos que el hola se ejecute cada vez que demos click entonces no, ya que al poner parentesis en el saluda le estamos diciendo que lo ejecute una sola vez.
```js
const boton = document.querySelector('button');
function saluda() {
    console.log('Hola');
}
boton.addEventListener('click', saluda());
```
6. ¿Que formas de seleccionar elementos del DOM conoces? ¿Cuál es la diferencia entre ellas?
getElementById,querySelector,appendChild,createElement
7. ¿Qué es un evento? ¿Qué formas conoces de crearlos? 
un evento es una llamada para decirle al script que cuando le demos a algo o pulsemos ocurra otra cosa , tenemos el addEventListenerpor ejemplo
8. ¿Como se añade una libreria externa a un proyecto de JavaScript? Puedes usar p5 como referencia.
9. ¿Que es esto? `<meta charset="UTF-8">` ¿Por qué es importante?
10. ¿Que es una función? Explica brevemente su sintaxis en el lenguaje que prefieras.
una funcion 
una funcion es palabra que almacena una parte del codigo y sirve para despues hacer llamadas en otrasw partes del codigo por ejemplo:
function mostrar(){
      p.innerText = input.value
    }
    input.addEventListener('input', mostrar)
