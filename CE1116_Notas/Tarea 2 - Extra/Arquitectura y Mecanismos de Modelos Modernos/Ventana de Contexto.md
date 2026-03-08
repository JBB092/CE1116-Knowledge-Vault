---
categoria: Arquitectura y Mecanismos de Modelos Modernos
tipo: concepto
tags: [ai, machine_learning, nlp, transformers, contexto]
---

## Definición
La Ventana de Contexto es la cantidad máxima de texto o tokens que un modelo de lenguaje puede procesar y "ver" simultáneamente para generar una respuesta.

Define el límite de información, como el historial de una conversación o la extensión de un documento, que el modelo puede mantener en su memoria de trabajo durante una tarea específica.

## Relacionados
- [[Arquitectura Transformer]]
- [[Mecanismo de Atención]]
- [[Tokenización]]
- [[Embeddings]]

## Ejemplo
Si un modelo tiene una ventana de contexto de 8,000 tokens, solo podrá considerar aproximadamente esa cantidad de texto al mismo tiempo. Si el texto o conversación supera ese límite, las partes más antiguas pueden dejar de ser tomadas en cuenta.

## Diferencia con / No confundir con
- [[Mecanismo de Atención]]: la atención determina qué partes del texto son más importantes, mientras que la ventana de contexto define cuánto texto puede analizar el modelo.
- [[Tokenización]]: la tokenización divide el texto en tokens, que luego son los elementos que cuentan dentro de la ventana de contexto.

## Notas
- Determina cuánta información puede considerar el modelo al mismo tiempo.
- Es una limitación técnica importante en los modelos de lenguaje.
- Ventanas de contexto más grandes permiten analizar documentos más largos o conversaciones extensas.