**Paso 1 – Definición del Alcance del Enterprise**

Autores: Daniel Ignasio Fuentes Estrada, Tomas Alberto Arias Zabala y Bryan Esteban Velilla Perez

**Información del Proyecto**

| **Campo**           | **Detalle**                                                                                          |
|---------------------|------------------------------------------------------------------------------------------------------|
| Nombre del proyecto | Automatización de Agentes de Inteligencia Artificial en WhatsApp para el Comercio Local de Sincelejo |
| Organización        | H&S Tecnología y Marketing S.A.S.                                                                    |
| Fecha               | 2026                                                                                                 |
| Autor(es)           | Daniel Ignasio Fuentes Estrada, Tomas Alberto Arias Zabala y Bryan Esteban Velilla Perez             |

**Core Enterprise Units**

Se entienden como Core Enterprise Units las unidades que crean directamente el valor del servicio de H&S: el desarrollo del agente de inteligencia artificial y su puesta en marcha para cada comerciante.

| **Unidad**                                    | **Descripción**                                                                                                              | **Responsabilidad**                                                                             |
|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Dirección estratégica y desarrollo de negocio | Define la visión del servicio, la propuesta de valor y las alianzas necesarias para llegar a los micronegocios de Sincelejo. | Asegurar que el producto avance según los objetivos y la estrategia definidos en el Taller \#1. |
| Desarrollo y mantenimiento de agentes de IA   | Diseño, entrenamiento y ajuste de los agentes conversacionales según el catálogo, el tono y las reglas de cada negocio.      | Mantener funcionando la solución principal que se ofrece a los micronegocios.                   |
| Implementación e integración con WhatsApp     | Conectar el agente con el canal que ya utiliza el comerciante (WhatsApp Business) y dejarlo operativo.                       | Facilitar una puesta en marcha sencilla y con poca fricción para cada nuevo cliente.            |
| Soporte y atención al cliente                 | Resolver dudas, fallos y ajustes solicitados por los comerciantes que usan el servicio.                                      | Mantener la continuidad del servicio y apoyar la retención de clientes.                         |

**Soft Enterprise Units**

Las Soft Enterprise Units son funciones de apoyo que no generan el producto en sí, pero que son necesarias para que la empresa capte clientes, los conserve y opere de forma ordenada. En esta etapa inicial, el equipo fundador las asumen de forma compartida.

| **Unidad**                    | **Relación con el proyecto**                                                                                                                                                                 | **Impacto**                                                                             |
|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| Marketing digital             | Ayuda a dar a conocer el servicio entre micronegocios de Sincelejo, aprovechando la experiencia de H&S en esta área.                                                                         | Apoya la captación de clientes.                                                         |
| Gestión comercial y alianzas  | Busca clientes y coordina relaciones con aliados. En la etapa actual esta función la cubre temporalmente el equipo fundador, ya que todavía no se cuenta con un asesor comercial contratado. | Facilita la llegada del servicio a más comerciantes sin agregar todavía un cargo nuevo. |
| Gestión de clientes           | Recoge necesidades, solicitudes y comentarios de los comerciantes que ya usan el agente.                                                                                                     | Permite mejorar el servicio y conservar clientes.                                       |
| Administración y cumplimiento | Maneja la facturación básica, los términos de servicio y el tratamiento de los datos de los clientes.                                                                                        | Sostiene la operación formal de la empresa y su cumplimiento legal.                     |

**Extended Enterprise**

El Extended Enterprise agrupa a los actores externos que, sin ser parte de H&S, son necesarios para que la solución funcione o influyen directamente en su operación. En este caso se toma como referencia la documentación técnica de PROTO-SHA y las integraciones previstas para el agente de IA.

