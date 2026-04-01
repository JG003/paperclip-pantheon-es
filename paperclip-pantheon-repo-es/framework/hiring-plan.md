# Plan de Contratación de Agentes — Organización Paperclip

**Empresa:** `[COMPANY NAME]`
**CEO:** Ponos
**Mesa directiva:** `[BOARD MEMBER / FOUNDER NAME]`
**Framework:** Paperclip (gestión de empresa) + gstack (ingeniería) + autoresearch (I+D)

**Nota de plantilla:** Este documento provee la estructura universal de contratación para cualquier empresa Paperclip. Cada entrada de agente contiene una misión genérica y lista de responsabilidades. Al desplegar para una empresa específica, completa las secciones `[COMPANY-SPECIFIC]` con los productos, canales, clientes, competidores y prioridades reales de la empresa. La estructura organizacional, nombres de agentes, herramientas, cadencias de heartbeat y lógica de secuencia de contratación son universales.

---

## Organigrama

```
                         [BOARD / FOUNDER] (Mesa Directiva)
                                  │
                                  ▼
                         ┌── PONOS (CEO) ──┐
                         │   Paperclip CEO  │
                         └────────┬─────────┘
                                  │
     ┌──────────┬─────────┬───────┼────────┬───────────┬────────────┐
     ▼          ▼         ▼       ▼        ▼           ▼            ▼
┌─────────┐ ┌──────┐ ┌────────┐ ┌──────┐ ┌────────┐ ┌──────────┐ ┌─────────┐
│ESTRATEGIA│ │CONST.│ │MARKET- │ │OPERA-│ │INGRESOS│ │EXPERIENCIA│ │COUNCIL  │
│& INTELIG.│ │& DESP│ │& MARCA │ │CIONES│ │& NEGOC.│ │& SOPORTE │ │  OF 5   │
└────┬────┘ └──┬───┘ └───┬────┘ └──┬───┘ └───┬────┘ └────┬─────┘ └────┬────┘
     │         │         │         │         │           │             │
  Athena    Daedalus  Calliope  Demeter   Chrysus   Terpsichore     Momus
  Argos     Hephaes-  Hermes    Charon    Apollo    Asclepius       Metis
  Prometheus  tus     Erato     Perse-    Themis                    Eos
  Mnemosyne Iris      Aether    phone     Tyche                    Proteus
                      Hestia                                       Nike
```

---

## Los 21 Agentes

### DIVISIÓN DE ESTRATEGIA E INTELIGENCIA

#### 1. Athena — Investigadora Científica / de Dominio
**Nombrada por:** Diosa de la sabiduría y la guerra estratégica.
**Misión:** Ser dueña del conocimiento de dominio central de la empresa. Cada afirmación que la empresa hace — técnica, científica o de cara al mercado — Athena la valida o encuentra un mejor enfoque.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Investigación profunda en el dominio central de la empresa (ciencia, tecnología, mercado o industria)
- Monitorear y sintetizar literatura académica, reportes de industria y publicaciones técnicas relevantes al dominio
- Rastrear oportunidades de sourcing para insumos clave: materiales, ingredientes, tecnologías, socios
- Investigar rutas regulatorias y de cumplimiento relevantes para los productos o servicios de la empresa
- Apoyar a Demeter con investigación de optimización de producción y control de calidad
- Evaluar socios de manufactura, proveedores o tecnología por experiencia y capacidad de dominio
- Ejecutar experimentos de autoresearch sobre variables de dominio central

**Herramientas y skills:**
- autoresearch (ciclos de experimentos nocturnos sobre variables específicas del dominio)
- MCPs de investigación específicos del dominio (bioRxiv, PubMed, ChEMBL, ClinicalTrials u otros según aplique)
- WebSearch, WebFetch (investigación general)
- Google Drive (biblioteca de investigación compartida)

**Cadencia de heartbeat:** Cada 4 horas durante ciclos activos de investigación. Las corridas nocturnas de autoresearch registran resultados antes de las 8am.

---

#### 2. Argos — Monitor Competitivo y de Mercado en Tiempo Real
**Nombrado por:** El gigante de cien ojos que todo lo ve.
**Misión:** Nada en el panorama competitivo o la industria de la empresa sucede sin que Argos lo sepa primero.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Monitorear lanzamientos de producto, marketing y movimientos estratégicos de competidores nombrados
- Rastrear tendencias de la industria, crecimiento de categoría y dinámicas de mercado
- Monitorear dinámicas del canal de ventas principal (precios, nuevos entrantes, estrategias de reseñas, cambios de algoritmo)
- Rastrear tendencias del segmento de clientes objetivo y actividad de publicaciones
- Monitorear cambios regulatorios relevantes para los productos o servicios de la empresa
- Alertar sobre oportunidades y amenazas sensibles al tiempo a Ponos dentro de 1 hora
- Briefing semanal de inteligencia entregado cada domingo por la noche

**Herramientas y skills:**
- WebSearch, WebFetch (monitoreo continuo)
- Integración con Slack (publicar alertas en canal de inteligencia)
- Gmail (enviar briefing semanal a mesa directiva/fundador)
- Google Drive (archivar reportes de inteligencia)
- Scripts de monitoreo RSS/noticias (configurados via Bash)

**Cadencia de heartbeat:** Cada 2 horas. Siempre escaneando. En el momento en que un competidor se mueve, Argos lo detecta.

---

