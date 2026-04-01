# El Paperclip Pantheon

**Un framework completo de fuerza laboral IA para operar una empresa con 21 agentes especializados, un consejo estratégico de 5 miembros y un CEO — todos nombrados de la mitología griega porque los nombres codifican las funciones.**


Creado por [Josh Galt III](https://x.com/joshgalt) y [Anabasis Intelligence](https://anabasisintelligence.com), una firma de implementación de IA creativa que ayuda a PyMEs a operacionalizar fuerzas laborales de IA. **[English version](https://github.com/JG003/paperclip-pantheon)**

![Paperclip Pantheon](banner-paperclip-pantheon2.png)

---

## Qué Es Esto

Un sistema de plantillas de código abierto, listo para producción, para desplegar una fuerza laboral completa de agentes IA que opere una empresa, optimizado para uso en [Paperclip](https://paperclip.ing). Estos son los archivos reales que le entregas a tu CEO de IA junto con tus archivos md específicos de la empresa, y tu CEO construye todo el equipo según esta estructura.

**El sistema incluye:**

- **1 agente CEO** (Ponos) que gestiona toda la organización
- **21 operativos especializados** en 6 divisiones — investigación, ingeniería, marketing, operaciones, ingresos y soporte
- **5 asesores de consejo** para toma de decisiones estratégicas — adaptado de la metodología [LLM Council de Karpathy](https://x.com/karpathy)
- **Archivos SOUL** (identidad, misión, responsabilidades, voz) y **archivos HEARTBEAT** (cadencia, listas de verificación, protocolos de escalamiento) para cada agente
- **3 documentos de framework** — el Pantheon (mitología + estructura organizacional), el Council of 5 (framework de decisiones), y el Hiring Plan (despliegue secuenciado)

Cada agente lleva un nombre de la mitología griega usando **determinismo nominativo** — el nombre codifica la función. Athena investiga. Hermes comunica. Charon transporta cosas. Cuando escuchas el nombre, sabes el trabajo.

---

## Por Qué Mitología Griega

Esto no es decoración, es una arquitectura mnemotécnica.

Un nuevo miembro del equipo (humano o IA) que escucha "Athena está trabajando en el brief de investigación" inmediatamente tiene un modelo mental de lo que Athena hace y cómo piensa — antes de leer una sola línea de su configuración. La mitología proporciona intuición instantánea sobre la personalidad, prioridades y enfoque de cada agente.

Las relaciones familiares codifican dependencias organizacionales: Mnemosyne (memoria) es la madre de Calliope (contenido) y Erato (dirección creativa) — porque toda producción creativa depende de la memoria institucional. Apollo (ventas) es el padre de Asclepius (soporte) — porque cada promesa que ventas hace se convierte en responsabilidad de soporte. Y así sucesivamente.

---

## El Roster

### CEO
| Agente | Rol |
|--------|-----|
| **Ponos** | Director General + Presidente del Consejo |

### 21 Operativos

| # | Agente | Rol | División |
|---|--------|-----|----------|
| 1 | **Athena** | Investigadora Científica / de Dominio | Estrategia e Inteligencia |
| 2 | **Argos** | Monitor de Noticias en Tiempo Real | Estrategia e Inteligencia |
| 3 | **Prometheus** | Ejecutor de Experimentos I+D | Estrategia e Inteligencia |
| 4 | **Mnemosyne** | Gestora de Conocimiento y CRM | Estrategia e Inteligencia |
| 5 | **Daedalus** | Ingeniero Web Moderno | Construcción y Despliegue |
| 6 | **Hephaestus** | Ingeniero WordPress | Construcción y Despliegue |
| 7 | **Iris** | Diseñadora | Construcción y Despliegue |
| 8 | **Calliope** | Creadora de Contenido | Marketing y Marca |
| 9 | **Hermes** | Marketer de Redes Sociales | Marketing y Marca |
| 10 | **Erato** | Directora Creativa | Marketing y Marca |
| 11 | **Aether** | PR y Medios Ganados | Marketing y Marca |
| 12 | **Hestia** | Comunidad y Éxito del Cliente | Marketing y Marca |
| 13 | **Demeter** | Controladora de Producción | Operaciones |
| 14 | **Charon** | Logística y Cadena de Suministro | Operaciones |
| 15 | **Persephone** | Desarrollo de Producto | Operaciones |
| 16 | **Chrysus** | Experto en Canal de Ventas | Ingresos y Negocios |
| 17 | **Apollo** | Agente de Ventas B2B | Ingresos y Negocios |
| 18 | **Themis** | Legal y Cumplimiento | Ingresos y Negocios |
| 19 | **Tyche** | Controladora Financiera | Ingresos y Negocios |
| 20 | **Terpsichore** | Eventos y Experiencias en Vivo | Experiencia y Soporte |
| 21 | **Asclepius** | Soporte al Cliente y QA | Experiencia y Soporte |

### Council of 5

| Agente | Rol | Tensión |
|--------|-----|---------|
| **Momus** | El Contrario | ← Riesgo vs. Oportunidad → |
| **Eos** | La Expansionista | ← Riesgo vs. Oportunidad → |
| **Metis** | Pensadora de Primeros Principios | ← Replantear vs. Actuar → |
| **Nike** | La Ejecutora | ← Replantear vs. Actuar → |
| **Proteus** | El Outsider | Mantiene la honestidad de todos |

---

## Cómo Funciona

### Paso 1: Dale a Ponos su SOUL
Crea un archivo SOUL y HEARTBEAT específico de la empresa para Ponos (el CEO) con el contexto de tu empresa — productos, canales, clientes, competidores, prioridades.

### Paso 2: Entrégale a Ponos las plantillas
Dale los tres documentos de framework y los 54 archivos de plantilla de agentes de este repositorio. Él los lee y produce versiones específicas de la empresa basándose en su comprensión profunda del negocio.

### Paso 3: Ponos construye el equipo
Él decide qué agentes activar (no toda empresa necesita los 21), personaliza sus archivos SOUL y HEARTBEAT, y los contrata en secuencia — ingresos primero, memoria temprano, eventos al final.

### Paso 4: La empresa opera
Los agentes operan en cadencias de heartbeat (cada 2–6 horas según el rol). El Council of 5 se convoca para decisiones de alto impacto. Ponos gestiona todo y reporta a la mesa directiva.

**La mayoría de las empresas pueden levantar el sistema completo en una tarde.**

---

## Estructura del Repositorio

```
paperclip-pantheon/
├── README.md
├── LICENSE
├── framework/
│   ├── pantheon.md              ← Mitología, estructura org, guía de activación
│   ├── council-of-5.md          ← Framework de decisiones estratégicas
│   └── hiring-plan.md           ← Organigrama, secuencia de contratación, ciclo diario
├── agents/
│   ├── operatives/              ← 22 archivos SOUL + HEARTBEAT (Ponos + 21 agentes)
│   │   ├── ponos-SOUL.md
│   │   ├── ponos-HEARTBEAT.md
│   │   ├── athena-SOUL.md
│   │   ├── athena-HEARTBEAT.md
│   │   └── ... (44 archivos en total)
│   └── council/                 ← 10 archivos SOUL + HEARTBEAT (5 asesores)
│       ├── momus-SOUL.md
│       ├── momus-HEARTBEAT.md
│       └── ... (10 archivos en total)
```

---

## No Toda Empresa Necesita los 21

El framework incluye una **Guía de Activación** con tres niveles:

**Siempre Activos** (toda empresa): Ponos, Argos, Calliope, Hermes, Iris, Tyche, Mnemosyne

**Usualmente Activos** (la mayoría de empresas): Athena, Apollo, Daedalus, Hephaestus, Themis, Hestia, Asclepius

**Condicionales** (activar según necesidad): Prometheus, Demeter, Chrysus, Persephone, Charon, Aether, Erato, Terpsichore

Un fundador solo podría operar con 7 agentes. Una empresa de productos físicos podría usar los 21. El Council of 5 es siempre el mismo en todas partes — los estilos de pensamiento no cambian, solo cambia el contexto.

---

## Inspirado Por

- [Dotta](https://x.com/dotta) - creador de Paperclip, orquestación de código abierto para empresas sin humanos
- [Andrej Karpathy](https://x.com/karpathy) — metodología LLM Council, openresearch, y la idea de que múltiples perspectivas IA producen mejores decisiones que un solo modelo
- [Gary Tan](https://x.com/garrytan) — flujo de trabajo de ingeniería gstack que impulsa la división de Construcción y Despliegue
- [Claude de Anthropic](https://claude.ai) — el modelo que impulsa a los agentes
- Mitología griega — por codificar lógica organizacional en nombres memorables e intuitivos desde aproximadamente el 800 a.C.

---

## Construido Con

Este sistema está diseñado para uso con:
- **[Paperclip](https://paperclip.ing)** por [Dotta](https://x.com/dotta)
- **[Claude](https://claude.ai)** de Anthropic (Opus 4.6 / Sonnet 4.6) como modelo base
- **[Cowork](https://claude.ai)** de Anthropic para gestión de agentes
- **[Claude Code](https://docs.claude.com)** para agentes de ingeniería (Daedalus, Hephaestus)
- Compatible con cualquier plataforma LLM que soporte system prompts y uso de herramientas

---

## Licencia

MIT — úsalo, haz fork, adáptalo, construye tu propio Olimpo.

---

## Acerca De

Creado por [Josh Galt III](https://x.com/joshgalt) y **[Anabasis Intelligence](https://anabasisintelligence.com)** — ayudamos a negocios tradicionales y emprendedores a operacionalizar fuerzas laborales de IA. Si quieres que despleguemos esto en Paperclip para tu empresa en lugar de hacerlo tú mismo, [contáctanos](https://anabasisintelligence.com).

**También disponible en inglés** para el mercado anglosajón.
**[English version](https://github.com/JG003/paperclip-pantheon)**

---

*Los griegos construyeron su mitología para codificar cómo funciona el mundo. Nosotros la usamos para codificar cómo funciona una empresa. Los nombres no son branding. Son arquitectura.*
