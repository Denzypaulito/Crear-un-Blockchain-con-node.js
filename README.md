# Práctica | Crear un Blockchain con Node.js

## Descripción
Este es un proyecto en el que se utiliza Node.js y JavaScript para crear un blockchain. El proyecto incluye dos clases, Block y Blockchain. La clase Block representa un bloque individual en la cadena, mientras que la clase Blockchain es responsable de manipular y agregar bloques a la cadena.

## Instrucciones
Para utilizar este proyecto, sigue los siguientes pasos:

1. Descarga todas las dependencias y archivos necesarios.

2. Abre una terminal en la raíz del repositorio clonado.

3. Asegúrate de tener Node.js y las dependencias del proyecto instaladas.

4. Abre el archivo main.js y modifica la siguiente línea:
```js
const blockchain = new Blockchain('Hello World');
```
5. Reemplaza 'Hello World' con la cadena de caracteres que deseas que sea el contenido del primer bloque en la cadena.

6. Ejecuta el siguiente comando en la terminal para ejecutar el script:
```js
node main.js
```
El programa agregará automáticamente bloques a la cadena de bloques con datos de ejemplo. Puedes modificar el número de bloques que se agregan modificando la variable i en el archivo main.js.

## Lenguaje de programación
JavaScript (Node.js v18.13.0).

## Autor
**Denzel Alexander Muñoz Santana**

Usuario: Denzypaulito

Matrícula: 348802

[Github](https://github.com/Denzypaulito) 

## Funcionamiento

La clase Block tiene tres atributos: index, data y previousHash. El atributo index es un identificador para la posición del bloque en la cadena, data contiene el contenido del bloque y previousHash es el valor hash del bloque anterior en la cadena.

La clase Blockchain se inicializa con un primer bloque y una dificultad. La dificultad es el número de ceros que deben preceder al hash para que se considere válido. La clase cuenta con métodos para crear el primer bloque, obtener el último bloque y agregar un bloque a la cadena.

El programa también incluye un método mine que calcula el nuevo hash del bloque según su dificultad. Este método es el encargado de "minar" nuevos bloques y agregarlos a la cadena.
