# SRS — ECOFIE

## 1. Introducción
**Propósito:** definir los requerimientos de ECOFIE, videojuego educativo sobre el cuidado ambiental.

**Alcance:** presentar problemas ambientales, permitir elegir soluciones, explicar consecuencias y mostrar una puntuación final.

## 2. Descripción general
**Usuarios:** jugadores interesados en aprender sobre el medio ambiente.  
**Funciones:** iniciar partida, leer situaciones, elegir opciones, conocer consecuencias, acumular puntos y consultar resultados.  
**Suposición:** el juego se ejecutará en una plataforma que permita mostrar textos y seleccionar botones.

## 3. Requerimientos funcionales

| ID | Descripción | Prioridad | Criterio de aceptación |
|---|---|---|---|
| RF-01 | Iniciar una partida desde el menú. | Alta | Al pulsar “Jugar” aparece la primera situación. |
| RF-02 | Mostrar situaciones ambientales. | Alta | Cada situación presenta un problema comprensible. |
| RF-03 | Mostrar al menos dos opciones por situación. | Alta | Las alternativas aparecen claramente identificadas. |
| RF-04 | Permitir seleccionar una opción. | Alta | La selección queda registrada una sola vez. |
| RF-05 | Mostrar las consecuencias de la decisión. | Alta | Se presenta una explicación relacionada con la opción elegida. |
| RF-06 | Actualizar la puntuación. | Media | Los puntos cambian según el valor asignado a la decisión. |
| RF-07 | Permitir avanzar a la siguiente situación. | Media | Se carga otra situación o el resumen final. |
| RF-08 | Mostrar los resultados de la partida. | Media | Se muestra la puntuación y un resumen de respuestas. |

## 4. Requerimientos no funcionales

| ID | Descripción | Prioridad | Criterio de aceptación |
|---|---|---|---|
| RNF-01 | Interfaz sencilla e intuitiva. | Alta | Los controles se identifican fácilmente en una prueba de uso. |
| RNF-02 | Lenguaje claro y adecuado para estudiantes. | Alta | Las instrucciones se comprenden sin explicación adicional. |
| RNF-03 | Respuesta oportuna a las selecciones. | Alta | La consecuencia aparece sin retrasos perceptibles. |
| RNF-04 | Diseño visual con temática ambiental. | Media | Colores e ilustraciones mantienen relación con la naturaleza. |
| RNF-05 | Información educativa revisada. | Media | Los mensajes se verifican antes de incluirse en el juego. |

## 5. Reglas del sistema
1. Cada situación contiene dos o más alternativas.
2. Cada alternativa tiene una consecuencia definida.
3. La puntuación se actualiza una sola vez por situación.
4. El jugador puede avanzar después de conocer la consecuencia.
5. Al terminar, se muestra un resumen.

## 6. Escenario principal
El jugador inicia la partida, lee una situación ambiental, revisa las opciones y selecciona una. El sistema explica el efecto de esa decisión, actualiza los puntos y permite continuar. Al terminar las situaciones, muestra el resultado final.

## 7. Validación
La primera versión se considerará funcional cuando permita iniciar, mostrar situaciones, registrar decisiones, presentar consecuencias, actualizar puntos y consultar resultados.
