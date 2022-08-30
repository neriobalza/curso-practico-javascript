# Variables.

## 1️⃣ Responde las siguientes preguntas:

- _¿Qué es una variable y para qué sirve?_

Una variable es un espacio reservado en memoria en el que podemos almacenar informacion.
Dentro de una variable podemos guardar valores primitivos como strings, numbers, booleans, undefinend, entre otros y valores complejos como objects o arrays.

- _¿Cuál es la diferencia entre declarar e inicializar una variable?_

Al declarar una variable estamos declarando que un espacio especifico en la memoria va a albergar
un valor que puede ser asignado durante su declaracion o mas adelante durante la ejecucion del codigo.

Ejemplo: var name; const lastName; let age;

Al inicializar una variable declaramos cual va a ser su valor inicial.

Ejemplo: var name = "Pedro"; const lastName = "Perez"; let age = 21;

- _¿Cuál es la diferencia entre sumar números y concatenar strings?_

Al momento sumar números estamos realizando una operación matemática con dos tipos de datos (Numbers)
mientras que al concatenar estamos sumando dos tipos de datos (String) que son cadena de textos.

- _¿Cuál operador me permite sumar o concatenar?_

El signo de mas "+";

## 2️⃣ Determina el nombre y tipo de dato para almacenar en variables la siguiente información:

- Nombre = string name
- Apellido = string lastNane
- Nombre de usuario en Platzi = string userName
- Edad = number age
- Correo electrónic0 = string email
- Mayor de edad = boolean isAdult
- Dinero ahorrado = number savedMoney
- Deudas = number debtAmount

## 3️⃣ Traduce a código JavaScript las variables del ejemplo anterior:

```javascript
let name = "Homero";
let lastName = "Simpson";
let userName = "HomeroJSimpson";
let age = 39;
let email = "homerojs@hotmail.com";
let isAdult = age >= 18 ? true : false;
let savedMoney = 2500;
let debtAmount = 1253000;
```

## 4️⃣ Calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:

- Nombre completo (nombre y apellido)

```javascript
function logFullName(name, lastName) {
  console.log("Your full name is: " + name + " " + lastName);
}

logFullName(name, lastName);
```

- Dinero real (dinero ahorrado menos deudas)

```javascript
function logRealMoney(saved = 0, debt = 0){
  const realMoney = saved - debt;
  console.log("Your money after debts is: $" realMoney);
  if(realmoney < 0) console.log("You are broke");
}

logRealMoney(savedMoney, debtAmound);
```