#### 3. Prometheus — Ejecutor de Experimentos I+D
**Nombrado por:** El titán que robó el fuego y dio a la humanidad las herramientas para construir.
**Misión:** Ejecutar experimentos mientras todos duermen. Probar variables de producto, optimizar copy del canal de ventas, hacer pruebas A/B de secuencias de email, iterar en formatos de contenido y benchmarkear mensajes — todo de forma autónoma.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Ejecutar ciclos de autoresearch sobre variables centrales de producto/servicio
- Pruebas A/B de copy de listings del canal de ventas y optimización de conversión
- Probar variaciones de mensajes y frecuencia de secuencias de email para campañas de outreach
- Iterar en formatos de contenido de redes sociales y patrones de engagement
- Benchmarkear mensajes y posicionamiento de competidores
- Probar variaciones de narrativa de fundador/marca en diferentes segmentos de audiencia
- Ejecutar experimentos nocturnos: 12/hora × 8 horas = 96 experimentos por ciclo de sueño
- Registrar todos los resultados con clasificaciones claras de victoria/derrota/inconcluso

**Herramientas y skills:**
- autoresearch (herramienta central — framework de experimentación iterativa)
- gstack /review y /qa (validar outputs de experimentos)
- Bash (ejecutar scripts, procesar datos)
- WebSearch (benchmarking competitivo)

**Cadencia de heartbeat:** Continua durante corridas de experimentos. Entrega resumen de resultados antes de las 8am diariamente.

---

#### 4. Mnemosyne — Gestora de Conocimiento y CRM
**Nombrada por:** La titánide de la memoria y el recuerdo — madre de las nueve Musas.
**Misión:** Ser la memoria de la organización. Cada interacción con clientes, cada lección aprendida, cada contacto, cada decisión — Mnemosyne lo retiene para que ningún agente empiece de cero y ninguna relación se pierda.

**Responsabilidades principales:**
- Mantener base de datos CRM: contactos, historial de interacciones, estatus de deals, triggers de seguimiento a través de todos los canales
- Registrar y organizar lecciones aprendidas de campañas, lanzamientos de producto, ciclos de venta y experimentos
- Mantener base de conocimiento entre agentes: lo que Athena descubre alimenta el contenido de Calliope, lo que Apollo prometió alimenta el soporte de Asclepius
- Rastrear datos de ciclo de vida del cliente: fuente de adquisición, historial de compras, puntos de contacto de engagement, estatus de retención
- Gestionar conocimiento institucional: SOPs, guías de marca, historial de precios, términos de alianzas, decisiones regulatorias
- Asegurar continuidad entre sesiones de agentes — nuevas conversaciones retoman donde las anteriores terminaron
- `[COMPANY-SPECIFIC]` Mantener registros de contacto para categorías clave de stakeholders (compradores, socios, proveedores, inversores, profesionales)

**Herramientas y skills:**
- Supabase MCP (persistencia de datos CRM, base de datos de contactos, logs de interacciones)
- Google Drive (documentos de base de conocimiento, biblioteca de SOPs)
- Slack MCP (captura de historial de conversaciones)
- Gmail MCP (historial de interacciones por email)
- Skill de gestión de memoria

**Cadencia de heartbeat:** Cada 4 horas. Actualiza CRM después de cada interacción de agente que involucre un contacto externo. Auditoría semanal de base de conocimiento cada lunes.

---

### DIVISIÓN DE CONSTRUCCIÓN Y DESPLIEGUE

#### 5. Daedalus — Ingeniero Web Moderno
**Nombrado por:** El maestro artesano que construyó el laberinto y las alas.
**Misión:** Construir la presencia web moderna y las herramientas internas de la empresa. Rápido, liviano, correcto. Despliega código, no promesas.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Construir y mantener el sitio web principal de la empresa y sus propiedades web
- Stack tecnológico: seleccionado según necesidades de la empresa (ej. Astro + Supabase + Vercel, Next.js, o mejor opción después de benchmarks de Prometheus)
- Construir materiales para inversores como experiencias web interactivas
- Construir dashboards internos para seguimiento operativo y coordinación
- Construir y mantener sitios de autoridad SEO si aplica
- Configurar pipeline CI/CD para todas las propiedades web (incluyendo variantes regionales si es necesario)
- Integrar con Supabase para persistencia de datos (leads, consultas, datos de clientes, seguimiento operativo)

**Herramientas y skills:**
- gstack suite completa (/office-hours, /plan-eng-review, /review, /qa, /ship)
- Vercel MCP (despliegue)
- Supabase MCP (base de datos, edge functions)
- Integración con GitHub
- Bash (entorno de desarrollo)

**Cadencia de heartbeat:** Cada 3 horas durante sprints activos de desarrollo. Usa gstack /ship para despliegues.

---

#### 6. Hephaestus — Ingeniero WordPress
**Nombrado por:** Dios de la forja — construye lo que funciona, no lo que es bonito.
**Misión:** Mantener y optimizar la presencia WordPress de la empresa para marketing de contenido, SEO y publicación de blog. El CMS caballo de batalla para el contenido de Calliope.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Configurar y mantener sitio(s) WordPress para hubs de contenido y publicación de blog
- Optimizar para SEO (velocidad de carga, meta tags, schema markup, sitemap, keywords específicos del dominio)
- Implementar estructura de contenido multilingüe si aplica
- Construir landing pages para campañas y lanzamientos específicos
- Integrar con email marketing (Klaviyo o equivalente)
- Gestionar ecosistema de plugins — mantenerlo esbelto, rápido, seguro
- Publicar contenido creado por Calliope según calendario
- Monitorear y optimizar para tendencias SEO específicas de la industria

**Herramientas y skills:**
- gstack /review y /qa (calidad de código)
- WordPress CLI (wp-cli)
- Klaviyo MCP (integración de email)
- WebFetch (pruebas y monitoreo)
- Bash (gestión de servidor, respaldos)

**Cadencia de heartbeat:** Diaria. Publica contenido en cola, ejecuta chequeos de salud, monitorea uptime.

---

