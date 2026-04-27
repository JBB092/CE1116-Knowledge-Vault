---
categoria: Escalamiento y Modelos de Servicio
tipo: concepto
tags: [abstracción, responsabilidad, modelos_servicio]
---

## Definición
Modelos que dictan el nivel de gestión: **IaaS** ofrece infraestructura base (el usuario gestiona SO y parches); **PaaS** abstrae la plataforma para desarrolladores (gestiona escalado y runtime); y **SaaS** entrega software listo para el usuario final gestionado íntegramente por el proveedor.

## Relacionados
[[Cloud Público]]
[[Escalamiento Horizontal y Vertical]]

## Ejemplo
**IaaS:** Alquilar un servidor vacío en la nube (EC2).
**PaaS:** Subir código a un servicio que lo ejecuta sin configurar servidores (Heroku/App Engine).
**SaaS:** Usar Google Workspace o Microsoft 365.

## Diferencia con / No confundir con
On-premises: donde tú eres responsable de hasta la electricidad y el aire acondicionado. En la nube, siempre delegas algo.

## Notas
- A mayor abstracción (SaaS), mayor dependencia del proveedor (*Vendor Lock-in*).
- Define quién es responsable legal de la seguridad de los datos.

## Imagen / Diagrama
![[Diagrama_Cloud_Responsibility_Stack.png]]