# objetos_js

## El tipo de datos number en JavaScript se utiliza para representar valores numéricos, ya sean enteros o números de punto flotante (números decimales). Este tipo de datos se utiliza ampliamente en aplicaciones web para realizar cálculos matemáticos, manipulaciones de datos numéricos y muchas otras operaciones.


- Operaciones aritméticas: Puedes realizar operaciones aritméticas básicas como suma, resta, multiplicación y división.


var x = 10;
var y = 5;
var suma = x + y;
var resta = x - y;
var multiplicacion = x * y;
var division = x / y;

- Comparaciones: Puedes comparar números utilizando operadores de comparación como <, >, <=, >=, ===, !==.


var a = 10;
var b = 20;

if (a < b) {
    console.log("a es menor que b");
}

- Conversión de tipos: Puedes convertir números a otros tipos de datos, como cadenas de texto, utilizando métodos como toString() o toFixed().

var numero = 123;
var texto = numero.toString(); // convierte el número a una cadena de texto

- Generación de números aleatorios: Puedes generar números aleatorios utilizando la función Math.random().

var numeroAleatorio = Math.random(); // genera un número aleatorio entre 0 y 1

- 
document.getElementById es una función en JavaScript que se utiliza para obtener una referencia a un elemento HTML en una página web utilizando su atributo id. Cuando se llama a esta función, se proporciona el id del elemento que se desea obtener y la función devuelve una referencia a ese elemento si existe en el documento HTML.