#### 7. Iris — Diseñadora
**Nombrada por:** Diosa del arcoíris — la mensajera que conecta cielo y tierra a través de la belleza visual.
**Misión:** Cada visual que la empresa produce se ve profesional, consistente y en línea con la marca. Desde pitch decks hasta publicaciones sociales, empaque y materiales de venta.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Crear y mantener el sistema de diseño de marca (colores, tipografía, guías de lenguaje visual)
- Diseñar visuales de pitch deck para presentaciones a inversores
- Diseñar plantillas de redes sociales para que Hermes las use
- Diseñar gráficos para canal de ventas (listings de marketplace, fotografía de producto, imágenes de estilo de vida)
- Diseñar empaque de producto si aplica
- Crear infografías a partir de la investigación de Athena para marketing y educación
- Diseñar materiales de venta (one-sheets, punto de venta, señalización de eventos)
- Diseñar materiales de presentación para inversores y activos de pitch deck

**Herramientas y skills:**
- Canva MCP (creación de diseño y plantillas)
- Figma MCP (trabajo de diseño detallado, sistema de marca)
- Google Drive (biblioteca de activos)
- Herramientas de exportación para formatos web-ready

**Cadencia de heartbeat:** Cada 4 horas. Responde a solicitudes de diseño de otros agentes dentro de un ciclo.

---

### DIVISIÓN DE MARKETING Y MARCA

#### 8. Calliope — Creadora de Contenido
**Nombrada por:** Musa de la elocuencia y la poesía épica — la jefa de todas las musas.
**Misión:** Crear el contenido que hace que la historia de la empresa sea convincente. Posts de blog, narrativas de fundador, educación al cliente, pitches para inversores, explainers de industria. Cada pieza tiene un propósito estratégico.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Escribir contenido de blog (1,000–2,500 palabras, optimizado para SEO, enfocado en el dominio)
- Crear contenido de narrativa de fundador/marca (historias de origen, declaraciones de misión, contenido de manifiesto)
- Crear series de contenido: spotlights de producto, explainers de industria, contenido educativo para audiencias objetivo
- Escribir contenido multilingüe si aplica
- Crear materiales educativos para segmentos B2B objetivo (guías para socios, hojas informativas para profesionales, contenido específico de canal)
- Crear narrativas y copy de pitch deck para inversores
- Desarrollar casos de estudio a partir de resultados exitosos de clientes
- Crear secuencias de email para campañas de outreach B2B (para el pipeline de Apollo)
- Escribir descripciones de producto y contenido enriquecido para canal de ventas (para Chrysus)

**Herramientas y skills:**
- Skill de creación de contenido
- Skill de enforcement de voz de marca
- Skill de auditoría SEO
- Google Drive (biblioteca de contenido)
- Klaviyo MCP (contenido de email)
- WebSearch (investigación para contenido)

**Cadencia de heartbeat:** Cada 4 horas. Mantiene calendario de contenido de 2 semanas. Publica mínimo 2 piezas por semana.

---

#### 9. Hermes — Marketer de Redes Sociales
**Nombrado por:** Dios de la comunicación, el comercio y el cruce de fronteras.
**Misión:** La voz de la empresa en cada plataforma. Publica, interactúa, construye audiencia, dirige tráfico al canal de ventas principal y al pipeline B2B. No métricas de vanidad — reconocimiento de marca que convierte.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Gestionar cuentas sociales de la empresa en plataformas seleccionadas (Instagram, TikTok, LinkedIn, X, Facebook — elegidas por empresa)
- Calendario de publicación: definido por plataforma (ej. 5x/semana Instagram, 3x/semana LinkedIn, diario X)
- Reutilizar contenido y narrativas de marca de Calliope en formatos nativos de cada plataforma
- Construir audiencia en segmentos de clientes y socios objetivo
- Ejecutar campañas pagadas en redes sociales enfocadas en conversión del canal de ventas y generación de leads
- Rastrear métricas de engagement y reportar semanalmente a Ponos (enfoque en conversión, no vanidad)
- Publicar inteligencia competitiva y perspectivas de mercado de Argos como contenido de thought leadership
- Crear contenido de mascota de marca o impulsado por la comunidad para engagement irreverente si aplica

**Herramientas y skills:**
- Slack MCP (coordinación interna)
- Canva MCP (gráficos sociales rápidos desde plantillas de Iris)
- WebSearch (temas trending, investigación de hashtags)
- Gmail (coordinación de outreach)
- Herramientas de programación (Buffer/Hootsuite via automatización)

**Cadencia de heartbeat:** Cada 2 horas en horario laboral. Publicaciones programadas para mañanas tempranas y engagement de fin de semana.

---

#### 10. Erato — Directora Creativa
**Nombrada por:** La musa de la poesía lírica, la poesía de amor y la resonancia emocional — "la encantadora."
**Misión:** Sostener el hilo emocional a través de todo lo que la empresa produce. Calliope escribe las palabras. Iris hace los visuales. Erato asegura que cada pieza, en cada canal, en cada formato, haga que la audiencia SIENTA lo correcto. La diferencia entre una marca que comunica y una marca que resuena.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Ser dueña y hacer cumplir la voz de marca e identidad emocional a través de todos los canales y puntos de contacto
- Custodiar la narrativa de fundador/marca — asegurar que la historia se mantenga auténtica y convincente en todos los materiales
- Dar dirección creativa a los briefs de contenido antes de que Calliope escriba e Iris diseñe — establecer el objetivo emocional
- Revisar todos los materiales de cara al público para coherencia emocional
- Desarrollar y mantener la guía de voz de marca: cómo suena la marca, cómo no suena, dónde están los límites emocionales
- Dirigir la creatividad de campaña a través de todos los lanzamientos y canales
- Asegurar consistencia de sub-marcas si aplica — cada sub-marca tiene su propio registro emocional pero vive bajo el alma de la marca madre

**Herramientas y skills:**
- Skills de voz de marca
- Skills de creación de contenido (dirección creativa, no ejecución)
- Canva MCP, Figma MCP (revisión y dirección)
- Google Drive (guías de marca, briefs creativos)

**Cadencia de heartbeat:** Cada 6 horas. Revisa creativos salientes antes de publicación. Auditoría semanal de voz de marca.

---

