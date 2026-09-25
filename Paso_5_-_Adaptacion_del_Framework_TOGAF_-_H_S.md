Paso 5 – Adaptación del Framework TOGAF

Autores: Daniel Ignasio Fuentes Estrada, Tomas Alberto Arias Zabala y Bryan Esteban Velilla Perez

Descripción

En este paso se adapta el framework TOGAF al caso de H&S Tecnología y Marketing. Las fases del ADM se usan como una guía sencilla y ligera para ordenar el análisis del negocio, los procesos, la información, las aplicaciones y la tecnología de la solución de agentes de IA documentada en PROTO-SHA, manteniendo como foco del Taller \#1 el comercio local y el uso de WhatsApp.

Terminología

| **Término**                        | **Definición**                                                                                                                      |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| TOGAF ADM                          | Método cíclico de TOGAF 10 para desarrollar la arquitectura empresarial, aplicado aquí de forma ligera y adaptada al tamaño de H&S. |
| Micronegocio / comerciante         | Negocio local de Sincelejo que contrata el servicio y utiliza el agente para atender a sus clientes.                                |
| Agente de IA                       | Componente que responde consultas, brinda información de catálogo y apoya la toma de pedidos por WhatsApp.                          |
| Pedido                             | Solicitud realizada por el cliente final que el agente registra y organiza para el comerciante.                                     |
| Cliente final                      | Persona que interactúa con el agente para consultar productos, hacer pedidos o recibir información.                                 |
| Suscripción                        | Modelo de ingresos de H&S: pago mensual del comerciante por el uso del agente, según el volumen de mensajes o pedidos.              |
| Onboarding                         | Proceso de implementación e integración del agente al WhatsApp de un nuevo comerciante.                                             |
| ADR (Architecture Decision Record) | Nota corta que registra una decisión de arquitectura: el contexto, las alternativas consideradas y lo decidido.                     |
| PROTO-SHA                          | Prototipo de inteligencia artificial conversacional multicanal de H&S que centraliza interacciones y automatizaciones.              |
| n8n                                | Orquestador de flujos utilizado para conectar módulos, APIs y acciones automáticas.                                                 |
| Integración                        | Conexión de PROTO-SHA con servicios como Twilio, Gmail API, servicios de IA y futuros CRM.                                          |

Adaptaciones del Proceso ADM

| **Fase ADM**                     | **Adaptación**                                                                                                                                                                                                                                                                                               |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enfoque general                  | TOGAF 10 aplicado de forma ligera, porque H&S es una empresa pequeña con tres founders y un producto en evolución. Solo se elabora el artefacto que realmente aporta valor en cada fase.                                                                                                                     |
| Preliminary                      | Definir el contexto de H&S, los actores y el alcance del servicio, con base en la información recogida en el Taller \#1.                                                                                                                                                                                     |
| Architecture Vision              | Definir la visión de ofrecer automatización accesible para el comercio local, usando WhatsApp como canal principal de la propuesta del Taller 1 y aprovechando la evolución multicanal documentada en PROTO-SHA. La meta inicial del Taller 1 es vincular 25 micronegocios y reducir el tiempo de respuesta. |
| Business Architecture            | Modelar la atención, la consulta de catálogo, la toma de pedidos, la confirmación y el soporte al comerciante.                                                                                                                                                                                               |
| Information Systems Architecture | Organizar los datos de clientes, productos, precios, disponibilidad, pedidos y configuración del agente, junto con las aplicaciones que los gestionan.                                                                                                                                                       |
| Technology Architecture          | Definir la tecnología que soporta la solución: Node.js/NestJS, TypeORM, base de datos relacional, n8n, servicios de IA Gemini/GPT, Twilio, Gmail API, Docker y servicios AWS, según la documentación técnica de PROTO-SHA.                                                                                   |
| Opportunities & Solutions        | Identificar mejoras e integraciones que permitan ampliar la automatización sin complicar la experiencia del comerciante, como CRM, BI, nuevos canales y flujos adicionales en n8n.                                                                                                                           |
| Migration Planning               | Planificar una implementación progresiva: comenzar con la configuración básica del agente para un grupo pequeño de comerciantes y luego agregar funciones y nuevos clientes.                                                                                                                                 |
| Implementation Governance        | Los tres founders revisan que el desarrollo y los cambios respeten los principios definidos en el Paso 4. Bryan lidera la revisión arquitectónica, Tomás valida la viabilidad técnica y Daniel valida la alineación con el negocio.                                                                          |
| Architecture Change Management   | Registrar y evaluar cambios futuros en procesos, aplicaciones e integraciones, especialmente los que surjan de la retroalimentación de los comerciantes.                                                                                                                                                     |
| Gestión de Requisitos            | Se realiza de forma continua: cada necesidad del comerciante o ajuste técnico se registra y se prioriza entre Daniel, Tomás y Bryan según su relación con la estrategia, la arquitectura y los principios definidos.                                                                                         |