| **Actor**                                       | **Tipo**                          | **Descripción**                                                                                                                  |
|-------------------------------------------------|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| Comerciante o micronegocio                      | Cliente / usuario                 | Contrata el servicio y utiliza el agente para atender a sus propios clientes.                                                    |
| Cliente final                                   | Usuario del servicio              | Persona que interactúa con el agente por WhatsApp para consultar productos o hacer pedidos.                                      |
| Meta / API de WhatsApp Business                 | Proveedor tecnológico             | Permite que el agente interactúe con los clientes del negocio a través del canal que ya usan.                                    |
| Proveedor de infraestructura en la nube         | Proveedor tecnológico             | Aloja el agente, sus integraciones y la información asociada al servicio.                                                        |
| Cámara de Comercio de Sincelejo / Nuevo Mercado | Socio o aliado                    | Pueden apoyar la divulgación y adopción del servicio entre comerciantes.                                                         |
| Alternativas actuales del comerciante           | Sustituto / competencia indirecta | WhatsApp manual, redes sociales y chatbots genéricos: la forma en que hoy se resuelve, de manera desordenada, el mismo problema. |
| Twilio                                          | Proveedor tecnológico             | Servicio utilizado para gestionar llamadas y la integración de comunicación con WhatsApp.                                        |
| Gmail API                                       | Proveedor tecnológico             | Permite integrar el correo electrónico al sistema de atención multicanal.                                                        |
| Gemini / GPT API                                | Proveedor de IA                   | Motor externo utilizado para analizar mensajes y generar respuestas.                                                             |
| n8n                                             | Proveedor / orquestador           | Coordina flujos entre módulos, APIs y servicios externos.                                                                        |
| AWS / infraestructura cloud                     | Proveedor tecnológico             | Servicios de infraestructura para desplegar y escalar la plataforma.                                                             |

**Stakeholders**

| **Stakeholder**                                                     | **Rol**                     | **Interés**                                                                                                                              |
|---------------------------------------------------------------------|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Equipo fundador de H&S: Daniel Fuentes, Tomas Arias y Bryan Velilla | Directivos / equipo interno | Desarrollar, mantener, gobernar y hacer crecer la solución desde sus diferentes roles fundadores.                                        |
| Comerciante o micronegocio                                          | Cliente                     | Ahorrar tiempo y atender pedidos de forma más organizada.                                                                                |
| Cliente final                                                       | Usuario del servicio        | Recibir respuestas, consultar productos y hacer pedidos por WhatsApp.                                                                    |
| Meta / proveedor de WhatsApp Business API                           | Proveedor                   | Que el uso del agente cumpla sus políticas de mensajería y uso comercial.                                                                |
| Cámara de Comercio de Sincelejo / Nuevo Mercado                     | Aliado                      | Que la propuesta apoye la formalización y modernización del comercio local.                                                              |
| Entes reguladores (SIC, DIAN)                                       | Regulador                   | Que la empresa cumpla la normativa de protección de datos y sus obligaciones tributarias.                                                |
| Asesor comercial                                                    | Rol futuro / vacante        | Apoyar la captación y seguimiento de clientes cuando el cargo sea incorporado; actualmente no hay personal contratado para esta función. |

**Contexto de Gobernanza**

| **Marco o Regulación**                                | **Descripción**                                                                                                                |
|-------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| Ley 1581 de 2012 y Decreto 1377 de 2013 (Habeas Data) | Regulan el tratamiento de datos personales de comerciantes y clientes finales que interactúan con el agente.                   |
| Ley 1273 de 2009 (delitos informáticos)               | Sirve de guía para definir los controles de seguridad de acceso a las cuentas y configuraciones del servicio.                  |
| Términos de uso de la API de WhatsApp Business (Meta) | Establecen condiciones sobre el tipo de mensajes, tiempos de respuesta y uso comercial del canal, que el agente debe respetar. |
| Ley 1258 de 2008 (S.A.S.) y normas tributarias        | Rigen la constitución de H&S Tecnología y Marketing S.A.S. y sus obligaciones con la DIAN.                                     |
| Políticas internas de H&S                             | Tratamiento de datos, condiciones del servicio y reglas de uso del agente, definidas por el equipo fundador.                   |