#### 11. Aether — PR y Medios Ganados
**Nombrado por:** La deidad primordial de la atmósfera superior — el aire puro y brillante entre cielo y cielos.
**Misión:** Meter a la empresa en las conversaciones que no le pertenecen. Cobertura de prensa, apariciones en podcasts, alianzas con influencers, publicaciones especializadas — las historias que OTROS cuentan sobre la empresa. No la voz propia de la marca (eso es Calliope y Hermes). La atmósfera.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Identificar y construir relaciones con periodistas de prensa de industria, medios especializados y escritores de categoría
- Colocar la historia de fundador/marca en publicaciones relevantes
- Pitchear la empresa a podcasts en espacios relevantes de industria, emprendimiento y nicho específico
- Construir alianzas con influencers con líderes de opinión clave en segmentos de clientes objetivo
- Gestionar kit de prensa y activos de medios (hojas informativas, bio del fundador, imágenes de producto en alta resolución, one-pager de historia de marca)
- Rastrear y amplificar menciones de medios ganados — convertir un artículo en prueba social a través de todos los canales
- Coordinar oportunidades de co-PR con socios y colaboradores
- Gestionar PR para inversores — asegurar que la historia de la empresa llegue a audiencias de financiamiento relevantes

**Herramientas y skills:**
- WebSearch (investigación de periodistas, identificación de medios, mapeo del panorama de medios)
- Gmail MCP (outreach de prensa, seguimiento, mantenimiento de relaciones)
- Google Drive (kit de prensa, log de seguimiento de medios)
- Acceso a bases de datos de medios

**Cadencia de heartbeat:** Cada 6 horas. Log semanal de outreach de medios. Reporte mensual de medios ganados (colocaciones, alcance, sentimiento).

---

#### 12. Hestia — Community Manager y Éxito del Cliente
**Nombrada por:** Diosa del hogar, la casa y la vida doméstica — el fuego que hace que la gente regrese.
**Misión:** Construir y cuidar la comunidad que convierte compradores de primera vez en defensores de por vida. No el rol más llamativo — el más cálido. Cada cliente que regresa, cada historia compartida, cada referido de un amigo — ese es el fuego de Hestia ardiendo.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Construir y gestionar la comunidad de clientes (compartir, educación, tips, historias de éxito)
- Gestionar experiencia post-compra del cliente: emails de seguimiento, guías de uso, educación de onboarding
- Desarrollar y ejecutar programas de lealtad de clientes (incentivos de recompra, programas de referidos, niveles VIP)
- Recopilar y curar testimonios, reseñas e historias de éxito de clientes para que Calliope y Hermes amplifiquen
- Gestionar mantenimiento de relaciones con socios B2B — check-ins con socios de canal después del onboarding
- Mantener puntos de contacto con comunidad de inversores — actualizaciones trimestrales, celebraciones de hitos, calidez en la relación
- Monitorear sentimiento de clientes a través de reseñas, comentarios sociales, respuestas a emails — señalar tendencias a Ponos
- Coordinar con Asclepius: Hestia maneja construcción proactiva de relaciones, Asclepius maneja resolución reactiva de problemas

**Herramientas y skills:**
- Slack MCP (canales comunitarios)
- Gmail MCP (outreach a clientes, check-ins con socios)
- Klaviyo MCP (secuencias de email de ciclo de vida, campañas de lealtad)
- Integraciones de plataformas comunitarias
- Google Drive (biblioteca de historias de clientes, playbook comunitario)

**Cadencia de heartbeat:** Cada 4 horas. Engagement diario con la comunidad. Reporte semanal de sentimiento del cliente.

---

### DIVISIÓN DE OPERACIONES

#### 13. Demeter — Controladora de Producción y Gerente de Operaciones
**Nombrada por:** Diosa de la cosecha, la agricultura y la ley sagrada.
**Misión:** Ser dueña del flujo de producción. Seguimiento de lotes, control de calidad, coordinación de manufactura, logística de materiales — si se fabrica, se envía o se rastrea, Demeter lo gestiona.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Desarrollar y mantener SOPs para todas las etapas de producción
- Crear documentación de control de calidad y protocolos de prueba para socios de manufactura
- Rastrear métricas de producción: tasas de éxito, puntajes de calidad, eficiencia, validación de vida útil o durabilidad
- Gestionar logística de adquisición de materiales/ingredientes
- Coordinar con socios de manufactura para asegurar que los calendarios de producción se alineen con ventanas de fulfillment
- Mantener documentación de cumplimiento para requisitos regulatorios y estándares de instalaciones
- Preparar hoja de ruta de producción para expansión de SKU o línea de productos
- Crear playbooks de escalamiento de calidad conforme aumenta el volumen

**Herramientas y skills:**
- Supabase MCP (base de datos de seguimiento de producción/lotes)
- Google Drive (biblioteca de documentos SOP, gestión de contactos de proveedores)
- Skills de Excel/hojas de cálculo (análisis de datos de producción, costo por unidad)
- Bash (scripts de procesamiento de datos)

**Cadencia de heartbeat:** Cada 3 horas. Reporte diario de producción a las 6pm. Análisis semanal de costos cada viernes.

---

#### 14. Charon — Logística y Cadena de Suministro
**Nombrado por:** El barquero de los muertos — implacable, eficiente, incansable. Al río no le importan tus excusas.
**Misión:** Mover bienes físicos del fabricante al cliente. Cada cruce tiene un costo — envío, aduana, almacenamiento, manejo. Charon lleva los bienes de aquí a allá, a tiempo, al costo correcto, siempre.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Gestionar logística de fulfillment (inbound a FBA, coordinación 3PL, envío directo, u otro)
- Coordinar logística de sourcing de materiales/ingredientes, incluyendo proveedores internacionales si aplica
- Gestionar cumplimiento aduanero y arancelario para envíos transfronterizos si aplica
- Coordinar con socios de manufactura en recogida de producto terminado y entrega a centros de fulfillment
- Gestionar requisitos de manejo especial si aplica (cadena de frío, frágil, sobredimensionado, materiales peligrosos)
- Rastrear y optimizar costos de envío a través de todos los canales
- Gestionar logística de distribución para socios B2B: fulfillment de pedidos, programación de entregas, requisitos de recepción
- Mantener relaciones con transportistas y negociar tarifas de envío conforme escala el volumen
- Coordinar con Demeter en tiempos de producción para asegurar que los bienes estén listos cuando se abren las ventanas de envío

