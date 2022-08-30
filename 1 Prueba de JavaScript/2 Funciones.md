# Funciones:

## 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- _¿Qué es una función?_

Es la manera como encapsulamos bloques de codigo para que sean reautilizables en el futuro.

- _¿Cuándo me sirve usar una función en mi código?_

Cuando tenemos un bloque de codigo que se repite varias veces en nuestro programa.

- _¿Cuál es la diferencia entre parámetros y argumentos de una función?_

Los parametros son los valores que puede recibir una funcion, mientras que los argumentos son los
valores exactos que le pasamos a una funcion cuando la ejecutamos.

## 2️⃣ Convierte el siguiente código en una función, pero, cambiando cuando sea necesario las variables constantes por parámetros y argumentos en una función:

// const name = "Juan David";
// const lastname = "Castro Gallego";
// const completeName = name + lastname;
// const nickname = "juandc";
// console.log("Mi nombre es " + completeName + ", pero prefiero que me digas " + nickname + ".");

```javascript
function introduceYourself(name, lastName, nickname) {
  const fullName = name + " " + lastName;
  console.log(
    "Mi nombre es: " +
      fullName +
      ", pero prefiero que me digas: " +
      nickname +
      "."
  );
}

introduceYourseft("Bartholomew JoJo", "Simpson", "Bart");
```
