# ai-example-2
Educational videogame created with just AI prompts.

This one is about an guessing the math formula plotted.

https://albertofemenias.github.io/ai-example-2/

## How to generate this videogame?
Ask the following to ChatGPT:

```
Crea un juego interactivo en un solo archivo HTML llamado 'Adivina la Fórmula'. El juego debe estar completamente en español y consistirá en un quiz donde el usuario debe identificar la ecuación matemática que corresponde a un gráfico mostrado.

Requisitos principales:

1.  Título y Lenguaje: El juego se llamará "Adivina la Fórmula" y toda la interfaz de usuario estará en español.
2.  Estructura del Juego:
    * Menú Principal: Permitir seleccionar familias de ecuaciones a incluir en el quiz (todas seleccionadas por defecto) y el número de preguntas (ej: 5, 10, 15). Botón "Empezar Juego".
    * Pantalla de Juego: Mostrar el número de pregunta actual y la puntuación. Un canvas HTML para dibujar el gráfico de la función misteriosa. A la derecha, una lista vertical de 5 botones con ecuaciones como opciones de respuesta múltiple. Un botón "Confirmar Respuesta" y luego "Siguiente Pregunta".
    * Pantalla Final: Mostrar el mensaje "¡Juego Terminado!", la puntuación final y un botón "Jugar de Nuevo".
3.  Familias de Ecuaciones y Fórmulas:
    * Incluir las siguientes familias: Lineal (`y=ax+b`), Cuadrática (`y=ax²+k`), Cúbica (`y=ax³+d`), Valor Absoluto (`y=a|x|+k`), Raíz Cuadrada (`y=a√x+k`), Exponencial (`y=abˣ+c`), Logarítmica (`y=a log_{base}(x)+k` o `y=a ln(x)+k`), y Trigonométrica (combinando Seno `y=asin(bx)+d` y Coseno `y=acos(bx)+d` en una sola familia).
    * Importante: Las fórmulas deben ser simplificadas, conteniendo como máximo un término constante que sume o reste (como se indica en los ejemplos).
4.  Graficación en Canvas:
    * El eje de coordenadas cartesianas debe ajustarse dinámicamente para cada pregunta, asegurando que el gráfico de la función misteriosa y todas las opciones se visualicen correctamente.
    * Proporción de Ejes: Los ejes X e Y deben mantener una proporción 1:1 en sus unidades (escalado "cuadrado"), es decir, un cambio de 1 unidad en X debe representar la misma distancia visual que 1 unidad en Y.
    * Incluir marcas de graduación (ticks) y etiquetas numéricas visibles y autoescaladas en los ejes. Las etiquetas del eje X deben aparecer justo debajo de la línea del eje.
    * La función misteriosa se dibujará en un color (ej: azul). Al confirmar, la función seleccionada por el usuario se dibujará en otro color (ej: rojo).
5.  Interfaz y Experiencia:
    * Diseño limpio, minimalista y funcional.
    * Feedback visual y textual (ej: "¡Correcto!", "Incorrecto. La respuesta correcta era: ..."). Colores distintivos para correcto/incorrecto.
    * Ecuaciones mostradas de forma legible (usar `<sup>`, `<sub>`, `√` según sea necesario).
6.  Archivo Único: Todo el código (HTML, CSS, JavaScript) debe estar contenido en un único archivo `.html` sin dependencias externas (excepto APIs estándar del navegador como Canvas y Math).
```
