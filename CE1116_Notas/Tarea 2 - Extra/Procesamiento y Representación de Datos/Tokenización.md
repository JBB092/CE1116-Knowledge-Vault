---
categoria: Procesamiento y Representación de Datos
tipo: concepto
tags: [ai, machine_learning, nlp, procesamiento_de_texto]
---

## Definición
La Tokenización es el proceso de descomponer un texto de entrada en unidades más pequeñas llamadas tokens, que pueden ser palabras individuales, caracteres o fragmentos de palabras.

Es el paso inicial necesario para convertir el lenguaje humano en una representación que los modelos de lenguaje puedan procesar de manera eficiente.

## Relacionados
- [[Embeddings]]
- [[Redes Neuronales]]
- [[Arquitectura Transformer]]
- [[Ventana de Contexto]]

## Ejemplo
La frase:

"Los modelos de lenguaje son útiles"

podría tokenizarse como:

["Los", "modelos", "de", "lenguaje", "son", "útiles"]

Cada uno de estos elementos se convierte luego en una representación numérica para que el modelo pueda procesarlo.

## Imagen / Diagrama
![[tokenization_example.png]]

## Diferencia con / No confundir con
- [[Embeddings]]: la tokenización divide el texto en tokens, mientras que los embeddings convierten esos tokens en vectores numéricos.
- [[Ventana de Contexto]]: la ventana de contexto define cuántos tokens puede procesar el modelo al mismo tiempo.

## Notas
- Es uno de los primeros pasos en el procesamiento de lenguaje natural.
- Los tokens pueden ser palabras, caracteres o subpalabras.
- Los modelos de lenguaje operan internamente sobre tokens en lugar de texto completo.