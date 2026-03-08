---
categoria: Fundamentos de Inteligencia Artificial
tipo: concepto
tags: [ai, machine_learning, redes_neuronales, deep_learning]
---

## Definición
La Función de Activación es una función matemática que se aplica a la suma ponderada de las entradas de una neurona para calcular su salida o nivel de "activación".

Es un componente crítico que introduce no linealidad en el modelo, permitiendo que la red aprenda y represente relaciones complejas en los datos que no podrían capturarse mediante transformaciones lineales simples.

## Relacionados
- [[Redes Neuronales]]
- [[Embeddings]]
- [[Arquitectura Transformer]]

## Ejemplo
En una red neuronal utilizada para clasificar imágenes, la función de activación permite que la red determine si ciertas combinaciones de características detectadas en una imagen corresponden a una categoría específica.

## Imagen / Diagrama
![[activation_function_graph.png]]

## Diferencia con / No confundir con
- [[Redes Neuronales]] (la función de activación es un componente dentro de cada neurona de una red neuronal)
- [[Embeddings]] (los embeddings representan datos como vectores, mientras que las funciones de activación transforman valores dentro de las neuronas)

## Notas
- Introduce no linealidad en las redes neuronales.
- Permite que los modelos aprendan patrones complejos.
- Algunas funciones comunes son ReLU, Sigmoid y Tanh.