---
categoria: Tipos de Nube e Infraestructura de Red
tipo: concepto
tags: [cloud, infraestructura, opEx, multi-tenancy]
---

## Definición
Modelo de hiper-escala basado en multi-inquilinidad masiva y recursos elásticos, donde el usuario aprovisiona servicios mediante autoservicio programático (APIs). Opera bajo un modelo de gasto operativo (**OpEx**) y de **Responsabilidad Compartida**, donde la gestión de seguridad y datos se divide entre el proveedor y el cliente según el nivel de abstracción.

## Relacionados
[[Virtual Private Cloud (VPC)]]
[[Cloud Híbrido (Hybrid cloud)]]
[[IaaS vs PaaS vs SaaS]]

## Ejemplo
Un desarrollador que lanza una base de datos en AWS o Azure usando su consola web o una línea de comandos, pagando solo por las horas que el servicio estuvo activo.

## Diferencia con / No confundir con
[[Cloud Híbrido (Hybrid cloud)]]: el público es 100% infraestructura del proveedor, el híbrido mezcla esta con servidores propios (on-premises).
Nube Privada: la privada es de uso exclusivo de una organización (física), mientras que el Cloud Público comparte el hardware físico entre muchos clientes (aislamiento lógico).

## Notas
- El beneficio económico viene de la infraestructura global del proveedor.
- El acceso no es solo por "internet abierta", puede ser por túneles cifrados.
- El usuario no compra hardware, consume servicios.

## Imagen / Diagrama
![[Diagrama_Cloud_Publico_Shared_Infra.png]]