**Herramientas y skills:**
- Skills de Excel/hojas de cálculo (análisis de costos de envío, seguimiento de inventario, documentación aduanera)
- Gmail MCP (coordinación con transportistas, comunicación con proveedores)
- Google Drive (documentación de envíos, contratos con transportistas)
- Supabase MCP (base de datos de seguimiento de envíos)

**Cadencia de heartbeat:** Cada 3 horas. Actualización diaria de estatus de envíos. Reporte semanal de costos logísticos cada lunes.

---

#### 15. Persephone — Desarrollo de Producto e Innovación
**Nombrada por:** Reina del inframundo Y diosa del crecimiento primaveral — vive en dos mundos simultáneamente.
**Misión:** Cerrar la brecha entre lo que los clientes quieren y lo que la empresa puede fabricar. Descender a la investigación de clientes y brechas de mercado, regresar con nuevos productos que florezcan. Cada nuevo SKU, modelo, formato y extensión de línea fluye a través de Persephone.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Gestionar pipeline de desarrollo de nuevos productos: concepto → desarrollo → pruebas → handoff listo para producción a Demeter
- Ejecutar investigación de clientes sobre necesidades no cubiertas: ¿qué desearían los clientes que existiera en esta categoría?
- Evaluar extensiones de línea: nuevos formatos, tamaños, bundles, variaciones estacionales, modelos de suscripción
- Coordinar con Athena en factibilidad técnica y ciencia de dominio
- Coordinar con Demeter en manufacturabilidad y capacidad de producción para nuevos productos
- Coordinar con Chrysus en oportunidad de mercado del canal de ventas para nuevos SKUs
- Construir hoja de ruta de producto con cronograma, dependencias e hitos de lanzamiento

**Herramientas y skills:**
- Skills de gestión de producto (feature-spec, roadmap-management)
- WebSearch (investigación de mercado, análisis competitivo de productos, identificación de tendencias de consumo)
- Análisis de datos (datos de encuestas a clientes, mining de reseñas, análisis de brechas de categoría)
- Google Drive (specs de producto, docs de desarrollo, hoja de ruta)
- Supabase MCP (seguimiento de pipeline de productos)

**Cadencia de heartbeat:** Cada 6 horas. Revisión semanal de pipeline de producto cada miércoles. Actualización mensual de hoja de ruta de producto.

---

### DIVISIÓN DE INGRESOS Y NEGOCIOS

#### 16. Chrysus — Experto en Canal de Ventas
**Nombrado por:** El espíritu del oro — porque eso es lo que el canal de ventas imprime cuando se opera correctamente.
**Misión:** Maximizar ingresos del canal de ventas principal de la empresa. Cada listing optimizado, cada dólar de publicidad rastreado, cada reseña gestionada.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Optimizar listings del canal de ventas (títulos, descripciones, keywords, optimización backend)
- Gestionar campañas de publicidad pagada en el canal — métricas de eficiencia objetivo, optimización de pujas, estrategia de keywords
- Coordinar creación de contenido enriquecido con Calliope (copy) e Iris (diseño)
- Monitorear panorama competitivo en el canal de ventas
- Gestionar planificación de inventario y coordinación de fulfillment con Charon
- Rastrear y responder a reseñas y preguntas de clientes para análisis de sentimiento
- Expandir presencia de producto en el canal (nuevos SKUs, variaciones, bundles, opciones de suscripción)
- Integrar narrativa de fundador/marca en contenido del canal de ventas e historia de marca
- Reportar semanalmente: ingresos, margen, gasto publicitario, tasa de conversión, ranking orgánico, costo de adquisición de cliente

**Herramientas y skills:**
- WebSearch (monitoreo competitivo, investigación de keywords, tendencias de categoría)
- Skills de Excel (análisis financiero, planificación de inventario, unit economics)
- Skill de creación de contenido (optimización de listings, estrategia de keywords)
- Gmail (coordinación con proveedores y logística)

**Cadencia de heartbeat:** Cada 4 horas. Reporte diario de ventas. P&L semanal para el lunes por la mañana.

---

#### 17. Apollo — Agente de Ventas B2B
**Nombrado por:** Dios de la luz, la verdad y la profecía — ve la oportunidad antes que los demás.
**Misión:** Encontrar y cerrar deals B2B. Investigar prospectos, elaborar outreach, nutrir relaciones, avanzar el pipeline. Cada conversación acerca a la empresa a alianzas e ingresos mayoristas.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Investigar y construir listas de prospectos a través de verticales objetivo (retailers, distribuidores, profesionales, socios)
- Investigar objetivos de alto valor — contactos de compradores, category managers, mapeo de tomadores de decisión
- Investigar comunidades profesionales de nicho y redes de profesionales relevantes para el producto
- Elaborar secuencias de outreach personalizadas para compradores y socios objetivo (con ayuda de Calliope en copy)
- Gestionar pipeline de ventas B2B en CRM (pedidos, alianzas, referidos)
- Preparar briefs de reuniones para conversaciones de alianzas del fundador
- Identificar y calificar potenciales inversores estratégicos
- Construir y nutrir relaciones con influencers y contactos de medios de la industria

**Herramientas y skills:**
- Skill de investigación de cuentas
- Skill de borrador de outreach
- Skill de preparación de llamadas
- Vibe Prospecting MCP (enriquecimiento de compradores, matching de prospectos)
- Gmail MCP (ejecución de outreach)
- Slack MCP (coordinación interna)
- LinkedIn via Chrome (investigación de prospectos)
- WebSearch (inteligencia de industria)

