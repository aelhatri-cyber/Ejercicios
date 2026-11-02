# T02 — Ejercicios de clase
## EC2.1 ¿IT u OT? (b)

|  #  | Sistema |  IT  |  OT  |  Mix  |
|:---:|---------|:----:|:----:|:-----:|
|  1  | Servidor de correo corporativo (Microsoft 365) |X|||
|  2  | SCADA de una planta química que controla válvulas y sensores ||X||
|  3  | ERP en la nube que gestiona pedidos y facturación |X|||
|  4  | PLC que gobierna una cadena de montaje ||X||
|  5  | Plataforma de tickets de soporte (Jira, Zendesk) |X|||
|  6  | Sistema MES que conecta el PLC con el ERP |||X|
|  7  | Software de copias de seguridad de los servidores |X|||
|  8  | Sistema de control de accesos de un edificio (tarjetas) |||X|

## EC2.2 Departamentos IT de una empresa (b)

| Área / Departamento | ¿Qué gestiona? | ¿Por qué es entorno IT? |
| --- | --- | --- |
| Sistemas y redes | Servidores, ordenadores, redes y conexiones. | Gestiona la infraestructura informática. |
| Desarrollo de software | Aplicaciones, páginas web y programas. | Crea y mantiene sistemas de información. |
| Ciberseguridad | Protección de datos, sistemas y usuarios. | Protege la información y los recursos digitales. |
| Soporte técnico | Incidencias y asistencia a empleados y clientes. | Mantiene los servicios informáticos funcionando. |
| Administración y finanzas | Facturas, nóminas, presupuestos y contabilidad. | Gestiona información económica mediante herramientas digitales. |
| Marketing y ventas | Campañas, clientes y oportunidades comerciales. | Utiliza sistemas digitales para gestionar información comercial. |

## EC2.3 Tecnología de negocio vs. de planta (b)

| Tecnología | Negocio | Planta |
| --- | --- | --- |
| ERP (SAP, Oracle, etc.) | X |  |
| SCADA / HMI |  | X |
| CRM (Salesforce, HubSpot) | X |  |
| MES (Manufacturing Execution System) |  | X |
| E-commerce (PrestaShop, Shopify) | X |  |
| PLC / PAC |  | X |
| BI / Data Warehouse | X |  |
| Robots colaborativos (cobots) |  | X |

## EC2.4 Qué hace que IT y OT se parezcan y se diferencien (m)

| Aspecto | IT | OT |
| --- | --- | --- |
| Coincidencia 1 | Utiliza redes para comunicar dispositivos y sistemas. | Utiliza redes para comunicar máquinas y sistemas de control. |
| Coincidencia 2 | Necesita medidas de ciberseguridad. | Necesita medidas de ciberseguridad. |
| Coincidencia 3 | Recoge y procesa información para tomar decisiones. | Recoge y procesa datos de máquinas para controlar procesos. |
| Diferencia 1 | Su prioridad suele ser proteger los datos y garantizar su disponibilidad. | Su prioridad es mantener la seguridad física y la continuidad de la producción. |
| Diferencia 2 | Sus sistemas suelen actualizarse con relativa frecuencia. | Las actualizaciones deben probarse cuidadosamente para evitar detener máquinas. |
| Diferencia 3 | Gestiona principalmente información empresarial. | Controla procesos físicos, sensores y maquinaria industrial. |

## EC2.5 Convergencia IT-OT de una consultora IT (m)

**Caso: BIT Consultores**

**1\. ¿Cuál es el entorno IT de BIT Consultores? ¿Y cuál es el entorno OT que ahora entra en casa del cliente?**

- **IT:** Los servidores, la plataforma en la nube, las redes, las aplicaciones y los sistemas informáticos de BIT Consultores.
- **OT:** Los sensores IoT, los PLC, los sistemas SCADA y los equipos industriales que controlan los procesos físicos del cliente.

**2\. ¿Qué sistema hace de puente entre los dos entornos?**

La plataforma IoT en la nube, que recibe los datos de los sensores y permite transmitir información entre los equipos industriales y los técnicos de BIT.

**3\. ¿Qué tecnología habilitadora permite que un técnico de BIT vea, en tiempo real, el estado de la línea de producción de un cliente a 500 km?**

La combinación de sensores IoT, conectividad a Internet, comunicaciones industriales y computación en la nube.

**4\. ¿Qué ventajas tiene para el cliente industrial?**

- Detectar averías antes de que ocurran.
- Reducir paradas inesperadas de producción.
- Disminuir los costes de mantenimiento.
- Supervisar las instalaciones a distancia.
- Mejorar la eficiencia de los equipos.

**5\. ¿Qué riesgo nuevo introduce esta conexión que antes no existía?**

Aumenta la superficie de ataque: un ciberdelincuente podría acceder a la red industrial a través de la conexión remota, robar información o manipular los sistemas de control y provocar una parada de producción.

## EC2.6 Ventajas de una digitalización de extremo a extremo (m)

**Caso: DeltaCode**

| Ámbito | Ventaja | Justificación (1-2 frases) |
| --- | --- | --- |
| Producción | Mayor control del inventario. | La integración con el MES permite conocer las existencias y las necesidades de producción. |
| Negocio | Automatización de procesos. | El SaaS reduce tareas manuales y facilita la gestión de inventarios de las pymes. |
| Mantenimiento | Detección temprana de problemas. | La monitorización permite identificar incidencias antes de que provoquen fallos importantes. |
| Atención al cliente | Mejor servicio y disponibilidad. | El soporte 24×7 permite atender incidencias durante todo el día. |
| Información | Datos centralizados. | La integración de los sistemas facilita consultar información desde diferentes áreas. |
| Competitividad | Mayor valor añadido. | DeltaCode pasa de vender horas de programación a ofrecer un servicio digital completo y continuo. |