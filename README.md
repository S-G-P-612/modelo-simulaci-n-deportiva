# Modelo Predictivo y Simulación de Resultados Deportivos
 ## Descripción;

Este proyecto tiene como objetivo desarrollar un modelo predictivo y de simulación aplicado a partidos de fútbol, utilizando datos históricos para estimar la probabilidad de los diferentes resultados posibles de un partido.

La finalidad principal no es recomendar apuestas, sino estudiar cómo un modelo matemático puede representar un fenómeno real caracterizado por la incertidumbre y utilizarlo para generar diferentes escenarios mediante simulación.

 ## Objetivo general: 

Desarrollar un modelo capaz de estimar y simular la probabilidad de los resultados de un partido de fútbol a partir de datos pasados y variables relacionadas con el rendimiento de los equipos.

 ## Preguntas de investigación:

¿Es posible desarrollar un modelo basado en datos históricos que permita estimar y simular la probabilidad de los diferentes resultados de un partido de fútbol?
¿Qué variables tienen mayor influencia sobre la estimación del resultado de un partido?

## Variables consideradas;

- Rendimiento reciente

- Victorias en los últimos partidos

- Empates

- Derrotas

- Goles anotados

- Goles recibidos

- Local o visitante

- Días de descanso

- Posición en la tabla

- Puntos acumulados


 ## Metodología propuesta

El proyecto se desarrollará en diferentes etapas:

Datos históricos
       ↓
Preparación y limpieza
       ↓
Modelo predictivo
       ↓
Simulación Monte Carlo
       ↓
Distribución de resultados
       ↓
Validación
       ↓
Análisis de resultados

## Simulación

Una vez estimados los parámetros del modelo, se realizarán múltiples simulaciones de un mismo partido.

Por ejemplo:

Simulaciones: 10,000

Victoria local:       XX%
Empate:               XX%
Victoria visitante:   XX%


La simulación permitirá estudiar la distribución de posibles resultados en lugar de producir únicamente una predicción determinista.

## Validación

El modelo será evaluado utilizando partidos que no hayan sido utilizados durante su construcción.

Se considerarán métricas como:

Accuracy

Matriz de confusión

Log Loss


También se compararán las probabilidades estimadas por el modelo con las frecuencias observadas en los resultados reales.

## Experimentos propuestos

Se realizarán diferentes experimentos para analizar el comportamiento del modelo.

Experimento 1 — Modelo base

Utilizar variables básicas de rendimiento y condición de local/visitante.

Experimento 2 — Forma reciente

Incorporar el rendimiento de los últimos partidos.

Experimento 3 — Descanso

Analizar el efecto de los días de descanso sobre las probabilidades estimadas.

Experimento 4 — Simulación Monte Carlo

Generar miles de escenarios posibles para un mismo partido.

Experimento 5 — Análisis de sensibilidad

Modificar determinadas variables y observar cómo cambia la distribución de resultados del modelo.

## Limitaciones

Los resultados de un modelo predictivo deportivo están sujetos a incertidumbre. El rendimiento pasado no garantiza resultados futuros y existen factores que pueden ser difíciles de representar mediante datos históricos.
