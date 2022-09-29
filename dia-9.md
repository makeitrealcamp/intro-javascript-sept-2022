# Ejercicios día 9

Recuerda que puedes hacer preguntas en el [Foro de Make It Real](https://foro.makeitreal.camp/c/intro-javascript-sept-2022/).

## Ejercicio 46

Crea una función flecha y asígnala a una variable llamada `hola`. La función debe recibir un argumento `name` (con valor por defecto "Pedro") y debe retornar la frase "Hola " seguido del nombre y un signo de exclamación.

**Nota:** Utiliza *plantillas de strings* para la creación de la frase.

```javascript
// escribe acá tu función flecha

// código de prueba
console.log(hola()) // "Hola Pedro!"
console.log(hola("Maria")) // "Hola Maria!"
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-46-js-septiembre-2022/6442). No incluyas el código de prueba.

## Ejercicio 47

Utiliza destructuración para almacenar los primeros dos elementos del siguiente arreglo en las variables `first` y `second`:

```javascript
const arr = [1, 2, 3, 4]

// escribe acá tu respuesta

// código de prueba
console.log(first) // 1
console.log(second) // 2
```

Utiliza ahora destructuración para obtener el valor de las llaves `name` y `age` del objeto:

```javascript
const person = {
  name: "Pedro",
  age: 20
}

// escribe tu respuesta acá

// código de prueba
console.log(name) // "Pedro"
console.log(age)
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-47-js-septiembre-2022/6443). No incluyas el código de prueba.

## Ejercicio 48

Crea un objeto literal en una variable llamada `auto` que tenga un atributo `velocidad` (con valor inicial 0) y dos métodos `acelerar` y `frenar`. Los métodos `acelerar` y `frenar` deben incrementar y decrementar la propiedad `velocidad` en 1.

**Nota:** Utiliza métodos concisos

```javascript
// escribe tu solución acá

// código de prueba
console.log(auto.velocidad) // 0
auto.acelerar()
console.log(auto.velocidad) // 1
auto.frenar()
console.log(auto.velocidad) // 0
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-48-js-septiembre-2022/6444). No incluyas el código de prueba.

## Ejercicio 49

Crea una función flecha y asígnala a una variable `obtenerImpares`. La función debe recibir un arreglo de números y retornar todos los impares.

**Nota:** Utiliza el método `filter` y pásale una función flecha como argumento.

```javascript
// escribe tu solución acá

// código de prueba
console.log(obtenerImpares([1, 2, 3, 4, 5])) // [1, 3, 5]
console.log(obtenerImpares([64, 35, 27])) // [35, 27]
console.log(obtenerImpares([])) // []
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-49-js-septiembre-2022/6445). No incluyas el código de prueba.

## Ejercicio 50

Crea una función llamada `max` (puede ser normal o función flecha) que reciba un arreglo de números como argumento y retorne el número mayor.

**Nota:** No utilices el método `Math.max` de JavaScript.

```javascript
// escribe tu solución acá

// código de prueba
console.log(max([1, 2, 3, 4])) // 4
console.log(max([63, 85, 39, 24, 3])) // 85
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-50-js-septiembre-2022/6446). No incluyas el código de prueba.

### Ejercicio 51 (Bonus)

Modifica el ejercicio anterior para que la función `max` no reciba un arreglo sino un número indeterminado de argumentos.

```javascript
// escribe tu solución acá

// código de prueba
console.log(max(1, 2, 3, 4)) // 4
console.log(max(63, 85, 39, 24, 3)) // 85
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-51-js-septiembre-2022/6447). No incluyas el código de prueba.