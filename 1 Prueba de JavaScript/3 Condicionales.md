# Condicionales.

## 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- _¿Qué es un condicional?_

  Un condicional es una caracteristica que nos permite verificar si una expresion es verdadera o falsa (true or false);

- _¿Qué tipos de condicionales existen en JavaScript y cuáles son sus diferencias?_

- _¿Puedo combinar funciones y condicionales?_

## 2️⃣ Replica el comportamiento del siguiente código que usa la sentencia switch utilizando if, else y else if:

```Javascript
const tipoDeSuscripcion = "Basic";

switch (tipoDeSuscripcion) {
   case "Free":
       console.log("Solo puedes tomar los cursos gratis");
       break;
   case "Basic":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");
       break;
   case "Expert":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un año");
       break;
   case "ExpertPlus":
       console.log("Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año");
       break;
}
```

```javascript
const subscriptionType = "Basic";

if (subscriptionType === "Free") {
  console.log("Solo puedes tomar los cursos gratis");
} else if (subscriptionType === "Basic") {
  console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");
} else if (subscriptionType === "Expert") {
  console.log("Puedes tomar casi todos los cursos de Platzi durante un año");
} else if (subscriptionType === "ExpertPlus") {
  console.log(
    "Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año"
  );
} else {
  console.log("Esta subscripcion no existe!");
}
```

### 3️⃣ Replica el comportamiento de tu condicional anterior con if, else y else if, pero ahora solo con if (sin else ni else if).

```javascript
const subscriptionType = "Basic";

if (subscriptionType === "Free") {
  console.log("Solo puedes tomar los cursos gratis");
}
if (subscriptionType === "Basic") {
  console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");
}
if (subscriptionType === "Expert") {
  console.log("Puedes tomar casi todos los cursos de Platzi durante un año");
}
if (subscriptionType === "ExpertPlus") {
  console.log(
    "Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año"
  );
}
```

💡 Bonus: si ya eres una experta o experto en el lenguaje, te desafío a comentar cómo replicar este comportamiento con arrays u objetos y un solo condicional. 😏

```javascript
const userSub = "Free";
const subsInfo = {
  Free: "Solo puedes tomar los cursos gratis",
  Basic: "Puedes tomar casi todos los cursos de Platzi durante un mes",
  Expert: "Puedes tomar casi todos los cursos de Platzi durante un año",
  ExpertPlus:
    "Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año",
};

function verifySubscription(subType) {
  Object.keys(subsInfo).forEach((sub) => {
    if (subType === sub) {
      console.log(subsInfo[sub]);
    }
  });
}

verifySubscription(userSub);
```
