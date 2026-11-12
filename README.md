# Proyectos integradores de fin de bimestre

**Asignaturas:** Fundamentos Computacionales e Introducción a la Programación  
**Modalidad:** Grupos de tres estudiantes  
**Duración:** 10 días  
**Producto final:** Miniespecificación, algoritmo y aplicación de consola en Java.

## Objetivo

Desarrollar una solución computacional a una problemática cotidiana o social mediante el análisis, la elaboración de miniespecificaciones y algoritmos, y su posterior implementación en Java.

Cada grupo seleccionará **un proyecto en Fundamentos Computacionales** y resolverá el mismo problema en las dos asignaturas:

- **Fundamentos Computacionales:** análisis, miniespecificación, algoritmo y pruebas de escritorio.
- **Introducción a la Programación:** implementación en Java, ejecución y verificación de resultados.

## Alcance y restricciones

Las soluciones deben utilizar los contenidos estudiados durante el primer bimestre: variables, tipos de datos, operadores, entrada y salida, condicionales simples, compuestos y anidados, y ciclos `while`. Pueden emplearse contadores, acumuladores, promedios, porcentajes y validaciones.

**No se requiere ni se permite utilizar arreglos, colecciones, funciones o métodos propios, ciclos `for` o `do-while`, búsqueda de máximos o mínimos ni programación orientada a objetos adicional.** En Java, la solución se implementará dentro de `main`.

---

## Proyecto 1. Control y análisis del tiempo de uso de dispositivos móviles

### Problemática

El uso prolongado de teléfonos celulares es una situación frecuente entre estudiantes universitarios. Aunque estos dispositivos facilitan la comunicación, el aprendizaje y el acceso a información, su utilización excesiva puede interferir con las actividades académicas, el descanso y la organización del tiempo.

Muchos estudiantes desconocen cuántas horas dedican diariamente al teléfono celular y qué proporción de ese tiempo destinan a actividades académicas o recreativas. Se propone desarrollar una herramienta que permita analizar estos hábitos y contribuya a una utilización más consciente del tiempo.

### Descripción del proyecto

Se requiere desarrollar una aplicación de consola que registre y analice el tiempo de uso de un teléfono celular durante **siete días**.

Para cada día se debe registrar el tiempo total de uso y el tiempo destinado a actividades académicas. El tiempo académico forma parte del tiempo total. El usuario establecerá una meta diaria de uso recreativo, expresada en horas, como referencia para evaluar sus hábitos.

Durante el registro, la aplicación informará si el tiempo recreativo del día se encuentra dentro del límite o si lo supera.

### Resultados esperados

1. Tiempo total de uso del dispositivo durante la semana.
2. Tiempo acumulado destinado a actividades académicas.
3. Tiempo acumulado destinado a actividades recreativas.
4. Promedio diario de uso del dispositivo.
5. Cantidad de días en que se superó la meta de uso recreativo.
6. Porcentajes del tiempo semanal destinados a actividades académicas y recreativas.
7. Valoración general sobre el cumplimiento de la meta.

La aplicación debe validar que los tiempos sean coherentes, no negativos y no superen las 24 horas diarias, y que el tiempo académico no supere el total diario.

**Propósito social:** Promover la autorregulación del tiempo de pantalla y la reflexión sobre los hábitos digitales.

---

## Proyecto 2. Sistema de seguimiento de hábitos saludables

### Problemática

Mantener hábitos saludables constituye un desafío para muchas personas, especialmente estudiantes que deben distribuir su tiempo entre actividades académicas, responsabilidades personales y descanso.

La falta de seguimiento de la hidratación, el sueño y la actividad física puede dificultar la identificación de hábitos que necesitan atención. Una herramienta sencilla de registro puede ayudar a observar las rutinas diarias.

### Descripción del proyecto

Se propone desarrollar una aplicación de consola que permita realizar el seguimiento durante **siete días consecutivos** de tres hábitos personales:

- Consumo diario de agua, expresado en litros.
- Horas de sueño.
- Minutos dedicados a actividad física.

Al iniciar, el usuario establecerá una meta diaria para cada hábito. En cada jornada, la aplicación determinará qué metas se cumplen y presentará un resumen de los tres indicadores.

### Resultados esperados

1. Cantidad total de agua consumida durante la semana.
2. Promedio diario de horas de sueño.
3. Tiempo total dedicado a actividad física.
4. Número de días en que se cumplió la meta de hidratación.
5. Número de días en que se cumplió la meta de descanso.
6. Número de días en que se cumplió la meta de actividad física.
7. Cantidad de días en que se cumplieron simultáneamente las tres metas.
8. Porcentaje general de cumplimiento de las metas (metas cumplidas respecto de las 21 evaluaciones posibles).

La aplicación debe validar cantidades no negativas y evitar que las horas de sueño o los minutos de actividad física superen la duración de un día.

**Propósito social:** Fomentar la observación de hábitos personales relacionados con el bienestar.

> **Consideración:** La herramienta presenta información descriptiva; no es un sistema de diagnóstico ni de recomendación médica.

---

## Proyecto 3. Sistema de seguimiento de alimentación diaria

### Problemática

La organización de la alimentación es importante en la vida cotidiana. Sin embargo, muchas personas no registran sus hábitos alimentarios y desconocen cómo se distribuyen sus comidas durante el día.

La ausencia de información organizada dificulta identificar rutinas como la omisión de comidas o el consumo reiterado de determinados tipos de alimentos. Se plantea una herramienta de registro y análisis para facilitar la reflexión personal.

