---
categoria: Redundancia y Resiliencia
tipo: concepto
tags: [almacenamiento, durabilidad, bajo_costo]
---

## Definición
Réplicas síncronas de datos (usualmente 3) dentro de distintos dominios de fallo (racks/nodos) en un solo centro de datos. Ofrece la mayor durabilidad de bits y menor latencia al menor costo, pero es vulnerable ante desastres totales del edificio.

## Relacionados
[[Redundante en Zona]]
[[Redundante Geo-Redundante]]

## Ejemplo
Guardar archivos temporales o logs que necesitas que se escriban muy rápido y no te importa si se pierden si el centro de datos sufriera un incendio.

## Diferencia con / No confundir con
Copia de seguridad (Backup): LRS es replicación inmediata para evitar fallos de hardware, no necesariamente un historial para recuperar archivos borrados por error.

## Notas
- Opción más económica del cloud.
- Garantiza que los datos se escriban síncronamente en las 3 copias.

## Imagen / Diagrama
![[Diagrama_Replication.png]]