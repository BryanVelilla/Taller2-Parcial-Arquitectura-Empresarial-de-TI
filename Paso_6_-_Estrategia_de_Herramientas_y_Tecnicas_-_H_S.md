Paso 6 – Estrategia de Herramientas y Técnicas

Autores: Daniel Ignasio Fuentes Estrada, Tomas Alberto Arias Zabala y Bryan Esteban Velilla Perez

Descripción

En esta etapa se define una estrategia de herramientas tomando como referencia la documentación técnica de PROTO-SHA. Se priorizan las tecnologías que ya forman parte del proyecto o que son necesarias para documentar y representar su arquitectura, evitando agregar herramientas de colaboración que no aparecen en la documentación del sistema.

Herramientas Seleccionadas

| **Tipo de Herramienta**              | **Herramienta**             | **Uso en el Proyecto**                                                                                               |
|--------------------------------------|-----------------------------|----------------------------------------------------------------------------------------------------------------------|
| Modelado de arquitectura empresarial | Archi (ArchiMate 3.x)       | Representar capacidades, procesos, aplicaciones y relaciones de arquitectura.                                        |
| Diagramación técnica                 | Draw.io / Diagrams.net      | Elaborar diagramas de arquitectura, procesos, integraciones y flujos.                                                |
| Backend y APIs                       | Node.js / NestJS            | Desarrollar el núcleo del sistema, casos de uso y APIs del agente.                                                   |
| Persistencia de datos                | TypeORM + MySQL Workbench   | Gestionar la capa de persistencia y apoyar el diseño y normalización de la base de datos documentada en el proyecto. |
| Motor de Inteligencia Artificial     | Gemini / GPT API            | Analizar mensajes y generar respuestas automáticas.                                                                  |
| Orquestación de flujos               | n8n (auto-hosted)           | Coordinar los flujos entre módulos, APIs y servicios externos.                                                       |
| Integraciones de comunicación        | Twilio + Gmail API          | Gestionar llamadas/WhatsApp y automatización del correo electrónico.                                                 |
| Frontend                             | React + Tailwind            | Construir el panel web para administración, monitoreo y configuración.                                               |
| Despliegue e infraestructura         | Docker + AWS (EC2, RDS, S3) | Contenerizar y desplegar los componentes de la plataforma y preparar su escalabilidad.                               |

Estrategia de Implementación

| **Actividad**                     | **Herramienta**                    | **Descripción**                                                                    |
|-----------------------------------|------------------------------------|------------------------------------------------------------------------------------|
| Modelado de arquitectura          | Archi                              | Construir modelos sencillos de capacidades, procesos, aplicaciones y tecnología.   |
| Diagramación técnica              | Draw.io / Diagrams.net             | Representar el flujo general y las integraciones de PROTO-SHA.                     |
| Desarrollo backend                | NestJS / Node.js                   | Implementar módulos, APIs y casos de uso del sistema.                              |
| Persistencia                      | TypeORM + base de datos relacional | Gestionar entidades como usuarios, conversaciones, mensajes, logs e integraciones. |
| IA y procesamiento conversacional | Gemini / GPT API                   | Procesar mensajes y producir respuestas según el conocimiento configurado.         |
| Orquestación                      | n8n                                | Coordinar automatizaciones entre los distintos módulos y servicios.                |
| Integraciones                     | Twilio / Gmail API                 | Conectar canales externos y manejar eventos mediante APIs y webhooks.              |
| Despliegue                        | Docker / AWS                       | Preparar el entorno de ejecución y la futura evolución hacia SaaS.                 |
| Panel administrativo              | React + Tailwind                   | Gestionar la interfaz web de monitoreo y configuración.                            |

Control de Artefactos de Arquitectura

| **Elemento**            | **Descripción**                                                                                                                              |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Control de versiones    | Mantener un historial de cambios en los documentos y artefactos de arquitectura del proyecto.                                                |
| Gestión de acceso       | Definir quién puede consultar o modificar documentos y modelos de arquitectura según el rol de cada founder.                                 |
| Trazabilidad de cambios | Registrar modificaciones importantes en modelos, procesos e integraciones.                                                                   |
| Revisión periódica      | Revisar los artefactos durante las fases del trabajo y cuando cambien los módulos, integraciones o tecnologías de PROTO-SHA.                 |
| Nombres de archivos     | Usar un formato consistente que identifique fase, tipo de artefacto, nombre y versión; por ejemplo EA-B-PROC-atencion-pedidos-v1.0.          |
| Aprobación de cambios   | Los cambios relevantes se revisan entre los tres founders: Daniel desde el negocio, Tomás desde el desarrollo y Bryan desde la arquitectura. |
