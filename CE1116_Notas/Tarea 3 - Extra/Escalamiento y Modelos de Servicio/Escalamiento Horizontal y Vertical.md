---
categoria: Escalamiento y Modelos de Servicio
tipo: concepto
tags: [elasticidad, disponibilidad, performance, infraestructura]
---

## Definición
El escalamiento **Vertical** (*Scale Up*) ajusta la potencia de una instancia (más CPU/RAM) con límites físicos y posible downtime. El **Horizontal** (*Scale Out*) añade más nodos elásticos tras un balanceador de carga para eliminar puntos únicos de fallo y mejorar la disponibilidad.

## Relacionados
[[IaaS vs PaaS vs SaaS]]
[[Redundante en Zona]]

## Ejemplo
**Vertical:** Cambiar un servidor de 4GB a 16GB de RAM (necesita reinicio).
**Horizontal:** Durante un "Black Friday", el sistema detecta tráfico y crea automáticamente 5 servidores gemelos para repartir la carga.

## Diferencia con / No confundir con
Alta Disponibilidad: el escalamiento horizontal ayuda a la disponibilidad, pero el vertical no (si el servidor único falla, todo cae).

## Notas
- El horizontal requiere aplicaciones *stateless* (sin estado local).
- El vertical tiene un "techo" definido por el hardware del host físico.

## Imagen / Diagrama
![[Diagrama_Scale_Up_vs_Scale_Out.png]]