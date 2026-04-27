---
categoria: Redundancia y Resiliencia
tipo: concepto
tags: [alta_disponibilidad, az, resiliencia]
---

## Definición
Pilar de la **Alta Disponibilidad (HA)** que replica datos síncronamente entre múltiples Zonas de Disponibilidad (AZ) con infraestructura independiente. Un fallo masivo en una zona permite un failover automático sin pérdida de datos.

## Relacionados
[[Redundante Localmente]]
[[Redundante Geo-Redundante]]
[[Escalamiento Horizontal y Vertical]]

## Ejemplo
Una base de datos crítica de un banco que debe seguir operando aunque un rayo deje sin electricidad a todo un sector de la ciudad donde está un centro de datos.

## Diferencia con / No confundir con
[[Redundante Localmente]]: LRS protege contra un disco roto; ZRS protege contra un edificio destruido.

## Notas
- Utiliza redes de fibra óptica de muy baja latencia.
- Es el estándar para aplicaciones de producción.

## Imagen / Diagrama
![[Diagrama_Replication.png]]