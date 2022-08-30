# Ciclos

## 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- _¿Qué es un ciclo?_

Un ciclo es un bloque de codigo que se ejecutara siempre y cuando una condicion sea verdadera.

- _¿Qué tipos de ciclos existen en JavaScript?_

while, doWhile, for, forEach.

- _¿Qué es un ciclo infinito y por qué es un problema?_

Un Ciclo infinito es un ciclo que no sale de su condicional para iterar, y se ejecuta infinitamente. Esto es un  
problema porque al no detenerse consume recursos y puede hacer que nuestro codigo se rompa y causar que el
navegador o el pc del usuario se congele.

- _¿Puedo mezclar ciclos y condicionales?_

Si, es posibe anidar condicionales dentro de ciclos y ciclos dentro dentro de condicionales.

## 2️⃣ Replica el comportamiento de los siguientes ciclos for utilizando ciclos while:

```javascript
for (let i = 0; i < 5; i++) {
  console.log("El valor de i es: " + i);
}

for (let i = 10; i >= 2; i--) {
  console.log("El valor de i es: " + i);
}
```

_Respuesta_

```javascript
let i = 0;
let e = 10;

while (i < 5) {
  console.log("El valor de i es: " + i);
  i++;
}

while (e >= 2) {
  console.log("El valor de e es: " + e);
  e--;
}
```

## 3️⃣ Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.

💡 Pista: puedes usar la función prompt de JavaScript.

```javascript
const a = 2;
const b = 2;
const rightAnswer = a + b;
let userAnswer;

while (userAnswer !== rightAnswer) {
  alert(`Cuanto es ${a} + ${b} ?`);
  userAnswer = parseInt(prompt("Respuesta:"));
  console.log(userAnswer);
  if (userAnswer === rightAnswer) {
    alert("Bien hecho, tu respuesta es correcta");
  } else {
    alert("Respuesta incorrecta, volveremos a empezar...");
  }
}
```
