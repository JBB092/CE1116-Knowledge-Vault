---
categoria: Redundancia y Resiliencia
tipo: concepto
tags: [disaster_recovery, rpo, rto, regiones]
---

## Definición
Estrategia de **Disaster Recovery** que utiliza replicación asíncrona entre pares de regiones distantes (cientos de km). Diseñada para la continuidad ante desastres regionales (terremotos, inundaciones masivas) asegurando independencia eléctrica y sísmica.

## Relacionados
[[Redundante en Zona]]
[[Cloud Híbrido (Hybrid cloud)]]

## Ejemplo
Tener los datos principales en la región de "Este de EE.UU." y una copia de seguridad constante en "Oeste de EE.UU." por si ocurre un evento catastrófico en toda la costa este.

## Diferencia con / No confundir con
Replicación síncrona: GRS es asíncrona por la distancia; siempre hay un pequeño desfase (RPO) de segundos o minutos en los datos.

## Notas
- Es el modelo más costoso por las tarifas de transferencia de datos (*egress*).
- Sujeto a leyes de soberanía de datos (no puedes replicar fuera del país en ciertos casos).

## Imagen / Diagrama
![[Diagrama_Replication.png]]