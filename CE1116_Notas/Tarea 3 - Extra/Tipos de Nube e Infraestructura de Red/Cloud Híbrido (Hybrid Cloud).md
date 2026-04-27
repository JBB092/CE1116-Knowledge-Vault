---
categoria: Tipos de Nube e Infraestructura de Red
tipo: concepto
tags: [arquitectura, interoperabilidad, edge, soberanía]
---

## Definición
Ecosistema interoperable que orquestra recursos locales (on-premises) y de nube pública mediante capas de estandarización. Permite la portabilidad dinámica de aplicaciones y es vital para industrias que requieren mantener datos sensibles localmente por ley (soberanía de datos).

## Relacionados
[[Cloud Público]]
[[Virtual Private Cloud (VPC)]]
[[Redundante Geo-Redundante]]

## Ejemplo
Una empresa financiera que guarda los datos de sus clientes en sus propios servidores (por seguridad), pero usa la nube pública para procesar reportes masivos cuando hay mucha demanda (**Cloud Bursting**).

## Diferencia con / No confundir con
Multi-cloud: usar varios proveedores públicos (AWS + Azure). El híbrido es mezclar lo privado/local con lo público.

## Notas
- Requiere una capa de abstracción consistente (como Kubernetes).
- Integra el procesamiento en el borde (Edge) para mayor velocidad.

## Imagen / Diagrama
![[Diagrama_Hybrid_Cloud_Bridge.png]]