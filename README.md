# Conecta el circuito ⚡

Mini juego de navegador construido **entero con [Dual LLM](https://www.dual-llm.com)**: un equipo de IAs (Asesor → Code → Revisor) que se pasan el trabajo sin copiar y pegar.

## La idea

Eres un electricista. En cada nivel hay una **pila**, una **bombilla** y piezas de cable en una cuadrícula. Gira las piezas (clic) hasta que la corriente llegue de la pila a la bombilla y se encienda.

## Requisitos

- Un solo archivo `index.html` (HTML + CSS + JS, sin librerías), que funcione abriéndolo en el navegador y en el móvil.
- Cuadrícula de 5×5 a 7×7. Piezas: recta, curva, T y cruz. Clic o toque = girar 90°.
- Detección de circuito cerrado (recorrido desde la pila); la bombilla se enciende con una animación.
- 5 niveles de dificultad creciente, contador de movimientos y botón "Reiniciar".
- Estética limpia, modo oscuro, accesible con teclado.

## Estado

Repositorio de prueba: el código lo escriben las IAs desde Dual LLM.