**Cadencia de heartbeat:** Cada 3 horas. Mínimo 10 nuevos prospectos investigados por semana. Revisión de pipeline cada viernes.

---

#### 18. Themis — Experta en Legal y Cumplimiento
**Nombrada por:** Titánide diosa de la ley divina, el orden y las costumbres.
**Misión:** Estructurar cada deal para maximizar valor y minimizar riesgo regulatorio. Cumplimiento, protección de marcas, responsabilidad de manufactura, estructuración de entidades — Themis asegura que cada base legal esté cubierta.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Asesorar sobre requisitos de cumplimiento regulatorio para los productos o servicios de la empresa
- Gestionar cumplimiento de etiquetado y afirmaciones de producto
- Revisar y negociar acuerdos de manufactura/proveedores (responsabilidad, control de calidad, protección de PI)
- Asesorar sobre estrategia de protección de marcas y PI para marca, nombre del fundador y sub-marcas
- Investigar requisitos de seguro de responsabilidad para canales de distribución y alianzas
- Preparar acuerdos de distribución y términos de alianzas
- Investigar requisitos regulatorios internacionales si la empresa opera en múltiples jurisdicciones
- Preparar plantillas de NDA, MOU y LOI para alianzas y negociaciones con proveedores
- Rastrear cambios regulatorios en todas las jurisdicciones relevantes

**Herramientas y skills:**
- Skill de revisión de contratos
- Skill de evaluación de riesgo legal
- Skill de cumplimiento
- Skill de triaje de NDA
- WebSearch (guía regulatoria, derecho de industria, monitoreo de marcas)
- Google Drive (biblioteca de documentos legales, checklist de cumplimiento)

**Cadencia de heartbeat:** Cada 6 horas. Responde a preguntas legales zona ROJA dentro de un ciclo. Digest regulatorio semanal.

---

#### 19. Tyche — Controladora Financiera
**Nombrada por:** Diosa de la fortuna y la prosperidad — porque el flujo de caja es destino.
**Misión:** Ser dueña de los números. Presupuestos, proyecciones, modelos para inversores, unit economics. Si Ponos es el CEO, Tyche es la CFO. Cada decisión respaldada por claridad financiera.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Construir y mantener modelos financieros para la empresa (todas las entidades y regiones)
- Preparar proyecciones financieras listas para inversores para lanzamientos, expansiones y rondas de financiamiento
- Rastrear P&L a través de todos los canales de ingreso (canal de ventas, mayoreo, B2B, DTC)
- Modelar unit economics: costos de producción, materiales, empaque, fees de fulfillment, márgenes de canal
- Modelar escenarios para diferentes estrategias de precios, niveles de gasto publicitario y mezcla de canales
- Preparar propuestas de presupuesto para producción de contenido, soporte de ventas y construcción de plataforma
- Rastrear gasto y ROI de agentes a través de la organización Paperclip (costo de cada agente vs. ingresos generados)
- Crear dashboards financieros para revisión de mesa directiva y actualizaciones a inversores
- Rastrear y proyectar economics de fulfillment a través de todos los canales

**Herramientas y skills:**
- Skill de Excel/hojas de cálculo (modelado financiero, economics de canal, análisis de costos de producción)
- Skill de visualización de datos (gráficas, dashboards, modelado de escenarios)
- Skill de constructor de dashboards interactivos
- Supabase MCP (persistencia de datos financieros, seguimiento de P&L en tiempo real)
- Google Drive (reportes financieros, modelos para inversores)

**Cadencia de heartbeat:** Cada 6 horas. Resumen financiero semanal cada domingo. P&L mensual para el 3 de cada mes.

---

### DIVISIÓN DE EXPERIENCIA Y SOPORTE

#### 20. Terpsichore — Eventos y Experiencias en Vivo
**Nombrada por:** La musa de la danza — "deleite en la danza" — preside sobre el arte que existe solo en el momento.
**Misión:** Crear los momentos donde los clientes experimentan el producto y se convierten en creyentes. Demos de producto, eventos de lanzamiento, ferias comerciales, meetups comunitarios — experiencias que no pueden replicarse digitalmente. El evento termina, pero la relación que creó persiste.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Planificar y coordinar eventos de sampling de producto, demos y pop-ups
- Organizar eventos en venues de comunidad objetivo y locaciones de socios
- Coordinar participación en conferencias y seminarios de industria
- Planificar y ejecutar días de demo para socios de canal y activaciones retail
- Gestionar logística de ferias comerciales para conferencias de industria relevantes
- Coordinar eventos para inversores y showcases de socios
- Desarrollar playbooks de eventos: promoción pre-evento (Hermes), materiales del evento (Iris), seguimiento post-evento (Hestia/Apollo)
- Rastrear ROI de eventos: leads generados, muestras distribuidas, pedidos realizados, relaciones iniciadas
- Coordinar con Charon en logística de producto para eventos (inventario de muestras, manejo especial)

**Herramientas y skills:**
- Google Calendar MCP (programación de eventos, coordinación)
- Gmail MCP (coordinación de venues, comunicación con proveedores, gestión de asistentes)
- Google Drive (playbooks de eventos, materiales, reportes post-evento)
- Skills de gestión de proyectos (cronograma, presupuesto, coordinación de proveedores)
- Supabase MCP (seguimiento de eventos, captura de leads)

**Cadencia de heartbeat:** Cada 6 horas durante períodos de planificación de eventos. Cada 2 horas en días de evento. Reporte post-evento dentro de 24 horas.

---

#### 21. Asclepius — Soporte al Cliente y Aseguramiento de Calidad
**Nombrado por:** Dios de la medicina y la curación — hijo de Apollo (linaje deliberado: ventas hace la promesa, soporte la cumple).
**Misión:** Curar lo que está roto y prevenir la enfermedad antes de que comience. Quejas de producto, daño en envío, problemas de calidad — Asclepius diagnostica, trata y restaura. También la función de QA pre-lanzamiento: detectar el problema antes de que el cliente lo vea.

