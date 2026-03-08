---
categoria: Comportamiento y Salidas del Modelo
tipo: concepto
tags: [ai, machine_learning, nlp, modelos_de_lenguaje]
---

## Definición
Las Alucinaciones son un fenómeno en el cual un modelo de lenguaje genera información que parece coherente y gramaticalmente correcta, pero que es fácticamente falsa, carece de sentido o no se basa en los datos de entrenamiento.

Ocurren cuando el modelo percibe patrones inexistentes o asociaciones estadísticas incorrectas al intentar predecir el siguiente token.

## Relacionados
- [[Arquitectura Transformer]]
- [[Ventana de Contexto]]
- [[Mecanismo de Atención]]
- [[Tokenización]]

## Ejemplo
Un modelo de lenguaje podría afirmar que un científico publicó un artículo en una revista que en realidad no existe, generando una cita que parece real pero que no tiene respaldo en fuentes verificables.

## Diferencia con / No confundir con
- [[Ventana de Contexto]]: la ventana de contexto limita cuánta información puede considerar el modelo, mientras que las alucinaciones son errores en la generación de información.
- [[Mecanismo de Atención]]: la atención ayuda a determinar qué partes del texto son relevantes, pero no garantiza que la información generada sea correcta.

## Notas
- Es un problema común en modelos generativos de lenguaje.
- Las respuestas pueden parecer muy convincentes aunque sean incorrectas.
- Puede ocurrir cuando el modelo intenta completar información faltante basándose en patrones estadísticos.