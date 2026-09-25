**Paso 2 – Frameworks de Gobernanza y Soporte**

Autores: Daniel Ignasio Fuentes Estrada, Tomas Alberto Arias Zabala y Bryan Esteban Velilla Perez

**Descripción**

En este paso se identifican los mecanismos de gobierno y los procesos que apoyan la Arquitectura Empresarial de H&S Tecnología y Marketing S.A.S., tomando como base el Taller \#1 y la documentación técnica de PROTO-SHA. Como la empresa está en una etapa pequeña y cuenta con tres fundadores, los marcos se aplican de forma ligera: se toma de cada uno lo esencial para ordenar la operación, sin exigir procesos que la empresa todavía no necesita.

**Frameworks Existentes**

| **Framework**                                                          | **Área**               | **Descripción**                                                                                                                                                                                                                          |
|------------------------------------------------------------------------|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Plan estratégico del Taller \#1 (seguimiento tipo OKR)                 | Dirección / negocio    | La estrategia de penetración de mercado y los tres objetivos estratégicos del Taller 1 (vincular 25 micronegocios, reducir el tiempo de respuesta en 50 %, consolidar alianzas) se manejan como metas trimestrales para medir el avance. |
| Gestión ágil de desarrollo (Kanban ligero)                             | Tecnología             | Organiza el desarrollo y los ajustes del agente en tareas cortas y visibles, sin la carga de un proceso formal de Scrum.                                                                                                                 |
| Gestión de seguridad de la información (ISO/IEC 27001 como referencia) | Tecnología             | Guía de buenas prácticas para proteger los datos de comerciantes y clientes finales que pasan por el agente.                                                                                                                             |
| Programa de protección de datos personales (Ley 1581 de 2012)          | Administración         | Define la política de tratamiento de datos, la autorización de comerciantes y clientes, y la atención de consultas o reclamos.                                                                                                           |
| Marco financiero y contable básico                                     | Administración         | Presupuesto, facturación y obligaciones tributarias ante la DIAN, además del control de los ingresos por suscripción mensual.                                                                                                            |
| Política de uso aceptable de la API de WhatsApp Business (Meta)        | Tecnología / Comercial | Reglas de Meta sobre el tipo de mensajes, tiempos de respuesta y uso comercial del canal, que cada implementación del agente debe cumplir.                                                                                               |

**Procesos Relacionados**

| **Proceso**                                               | **Área Responsable** | **Relación con EA**                                                                                                                     |
|-----------------------------------------------------------|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Planeación estratégica y seguimiento de objetivos         | Dirección            | La arquitectura arranca de la estrategia del Taller 1; sus tres objetivos se revisan en cada ciclo de trabajo.                          |
| Desarrollo y evolución del agente de IA                   | Tecnología           | Es el proceso que más influye la arquitectura: cada ajuste al agente se revisa contra los principios definidos en el Paso 4.            |
| Implementación y configuración del agente por comerciante | Tecnología / Soporte | La arquitectura define cómo se conectan el agente, WhatsApp y los componentes necesarios para cada negocio nuevo.                       |
| Atención y toma de pedidos                                | Comercial / Soporte  | La arquitectura organiza el flujo cliente → WhatsApp → agente → pedido → confirmación.                                                  |
| Soporte y mantenimiento                                   | Tecnología           | La arquitectura debe permitir ajustes, seguimiento y continuidad del servicio sin afectar a los comerciantes activos.                   |
| Gestión comercial y alianzas                              | Comercial            | De aquí sale la meta de vincular 25 micronegocios en el primer año y las alianzas con la Cámara de Comercio y el Nuevo Mercado.         |
| Gobierno de arquitectura                                  | Equipo fundador      | Proceso nuevo que nace con este trabajo: revisar las decisiones importantes de arquitectura y aprobar las excepciones a los principios. |
| Gestión de integraciones externas                         | Tecnología           | La arquitectura debe controlar integraciones con Twilio, Gmail API, servicios de IA, n8n y futuros CRM o herramientas BI.               |

*Nota: en este paso se identifican los marcos de apoyo y los procesos del caso; la selección concreta de herramientas se desarrolla en el Paso 6.*
