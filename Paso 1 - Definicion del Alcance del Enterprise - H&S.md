**Paso 1 -- Definición del Alcance del Enterprise**

Autores: Daniel Ignasio Fuentes Estrada, Tomas Alberto Arias Zabala y
Bryan Esteban Velilla Perez

**Información del Proyecto**

  -----------------------------------------------------------------------
  **Campo**                           **Detalle**
  ----------------------------------- -----------------------------------
  Nombre del proyecto                 Automatización de Agentes de
                                      Inteligencia Artificial en WhatsApp
                                      para el Comercio Local de Sincelejo

  Organización                        H&S Tecnología y Marketing S.A.S.

  Fecha                               2026

  Autor(es)                           Daniel Ignasio Fuentes Estrada,
                                      Tomas Alberto Arias Zabala y Bryan
                                      Esteban Velilla Perez
  -----------------------------------------------------------------------

**Core Enterprise Units**

Se entienden como Core Enterprise Units las unidades que crean
directamente el valor del servicio de H&S: el desarrollo del agente de
inteligencia artificial y su puesta en marcha para cada comerciante.

  -----------------------------------------------------------------------
  **Unidad**              **Descripción**         **Responsabilidad**
  ----------------------- ----------------------- -----------------------
  Dirección estratégica y Define la visión del    Asegurar que el
  desarrollo de negocio   servicio, la propuesta  producto avance según
                          de valor y las alianzas los objetivos y la
                          necesarias para llegar  estrategia definidos en
                          a los micronegocios de  el Taller #1.
                          Sincelejo.              

  Desarrollo y            Diseño, entrenamiento y Mantener funcionando la
  mantenimiento de        ajuste de los agentes   solución principal que
  agentes de IA           conversacionales según  se ofrece a los
                          el catálogo, el tono y  micronegocios.
                          las reglas de cada      
                          negocio.                

  Implementación e        Conectar el agente con  Facilitar una puesta en
  integración con         el canal que ya utiliza marcha sencilla y con
  WhatsApp                el comerciante          poca fricción para cada
                          (WhatsApp Business) y   nuevo cliente.
                          dejarlo operativo.      

  Soporte y atención al   Resolver dudas, fallos  Mantener la continuidad
  cliente                 y ajustes solicitados   del servicio y apoyar
                          por los comerciantes    la retención de
                          que usan el servicio.   clientes.
  -----------------------------------------------------------------------

**Soft Enterprise Units**

Las Soft Enterprise Units son funciones de apoyo que no generan el
producto en sí, pero que son necesarias para que la empresa capte
clientes, los conserve y opere de forma ordenada. En esta etapa inicial,
el equipo fundador las asumen de forma compartida.

  -----------------------------------------------------------------------
  **Unidad**              **Relación con el       **Impacto**
                          proyecto**              
  ----------------------- ----------------------- -----------------------
  Marketing digital       Ayuda a dar a conocer   Apoya la captación de
                          el servicio entre       clientes.
                          micronegocios de        
                          Sincelejo, aprovechando 
                          la experiencia de H&S   
                          en esta área.           

  Gestión comercial y     Busca clientes y        Facilita la llegada del
  alianzas                coordina relaciones con servicio a más
                          aliados. En la etapa    comerciantes sin
                          actual esta función la  agregar todavía un
                          cubre temporalmente el  cargo nuevo.
                          equipo fundador, ya que 
                          todavía no se cuenta    
                          con un asesor comercial 
                          contratado.             

  Gestión de clientes     Recoge necesidades,     Permite mejorar el
                          solicitudes y           servicio y conservar
                          comentarios de los      clientes.
                          comerciantes que ya     
                          usan el agente.         

  Administración y        Maneja la facturación   Sostiene la operación
  cumplimiento            básica, los términos de formal de la empresa y
                          servicio y el           su cumplimiento legal.
                          tratamiento de los      
                          datos de los clientes.  
  -----------------------------------------------------------------------

**Extended Enterprise**

