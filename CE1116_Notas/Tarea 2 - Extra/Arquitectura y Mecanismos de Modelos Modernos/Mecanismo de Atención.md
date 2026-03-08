---
categoria: Arquitectura y Mecanismos de Modelos Modernos
tipo: concepto
tags: [ai, machine_learning, transformers, nlp, deep_learning]
---

## Definición
El Mecanismo de Atención es una función que permite al modelo identificar y ponderar la importancia relativa de diferentes partes de una secuencia de entrada con respecto a un elemento específico.

Este mecanismo posibilita la captura de dependencias de largo alcance y relaciones contextuales globales, sin importar la distancia física entre los tokens en el texto original.

## Relacionados
- [[Arquitectura Transformer]]
- [[Embeddings]]
- [[Tokenización]]
- [[Ventana de Contexto]]
- [[Redes Neuronales]]

## Ejemplo
En la oración “El gato que estaba en el jardín maulló fuerte”, el modelo puede usar el mecanismo de atención para relacionar la palabra “maulló”** con “gato”, incluso si hay varias palabras entre ellas.

## Imagen / Diagrama
![[attention_mechanism.png]]

## Diferencia con / No confundir con
- [[Arquitectura Transformer]]: la atención es un componente fundamental dentro de esta arquitectura.
- [[Embeddings]]: los embeddings representan tokens como vectores, mientras que la atención analiza relaciones entre esos tokens.

## Notas
- Es uno de los componentes clave de los modelos Transformer.
- Permite al modelo enfocarse en las partes más relevantes de la información de entrada.
- Facilita el aprendizaje de relaciones entre palabras o elementos que pueden estar muy separados en una secuencia.