1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- _¿Qué es un array?_

- _¿Qué es un objeto?_

- _¿Cuándo es mejor usar objetos o arrays?_

- _¿Puedo mezclar arrays con objetos o incluso objetos con arrays?_

2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.

```javascript
const showFirstElement = (array) => {
  console.log(array[0]);
};
```

3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).

```javascript
const showAllElements = (array) => {
  array.forEach((element) => {
    console.log(element);
  });
};
```

4️⃣ Crea una función que pueda recibir cualquier objeto como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el objeto completo).

```javascript
const showFirstElement = (object) => {
  const array = Object.values(object);
  array.forEach((element) => {
    console.log(element);
  });
};
```