El Extended Enterprise agrupa a los actores externos que, sin ser parte
de H&S, son necesarios para que la solución funcione o influyen
directamente en su operación. En este caso se toma como referencia la
documentación técnica de PROTO-SHA y las integraciones previstas para el
agente de IA.

  -----------------------------------------------------------------------
  **Actor**               **Tipo**                **Descripción**
  ----------------------- ----------------------- -----------------------
  Comerciante o           Cliente / usuario       Contrata el servicio y
  micronegocio                                    utiliza el agente para
                                                  atender a sus propios
                                                  clientes.

  Cliente final           Usuario del servicio    Persona que interactúa
                                                  con el agente por
                                                  WhatsApp para consultar
                                                  productos o hacer
                                                  pedidos.

  Meta / API de WhatsApp  Proveedor tecnológico   Permite que el agente
  Business                                        interactúe con los
                                                  clientes del negocio a
                                                  través del canal que ya
                                                  usan.

  Proveedor de            Proveedor tecnológico   Aloja el agente, sus
  infraestructura en la                           integraciones y la
  nube                                            información asociada al
                                                  servicio.

  Cámara de Comercio de   Socio o aliado          Pueden apoyar la
  Sincelejo / Nuevo                               divulgación y adopción
  Mercado                                         del servicio entre
                                                  comerciantes.

  Alternativas actuales   Sustituto / competencia WhatsApp manual, redes
  del comerciante         indirecta               sociales y chatbots
                                                  genéricos: la forma en
                                                  que hoy se resuelve, de
                                                  manera desordenada, el
                                                  mismo problema.

  Twilio                  Proveedor tecnológico   Servicio utilizado para
                                                  gestionar llamadas y la
                                                  integración de
                                                  comunicación con
                                                  WhatsApp.

  Gmail API               Proveedor tecnológico   Permite integrar el
                                                  correo electrónico al
                                                  sistema de atención
                                                  multicanal.

  Gemini / GPT API        Proveedor de IA         Motor externo utilizado
                                                  para analizar mensajes
                                                  y generar respuestas.

  n8n                     Proveedor / orquestador Coordina flujos entre
                                                  módulos, APIs y
                                                  servicios externos.

  AWS / infraestructura   Proveedor tecnológico   Servicios de
  cloud                                           infraestructura para
                                                  desplegar y escalar la
                                                  plataforma.
  -----------------------------------------------------------------------

**Stakeholders**

  -----------------------------------------------------------------------
  **Stakeholder**         **Rol**                 **Interés**
  ----------------------- ----------------------- -----------------------
  Equipo fundador de H&S: Directivos / equipo     Desarrollar, mantener,
  Daniel Fuentes, Tomas   interno                 gobernar y hacer crecer
  Arias y Bryan Velilla                           la solución desde sus
                                                  diferentes roles
                                                  fundadores.

  Comerciante o           Cliente                 Ahorrar tiempo y
  micronegocio                                    atender pedidos de
                                                  forma más organizada.

  Cliente final           Usuario del servicio    Recibir respuestas,
                                                  consultar productos y
                                                  hacer pedidos por
                                                  WhatsApp.

  Meta / proveedor de     Proveedor               Que el uso del agente
  WhatsApp Business API                           cumpla sus políticas de
                                                  mensajería y uso
                                                  comercial.

  Cámara de Comercio de   Aliado                  Que la propuesta apoye
  Sincelejo / Nuevo                               la formalización y
  Mercado                                         modernización del
                                                  comercio local.

  Entes reguladores (SIC, Regulador               Que la empresa cumpla
  DIAN)                                           la normativa de
                                                  protección de datos y
                                                  sus obligaciones
                                                  tributarias.

  Asesor comercial        Rol futuro / vacante    Apoyar la captación y
                                                  seguimiento de clientes
                                                  cuando el cargo sea
                                                  incorporado;
                                                  actualmente no hay
                                                  personal contratado
                                                  para esta función.
  -----------------------------------------------------------------------

**Contexto de Gobernanza**

  -----------------------------------------------------------------------
  **Marco o Regulación**              **Descripción**
  ----------------------------------- -----------------------------------
  Ley 1581 de 2012 y Decreto 1377 de  Regulan el tratamiento de datos
  2013 (Habeas Data)                  personales de comerciantes y
                                      clientes finales que interactúan
                                      con el agente.

  Ley 1273 de 2009 (delitos           Sirve de guía para definir los
  informáticos)                       controles de seguridad de acceso a
                                      las cuentas y configuraciones del
                                      servicio.

  Términos de uso de la API de        Establecen condiciones sobre el
  WhatsApp Business (Meta)            tipo de mensajes, tiempos de
                                      respuesta y uso comercial del
                                      canal, que el agente debe respetar.

  Ley 1258 de 2008 (S.A.S.) y normas  Rigen la constitución de H&S
  tributarias                         Tecnología y Marketing S.A.S. y sus
                                      obligaciones con la DIAN.

  Políticas internas de H&S           Tratamiento de datos, condiciones
                                      del servicio y reglas de uso del
                                      agente, definidas por el equipo
                                      fundador.
  -----------------------------------------------------------------------
