# Programación 1 - Parcial 1

El parcial va a durar 2 horas, y va a ser un exámen práctico en computadora. Se podrá tener cualquier material impreso, y se podrá acceder via internet únicamente a los siguientes materiales trabajados en clase:

- [https://github.com/matismasters/prog1_js_basico](https://github.com/matismasters/prog1_js_basico)
- [https://github.com/matismasters/prog1_html](https://github.com/matismasters/prog1_html)
- [https://github.com/matismasters/prog1_oop](https://github.com/matismasters/prog1_oop)
- [https://github.com/matismasters/prog1_cheatsheets](https://github.com/matismasters/prog1_cheatsheets)
- [https://github.com/matismasters/prog1_swapscore](https://github.com/matismasters/prog1_swapscore)

No se permite el uso de teléfonos móviles durante el parcial.

Al terminar se debe subir el examen a un repositorio de github y enviar el link al profesor por mail. Antes de retirarse el alumno debe asegurarse que el profesor recibe el mail y que el examen se subió correctamente.

## Datos del alumno

Nombre:

## Introducción

Un grupo inversor ha decidido fundar una empresa de producción de robots en Uruguay. Los siguientes ejercicios comprenden funciones importantes del proceso de evaluación de viabilidad del uso del complejo industrial Sudamtex de Colonia del Sacramento para la instalación de su primera planta de producción.

Los robots que se producirán son robots industriales, a continuación se detallan las características de algunos de ellos:

- **Robot Soldador**: Robot de soldadura, se moviliza a una velocidad maxima de 5 km/h, tiene una autonomía de 8 horas y puede realizar 1000 operaciones por hora.
- **Robot Triturador**: Robot de trituración, se moviliza a una velocidad maxima de 2 km/h, tiene una autonomía de 12 horas y puede realizar 500 operaciones por hora.
- **Robot Transportador**: Robot de transporte de carga, se moviliza a una velocidad maxima de 3 km/h, tiene una autonomía de 10 horas y puede realizar 10 operaciones por hora.

## Ejercicio 1

Crea una función que recibe un array, `medidasGalpones` con objetos con el siguiente formato:

```javascript
{ largo: 50, ancho: 100 }
```

Las medidas corresponden a diferentes galpones de un complejo industrial y estan en metros.

**La función debe calcular el área de cada galpón y devolver la suma de todas las áreas.**

```javascript
// Solucion

```

## Ejercicio 2

Crea una función que recibe dos parametros, un número, `superficieEdificio` y un array `maquinas` de objetos con el siguiente formato:

```javascript
{ nombreMaquina: "Torno Industrial", superficieDeOperacionRequerida: 40 }
```

El array contiene diferentes maquinas de una fábrica y sus superficies de operación requeridas en metros cuadrados.
El número `superficieEdificio` representa la superficie de uno de los edificios del complejo industrial en metros cuadrados.

**La función debe devolver true si al menos una de las máquinas puede ser instalada en el edificio, y false en caso contrario.**

```javascript
// Solucion

```

## Ejercicio 3

Crea una función llamada `filtrarInversoresVIP` que recibe un array `inversores` con objetos con el siguiente formato:

```javascript
{ nombre: "Lopez Mena", capital: 9000000 }
```

Los objetos representan inversores del proyecto y cuanto capital están dispuestos a aportar.

**La función debe devolver un array solo con aquellos inversores que aportan más de 1 millon de dólares.**

```javascript
// Solucion

```

## Ejercicio 4

Crea una función que recibe un array de objetos con el siguiente formato:

```javascript
{ nombre: "Robot Triturador", cantidad: 5 }
```

Los objetos representan la cantidad de robots de cada tipo que ya se han encargado a construir.

**La función debe devolver un objeto `<li>` por cada objeto del array con el siguiente formato:**

```html
<li class="item-encargado">Robot Triturador: 5</li>
```

```javascript
// Solucion

```

## Ejercicio 5

**Crea una clase `Robot` con al menos 3 propiedades, 2 métodos de instancia y 3 métodos estáticos.**
Al menos uno de los métodos de instancia debe llamar al otro.
Cada uno de los métodos estáticos debe devlover una instancia de la clase. Estas instancias deben tener ya cargadas propiedades acordes a los tipos de robots mencionados al principio del documento.

```javascript
// Solucion

```
