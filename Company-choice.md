#Yo escojo Brasaland por las siguientes razones:

1. El área de operaciones es la que más me interesa. Me gustaría crear un sistema de manejo de inventario que muestre no solo el inventario actual, sino también otros datos, como historiales de precios, y que mande alertas cuando el stock esté bajo. Hacer que todo ese sistema trabaje en conjunto se me hace muy interesante, al igual que conocer cómo la IA y la automatización pueden ayudar en esta área.

2. Otro aspecto que quiero aprender es cómo recopilar los datos de cada departamento: desde definir los requerimientos de cada área y diseñar los pipelines de datos, hasta ver todo funcionando en conjunto y llegar a los dashboards.

3. También me ha interesado mucho la integración de todos estos sistemas, desde inventario, compras y proveedores hasta marketing, para luego generar un reporte automático para el CEO de la empresa, o para que el mismo CEO pueda revisar el estado actual de cada departamento y ver sus métricas. Es algo que quiero aprender a diseñar y construir.

4. Creo que la capacidad de escalar un negocio es de suma importancia. Todas estas herramientas de integración, automatización e IA, junto con la estandarización de la información y los procesos, hacen que escalar sea mucho más fácil que hacerlo todo de manera manual y sin las herramientas adecuadas.

Las otras opciones me encantaron igualmente, pero la parte operativa y de obtención de datos de Brasaland me llamó más la atención por las aplicaciones que podría tener en sectores que me interesan.

##AI SUGGESTION

Estas son algunas ideas de agentes que se podrían implementar:

1. Agente de recetas y procedimientos (Recipe Knowledge Agent)
Responde preguntas del personal de cocina sobre recetas, procedimientos y estándares, usando RAG sobre la knowledge base de formación. Cita la fuente, responde en el idioma del usuario y escala a un humano cuando no hay información fiable o el tema es sensible (alérgenos).

2. Agente de onboarding (Onboarding Tutor Agent)
Guía al personal nuevo en su itinerario, aplica evaluaciones breves para detectar qué repasar, lleva el registro de su progreso y avisa al supervisor cuando completa una etapa o se atasca.

3. Agente de analítica departamental (Department Analytics Agent)
Asistente de lenguaje natural que recolecta métricas desde la API central y los pipelines, genera resúmenes por área y ofrece insights y recomendaciones con datos reales. Cada cifra indica su fuente y fecha, y cada jefe solo ve su área.

4. Agente ejecutivo (Executive Insights Agent)
Consolida los resúmenes del agente de analítica departamental en una visión global de la cadena (USD y COP), responde preguntas en lenguaje natural y envía el informe semanal cada lunes a las 7:00, con recomendaciones respaldadas por datos.

5. Agente de personalización y fidelización (Loyalty & Personalization Agent)
Dentro de la app de clientes, propone promociones personalizadas a partir del comportamiento y los loyalty points del cliente. Usa un catálogo de ofertas aprobado por Marketing, respeta el consentimiento de datos y limita la frecuencia de envíos.

6. Agente de soporte al cliente (nivel 1) (Customer Support Agent, Tier 1)
Resuelve consultas básicas y deriva a un humano los casos complejos o sensibles, con el historial de la conversación. Etiqueta los motivos de contacto para generar insights sobre el desempeño de la app.

Base común: el agente de recetas y el de onboarding comparten la misma knowledge base. El agente de analítica departamental y el agente ejecutivo comparten la API central, y este último se alimenta de los resúmenes del primero.