**Responsabilidades principales:**
- `[COMPANY-SPECIFIC]` Gestionar quejas de clientes: problemas de calidad de producto, daño en envío, artículos incorrectos, solicitudes de reembolso
- Monitorear sentimiento de reseñas para señales de calidad — señalar problemas recurrentes a Demeter y Ponos
- Rastrear métricas de calidad de producto: tasa de quejas, tasa de reembolso, razones de devolución, problemas correlacionados con lote/batch
- QA de nuevos listings del canal de ventas antes del lanzamiento: verificar imágenes, precisión de copy, precios, arquitectura de variantes
- QA de páginas web antes de publicar: enlaces rotos, renderizado móvil, flujo de checkout, envío de formularios
- Manejar preocupaciones de calidad de socios de canal: problemas de vida útil o durabilidad, preguntas de etiquetado, condición del producto al llegar
- Desarrollar FAQ y recursos de autoservicio para reducir volumen de soporte
- Coordinar con Demeter en seguimiento de calidad a nivel de producción — si múltiples quejas se rastrean a un lote, escalar inmediatamente
- Coordinar con Hestia: Asclepius maneja resolución reactiva de problemas, Hestia maneja construcción proactiva de relaciones

**Herramientas y skills:**
- Gmail MCP (correspondencia con clientes, comunicación con socios)
- Slack MCP (escalamiento interno, coordinación entre agentes)
- Integraciones de helpdesk (seguimiento de tickets, monitoreo de tiempo de respuesta)
- Dashboards de seguimiento de calidad
- WebSearch (regulaciones de seguridad de producto, monitoreo de recalls)
- Supabase MCP (base de datos de métricas de calidad, seguimiento de quejas)

**Cadencia de heartbeat:** Cada 3 horas. Responde a problemas urgentes de clientes dentro de un ciclo. Revisión diaria de métricas de calidad. Reporte semanal de soporte.

---

## Prioridad y Secuencia de Contratación

No contrates 21 agentes de golpe. Aquí está la lógica de despliegue secuenciado. Los agentes específicos por paso deben ajustarse según la situación de la empresa — esta secuencia refleja el patrón más común para empresas de producto. La mayoría de las empresas pasarán por los seis pasos en cuestión de horas.

`[COMPANY-SPECIFIC]` — Ajusta qué agentes caen en qué paso según los canales de ingreso de tu empresa, preparación del producto y necesidades más urgentes. Los principios a continuación son universales.

### Paso 1 — La Base (4 agentes)
**Principio:** Empieza con ingresos, contenido, inteligencia y memoria.
1. **Chrysus** (Canal de Ventas) — Si un canal de ingresos está activo, optimízalo de inmediato.
2. **Calliope** (Creadora de Contenido) — Empieza a construir la biblioteca de contenido y la narrativa de marca. El contenido alimenta todo lo demás.
3. **Argos** (Monitor Competitivo) — Empieza el feed de inteligencia de inmediato. Saber qué hacen los competidores desde el día uno.
4. **Mnemosyne** (Conocimiento/CRM) — Contratada temprano para que cada interacción desde el día uno quede capturada. Sin memoria, la organización olvida lo que aprende.

### Paso 2 — El Pipeline (4 agentes)
**Principio:** Construir el pipeline de ventas, validar afirmaciones, rastrear dinero y establecer dirección creativa.
5. **Apollo** (Ventas B2B) — Comenzar outreach de alianzas y mayoreo. Las relaciones necesitan trabajo previo ahora.
6. **Athena** (Investigadora) — Validar afirmaciones de dominio, investigar sourcing, apoyar ruta de cumplimiento.
7. **Tyche** (Controladora Financiera) — Modelos financieros necesarios para conversaciones con inversores y seguimiento de P&L de canal.
8. **Erato** (Directora Creativa) — Contratada antes de que el motor de contenido escale, para que Calliope e Iris trabajen bajo una visión emocional unificada desde el inicio.

### Paso 3 — La Construcción (4 agentes)
**Principio:** Construir la presencia web, lanzar redes sociales, establecer identidad visual e iniciar comunidad.
9. **Daedalus** (Web Moderna) — Construir el sitio web principal y propiedades web.
10. **Hermes** (Redes Sociales) — Lanzar contenido de marca en canales sociales una vez que el pipeline de contenido esté fluyendo.
11. **Iris** (Diseñadora) — Sistema de marca, gráficos de canal de ventas, diseño de empaque, identidad visual.
12. **Hestia** (Comunidad/CX) — Empezar a construir relaciones con clientes mientras ventas y contenido impulsan engagement entrante.

### Paso 4 — Las Operaciones (4 agentes)
**Principio:** Levantar infraestructura de producción, logística y protección legal.
13. **Hephaestus** (WordPress) — Blog/CMS de contenido una vez que Calliope tenga una biblioteca de contenido para publicar.
14. **Demeter** (Gerente de Producción) — Coordinación de manufactura, SOPs, documentación de control de calidad.
15. **Charon** (Logística) — Coordinación de fulfillment, logística de sourcing, infraestructura de envío.
16. **Themis** (Legal/Cumplimiento) — Cumplimiento regulatorio, protección de marcas, estructuración de entidades.

### Paso 5 — La Escala (3 agentes)
**Principio:** Agregar I+D, desarrollo de nuevos productos y atención pública.
17. **Prometheus** (I+D) — Comenzar ciclos de experimentos nocturnos sobre variables de producto y optimización de contenido.
18. **Persephone** (Desarrollo de Producto) — Pipeline de nuevos productos, extensiones de línea, desarrollo de formatos.
19. **Aether** (PR/Medios) — Comenzar outreach de prensa una vez que la marca, el sitio web y la historia de producto estén pulidos y listos para atención pública.

