---
categoria: Procesamiento y Representación de Datos
tipo: concepto
tags: [ai, machine_learning, nlp, representacion_de_datos]
---

## Definición
Los Embeddings son un mapeo de tokens discretos a vectores de números continuos en un espacio multidimensional, permitiendo que las redes neuronales procesen datos no numéricos.

Estos vectores capturan el significado semántico de los datos, de modo que elementos con significados similares se ubiquen en posiciones cercanas dentro de dicho espacio vectorial.

## Relacionados
- [[Tokenización]]
- [[Redes Neuronales]]
- [[Arquitectura Transformer]]
- [[Mecanismo de Atención]]

## Ejemplo
En un espacio de embeddings, palabras como “rey”, “reina” y “príncipe” pueden ubicarse cerca unas de otras porque tienen significados relacionados, mientras que palabras como “computadora” o “montaña” estarán más alejadas en el espacio vectorial.

## Imagen / Diagrama
![[word_embeddings_space.png]]

## Diferencia con / No confundir con
- [[Tokenización]]: la tokenización divide el texto en tokens, mientras que los embeddings convierten esos tokens en vectores numéricos.
- [[Redes Neuronales]]: las redes neuronales utilizan embeddings como representación de entrada para procesar datos.

## Notas
- Permiten representar palabras o tokens como vectores numéricos.
- Capturan relaciones semánticas entre palabras.
- Son ampliamente utilizados en modelos de lenguaje y procesamiento de texto.