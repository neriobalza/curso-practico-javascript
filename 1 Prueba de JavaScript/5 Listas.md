# Listas

## 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- _¿Qué es un array?_

Un Array es una lista de elementos.

- _¿Qué es un objeto?_

Un objecto es una lista de elementos donde cada elemento tiene un un nombre que lo identifica.

- _¿Cuándo es mejor usar objetos o arrays?_

Arrays cuando lo que haremos en un elemento es lo mismo que en todos los demás (la regla se puede incumplir).
Mientras que un objeto cuando los nombres de cada elemento son importantes para nuestro algoritmo.

- _¿Puedo mezclar arrays con objetos o incluso objetos con arrays?_

Sí. Los arrays pueden guardar objetos. Y los objetos pueden guardar arrays entre sus propiedades.

## 2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.

```javascript
const showFirstElement = (array) => {
  console.log(array[0]);
};
```

## 3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).

```javascript
const showAllElements = (array) => {
  array.forEach((element) => {
    console.log(element);
  });
};
```

## 4️⃣ Crea una función que pueda recibir cualquier objeto como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el objeto completo).

```javascript
const showFirstElement = (object) => {
  const array = Object.values(object);
  array.forEach((element) => {
    console.log(element);
  });
};
```