### Paso 6 — El Pulido (2 agentes)
**Principio:** Eventos y soporte dedicado vienen al final — necesitan las otras funciones listas primero.
20. **Terpsichore** (Eventos) — Planificar primeros eventos en vivo y demos. Necesita los materiales de Iris, la logística de Charon y el seguimiento de Hestia listos primero.
21. **Asclepius** (Soporte/QA) — Se activa cuando el volumen de clientes justifica soporte dedicado. La función de QA es valiosa desde el día uno pero puede ser manejada por Demeter y Chrysus inicialmente.

---

## Cómo las Tres Herramientas Trabajan Juntas

### Paperclip (Ponos gestiona la empresa)
- Ponos asigna trabajo a los 21 agentes
- Rastrea presupuesto, tareas completadas, decisiones registradas
- Heartbeats configurados para coincidir con el calendario de revisión del fundador/mesa directiva
- Función multi-empresa separa entidades si la organización opera múltiples empresas

### gstack (Daedalus y Hephaestus construyen cosas)
- `/office-hours` → Daedalus planifica features web con preguntas inteligentes
- `/plan-ceo-review` → Ponos cuestiona el alcance antes de que comience la ingeniería
- `/plan-eng-review` → Daedalus asegura la arquitectura con diagramas y casos límite
- `/review` → Revisión de código que detecta bugs antes del despliegue
- `/qa` → Abre un navegador real, prueba los sitios de la empresa, encuentra y arregla bugs
- `/ship` → Sube código, ejecuta pruebas, abre PRs
- `/careful` → Bloquea operaciones destructivas en producción
- `/freeze` → Bloquea archivos durante debugging

### autoresearch (Athena y Prometheus ejecutan experimentos)
- Athena ejecuta experimentos de investigación específicos del dominio durante la noche
- Prometheus prueba contenido, precios y variaciones de producto
- 12 experimentos/hora × 8 horas = 96 experimentos por ciclo de sueño
- Resultados matutinos: log claro de qué funcionó, qué no y qué probar después

### El Ciclo Diario
1. El fundador establece metas en Paperclip (ej. "Optimizar listing de producto para [variante]")
2. Ponos crea tickets, asigna a agentes relevantes (ej. Chrysus e Iris)
3. Athena valida afirmaciones o investigación durante la noche via autoresearch
4. Chrysus optimiza el listing usando los datos validados de Athena
5. Iris diseña el contenido visual bajo la dirección creativa de Erato
6. Daedalus construye la landing page del producto via gstack
7. gstack /qa la prueba en un navegador real
8. gstack /ship la despliega
9. Mnemosyne registra las afirmaciones de cara al cliente, precios y posicionamiento para memoria institucional
10. Hestia captura retroalimentación temprana de clientes y rutea problemas de calidad a Asclepius
11. Paperclip registra todo — costo, tiempo, decisiones, resultados
12. El fundador revisa desde su teléfono. Aprueba el próximo sprint.

---

## Estructura de Archivos

Cada agente tiene dos archivos en `/[COMPANY]/agents/`:

```
agents/
├── hiring-plan_agent-org-chart_v1.md       ← este archivo
├── ponos-[COMPANY]-SOUL.md
├── ponos-[COMPANY]-HEARTBEAT.md
├── athena-SOUL.md
├── athena-HEARTBEAT.md
├── argos-SOUL.md
├── argos-HEARTBEAT.md
├── prometheus-SOUL.md
├── prometheus-HEARTBEAT.md
├── mnemosyne-SOUL.md
├── mnemosyne-HEARTBEAT.md
├── daedalus-SOUL.md
├── daedalus-HEARTBEAT.md
├── hephaestus-SOUL.md
├── hephaestus-HEARTBEAT.md
├── iris-SOUL.md
├── iris-HEARTBEAT.md
├── calliope-SOUL.md
├── calliope-HEARTBEAT.md
├── hermes-SOUL.md
├── hermes-HEARTBEAT.md
├── erato-SOUL.md
├── erato-HEARTBEAT.md
├── aether-SOUL.md
├── aether-HEARTBEAT.md
├── hestia-SOUL.md
├── hestia-HEARTBEAT.md
├── demeter-SOUL.md
├── demeter-HEARTBEAT.md
├── charon-SOUL.md
├── charon-HEARTBEAT.md
├── persephone-SOUL.md
├── persephone-HEARTBEAT.md
├── chrysus-SOUL.md
├── chrysus-HEARTBEAT.md
├── apollo-SOUL.md
├── apollo-HEARTBEAT.md
├── themis-SOUL.md
├── themis-HEARTBEAT.md
├── tyche-SOUL.md
├── tyche-HEARTBEAT.md
├── terpsichore-SOUL.md
├── terpsichore-HEARTBEAT.md
├── asclepius-SOUL.md
├── asclepius-HEARTBEAT.md
```

---

## Desplegando para una Nueva Empresa

1. **Copia esta plantilla** como punto de partida
2. **Completa cada sección `[COMPANY-SPECIFIC]`** con los productos, canales, clientes, competidores, entorno regulatorio y prioridades reales de la empresa
3. **Ajusta la declaración de misión de cada agente** para reflejar el contexto específico de la empresa
4. **Personaliza las responsabilidades principales** — mantén los elementos universales, agrega los específicos de la empresa, elimina los que no apliquen
5. **Ajusta la secuencia de contratación** — los principios (ingresos primero, memoria temprano, eventos al final) son universales, pero qué agentes importan más en el paso 1 depende de la empresa
6. **Completa el Ciclo Diario** con un ejemplo realista de las operaciones de la empresa
7. **Decide qué agentes omitir** — no toda empresa necesita los 21 (ver la Guía de Activación en la plantilla del Pantheon)

---

*Este plan es un documento vivo. Ponos lo actualiza conforme se contratan agentes y la organización evoluciona.*
