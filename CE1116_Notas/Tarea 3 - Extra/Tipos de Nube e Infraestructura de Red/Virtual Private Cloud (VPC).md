---
categoria: Tipos de Nube e Infraestructura de Red
tipo: concepto
tags: [redes, sdn, seguridad, aislamiento]
---

## Definición
Abstracción lógica y red definida por software (**SDN**) que garantiza aislamiento de rendimiento y control total sobre el direccionamiento IP dentro de una nube pública. Permite segmentación interna mediante subredes, control de salida mediante NAT y conectividad híbrida segura.

## Relacionados
[[Cloud Público]]
[[Cloud Híbrido (Hybrid cloud)]]

## Ejemplo
Crear una red aislada en la nube donde la "Subred A" tiene acceso a internet para la web, pero la "Subred B" (base de datos) está totalmente bloqueada del mundo exterior.

## Diferencia con / No confundir con
Subred: una subred es una división dentro de la VPC; la VPC es el contenedor completo.
VPN: la VPN es el túnel para llegar a la red; la VPC es la red en sí misma.

## Notas
- Garantiza que el tráfico de otros clientes no afecte tu ancho de banda (Andromeda).
- Es el pilar para conectar tu oficina física con la nube de forma segura.

## Imagen / Diagrama
![[Diagrama_VPC_Architecture.png]]