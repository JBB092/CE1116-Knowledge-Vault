---
categoria: Arquitectura y Mecanismos de Modelos Modernos
tipo: concepto
tags: [ai, machine_learning, transformers, nlp, deep_learning]
---

## Definición
La Arquitectura Transformer es un tipo de arquitectura de red neuronal profunda que se basa exclusivamente en mecanismos de atención, prescindiendo totalmente de la recurrencia y las convoluciones utilizadas en modelos anteriores. Su diseño permite el procesamiento en paralelo de secuencias completas, lo que mejora la calidad de los resultados y reduce significativamente el tiempo de entrenamiento.

## Relacionados
- [[Mecanismo de Atención]]
- [[Embeddings]]
- [[Tokenización]]
- [[Ventana de Contexto]]
- [[Redes Neuronales]]

## Ejemplo
Modelos modernos de lenguaje como los utilizados en asistentes virtuales o sistemas de generación de texto utilizan arquitecturas Transformer para analizar una oración completa y determinar la relación entre sus palabras antes de generar una respuesta.

## Imagen / Diagrama
![[transformer_architecture.png]]

## Diferencia con / No confundir con
- [[Redes Neuronales]]: es un tipo específico de arquitectura dentro de las redes neuronales profundas.
- [[Mecanismo de Atención]]: la atención es un componente dentro del Transformer, no la arquitectura completa.

## Notas
- Introducida en el artículo *Attention is All You Need* en 2017.
- Permite el procesamiento paralelo de secuencias completas.
- Es la base de muchos modelos modernos de lenguaje.
- Utiliza mecanismos de atención para identificar relaciones entre tokens en una secuencia.