### Descripción del proyecto

Se requiere una aplicación de consola que registre las comidas realizadas durante **siete días**, considerando tres momentos diarios: desayuno, almuerzo y cena.

Para cada momento, el usuario indicará si realizó la comida. En caso afirmativo, seleccionará el tipo predominante de alimento consumido:

| Código | Tipo de alimento |
|---|---|
| 1 | Frutas y verduras |
| 2 | Cereales y tubérculos |
| 3 | Carnes, huevos y legumbres |
| 4 | Otros alimentos |

Al finalizar cada día se presentará un resumen de las comidas realizadas y omitidas.

### Resultados esperados

1. Número total de comidas realizadas.
2. Cantidad de desayunos, almuerzos y cenas registrados.
3. Cantidad de comidas omitidas durante la semana.
4. Número de registros correspondientes a cada tipo de alimento.
5. Promedio diario de comidas realizadas.
6. Porcentaje de comidas realizadas respecto de las **21 comidas posibles** durante la semana.
7. Cantidad de días en que se realizaron las tres comidas.

La aplicación debe validar las opciones ingresadas y evitar solicitar o registrar un tipo de alimento cuando la comida no se realizó.

**Propósito social:** Favorecer la observación de rutinas alimentarias mediante el registro organizado de información.

> **Consideración:** El sistema no determina si una dieta es saludable ni calcula necesidades nutricionales; describe los hábitos registrados.

---

## Proyecto 4. Sistema de planificación y seguimiento del ahorro personal

### Problemática

La administración de recursos económicos es una dificultad frecuente entre jóvenes y estudiantes universitarios. En muchos casos, las personas reciben ingresos de distintas fuentes y realizan gastos cotidianos sin información clara sobre cuánto dinero utilizan o pueden destinar al ahorro.

Esto puede dificultar el cumplimiento de metas económicas, como adquirir materiales académicos, financiar formación o cubrir gastos personales. Se plantea una herramienta para organizar movimientos económicos y evaluar el cumplimiento de una meta de ahorro.

### Descripción del proyecto

Se requiere desarrollar una aplicación de consola para registrar los movimientos económicos personales de un período mensual.

Al iniciar, el usuario establecerá una **meta de ahorro mensual**. Podrá registrar varios movimientos hasta indicar que desea finalizar:

- **Ingreso:** dinero recibido.
- **Gasto:** dinero utilizado para cubrir necesidades; se clasificará según una categoría.

| Código | Categoría del gasto |
|---|---|
| 1 | Alimentación |
| 2 | Transporte |
| 3 | Educación |
| 4 | Otros gastos |

Por cada movimiento se ingresará el tipo y el valor. Cuando se trate de un gasto, se especificará su categoría. Durante el registro se informará cómo cada operación afecta el balance acumulado.

### Resultados esperados

1. Cantidad total de movimientos económicos registrados.
2. Total de ingresos.
3. Total de gastos.
4. Total de gastos por cada categoría.
5. Balance económico final (ingresos menos gastos).
6. Porcentaje de ingresos utilizado en gastos.
7. Dinero disponible para ahorro (cero cuando el balance sea negativo).
8. Diferencia entre el ahorro disponible y la meta establecida.
9. Valoración del cumplimiento de la meta.

Se deben validar las opciones y los valores económicos, que deben ser mayores que cero. Si no se registran ingresos, el programa debe evitar divisiones entre cero y presentar un resultado coherente. También debe contemplar el caso de finalizar sin movimientos.

**Propósito social:** Fortalecer la organización de los recursos económicos y promover hábitos de planificación financiera.

---

## Entregables

| N.º | Entregable | Asignatura |
|---|---|---|
| 1 | Análisis del problema | Fundamentos Computacionales |
| 2 | Miniespecificación | Fundamentos Computacionales |
| 3 | Algoritmo completo | Fundamentos Computacionales |
| 4 | Pruebas de escritorio | Fundamentos Computacionales |
| 5 | Proyecto desarrollado en Java | Introducción a la Programación |
| 6 | Evidencia de ejecución y pruebas | Introducción a la Programación |
| 7 | Presentación y defensa del proyecto | Ambas |

Las pruebas de escritorio y la ejecución del programa Java deben producir resultados equivalentes al usar los mismos datos.

## Organización sugerida de los diez días

| Día | Actividad |
|---|---|
| 1 | Selección del proyecto y comprensión de la problemática. |
| 2 | Análisis de requisitos y datos de entrada y salida. |
| 3 | Desarrollo de la miniespecificación. |
| 4 | Elaboración y revisión del algoritmo. |
| 5 | Inicio de la implementación en Java. |
| 6 | Implementación de las condiciones y cálculos. |
| 7 | Implementación del procesamiento con `while`. |
| 8 | Pruebas y corrección de errores. |
| 9 | Preparación de entregables y exposición. |
| 10 | Presentación y defensa del proyecto. |

## Condición de participación

Los tres integrantes deberán comprender **ambas soluciones**: la algorítmica y la desarrollada en Java. Durante la defensa, cualquiera de los integrantes podrá ser consultado sobre el análisis, las decisiones del algoritmo, las condiciones, las iteraciones y los resultados de las pruebas.

La finalidad del proyecto es construir una herramienta funcional para una necesidad concreta, no solamente ejecutar operaciones matemáticas aisladas.
