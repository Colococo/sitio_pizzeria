# Modelos Mentales

Lee el codigo siguiente:

```
let a = 10;

let b = a;

a = 0;
```

Cuales son los valores de **a** y **b** después que se ejecuto el codigo? Piensalo antes de seguir leyendo.

Si has estado escribiendo JavaScript por un tiempo, podrias decir: “Este snippet de codigo es mucho mas simple que el codigo que escribo todos los dias”. Cual es el punto….

El objetivo de este ejercicio no es una introducción a las variables en JavaScript. Estoy asumiendo que es algo familiar para ti. En lugar, es para hacer que observes y reflexiones en tu modelo mental.

## Que es un Modelo Mental

Lee el código nuevamente con la intención de estar realmente seguro cual es el resultado. (Veremos luego porque esta intención es importante.)

Mientras lees por segunda vez, presta atención a lo que está sucediendo en tu cabeza, paso a paso. Podrias quizas escuchar un monólogo como este:

```
· let a = 10;
```

- Declarar una variable que se llama **a**. Asignar el valor 10.

```
· let b = a;
```

- Declarar una variable que se llama **b**. Asignar el valor de **a**.

- Espera, que es **a** ? ah, era 10. Entonces **b** es 10 también.

```
· a = 0;
```

- Poner la variable **a** en **0**.

- Entonces **a** es **0** ahora y **b** es **10**. Esta es nuestra respuesta.

Quizás tu monólogo es un poco diferente. Quizás tu dices poner en lugar de asignar, o quizás lees en orden un poco diferente. Quizás has arribado a un resultado diferente. Presta con mucha atención como es diferente. También puedes observar que este monólogo no captura lo que realmente está sucediendo en tu cabeza. Podríamos decir **“colocar b en a”**, pero qué significa realmente colocar una variable.

Podrías encontrar que por cada concepto básico de programación (como una variable) y sus operaciones (como asignar un valor), hay un conjunto de analogías profundamente arraigadas que tú asocias con ello. Algunas pueden venir del mundo real, otras pueden ser reutilizadas de otros campos que ya has aprendido, como números en matemáticas.

Estas analogías pueden sobreponerse y aun contradecir una con la otra, pero todavía te ayudan a hacer que tenga sentido lo que está pasando con el código.

Por ejemplo, mucha gente primero aprende acerca de variables como “cajas”- contenedores que contienen tus cosas. Aun si no puedes imaginar las cajas cuando observas una variable, podrían todavía comportarse como una caja en tu imaginación.

Estas aproximaciones de cómo algo funciona en tu cabeza son conocidos como modelos mentales. Podría ser difícil si tu has programado por mucho tiempo, pero trata de observar y analizar tus modelos mentales. Son probablemente una combinación de algo visual, especial y atajos mentales mecánicos. Estas intuiciones (como “cajas” en las variables) influencian mucho como leemos el código en toda nuestra vida.

Desafortunadamente, a veces nuestros modelos mentales están equivocados. Tal vez un tutorial que leímos anteriormente sacrificó la precisión para hacer que un concepto sea más fácil de explicar. Quizás cuando iniciamos a aprender JavaScript, incorrectamente “treamos” un comportamiento esperado de otro lenguaje que hemos aprendido anteriormente. Tal vez inferimos un modelo mental a partir de algún código, pero nunca verificamos que fuera exacto.

Identificando y corrigiendo estos problemas es “Solo JavaScript”. Vamos a construir gradualmente (o quizás reconstruir) tu modelo mental de JavaScript para que sea preciso y útil. Un buen modelo mental te dará seguridad en tu código, y te dará la oportunidad de aprender (y corregir) código que otra persona haya escrito.

Por cierto, **a** es **0** y **b** es **10** es la respuesta correcta. 😊
