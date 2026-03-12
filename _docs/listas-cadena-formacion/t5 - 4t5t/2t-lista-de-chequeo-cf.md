# Lista de Chequeo — Trimestre II
## Seguimiento de Proyecto Formativo · Cadena de Formación
### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Modalidad:** Cadena de Formación (aprendices graduados como Técnicos en Desarrollo de Software)  
> **Equivalencia en el semáforo interno:** Trimestre III–IV del plan de formación  
> **Fase del proyecto formativo:** Arquitectura de Software + Propuesta Técnica — Proyecto II  
> **Competencias activas:** Análisis de la Especificación de Requisitos del Software · Elaboración de la Propuesta Técnica del Software · Modelado de los Artefactos del Software (inicio) · Construcción de BD — resultado parcial · HTML/CSS/Responsive  
> **Propósito del trimestre:** El equipo, que trae base técnica de la etapa de Técnico, profundiza en arquitectura de software, consolida el análisis mediante modelado UML avanzado, construye una propuesta técnica completa con estimación ágil (Scrum/backlog/costos) y avanza en el diseño de la interfaz web responsive. El nivel de exigencia es superior al T2 de Oferta Abierta en densidad técnica y en madurez de los artefactos.

---

## Datos de la sesión

| Campo | Valor |
|-------|-------|
| Número de Ficha | |
| Nombre del grupo de proyecto | |
| Nombre del sistema / software | |
| Integrantes presentes | |
| Integrantes ausentes | |
| Fecha de sustentación | |
| Jurado 1 | |
| Jurado 2 | |

---

## Escala de valoración

| Símbolo | Nivel | Descripción |
|---------|-------|-------------|
| ✅ | **Excelente** | Cumple completamente con evidencia sólida y sustentable |
| 🟡 | **Satisfactorio** | Cumple parcialmente o la evidencia es incompleta pero válida |
| 🔴 | **Insuficiente** | No cumple o la evidencia es muy débil / ausente |
| ➖ | **No aplica** | El ítem no corresponde al tipo o contexto de este proyecto |

---

## Ponderación por dimensión

| Dimensión | Peso |
|-----------|------|
| D1 — Gestión del Proyecto | 20 % |
| D2 — Artefactos Técnicos | 40 % |
| D3 — Documentación | 20 % |
| D4 — Trabajo en Equipo | 10 % |
| D5 — Calidad y Mejores Prácticas | 10 % |

---

> **Nota al jurado:** Los aprendices de Cadena de Formación llegan al programa habiendo cursado el Técnico en Desarrollo de Software. Esto significa que ya tienen base en lógica de programación, modelado de datos básico y manejo de herramientas de desarrollo. El jurado debe calibrar sus preguntas y expectativas a ese nivel: no se evalúa si saben qué es una clase o una tabla, sino si aplican ese conocimiento con criterio en el contexto de un proyecto real de complejidad media-alta.

---

## DIMENSIÓN 1 — Gestión del Proyecto (20 %)

> A diferencia del T1, en este trimestre el proceso de gestión debe mostrar madurez metodológica. Se espera que el equipo no solo use una herramienta de seguimiento, sino que la use con criterio ágil: sprints definidos, backlog priorizado, velocidad estimada y reuniones de revisión documentadas.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 1.1 | El equipo tiene un **product backlog** documentado en la herramienta de gestión elegida (Jira, Trello, GitHub Projects, Notion, etc.), con historias de usuario priorizadas usando un criterio explícito (MoSCoW, valor vs. esfuerzo u otro). | | | | | |
| 1.2 | El backlog está dividido en **sprints** con objetivo claro por sprint. El equipo puede explicar cuántos sprints ha completado en el trimestre, qué se logró en cada uno y qué quedó pendiente. | | | | | |
| 1.3 | Existen **actas de las ceremonias Scrum** (o equivalente según metodología elegida): al menos una acta de sprint planning, evidencia de daily (puede ser captura del canal de comunicación) y una acta de sprint review / retrospectiva del período. | | | | | |
| 1.4 | Los **roles del equipo** son claros, visibles en la herramienta de gestión y operativos: hay un Product Owner identificado que puede hablar sobre las prioridades del negocio, y un Scrum Master que puede describir los impedimentos que gestionó. | | | | | |
| 1.5 | El equipo puede mostrar un **gráfico de burndown** (generado por la herramienta o elaborado manualmente) que represente el avance real del sprint más reciente. Aunque el gráfico no sea perfecto, el equipo entiende lo que representa. | | | | | |

---

## DIMENSIÓN 2 — Artefactos Técnicos (40 %)

> Esta dimensión se divide en cuatro bloques que corresponden a las competencias activas del trimestre. Dado que los aprendices de Cadena ya traen base técnica, los artefactos deben mostrar mayor rigor que en Oferta Abierta.

### Bloque 2A — Arquitectura de software y modelado de análisis (RA 01 y 02 de Análisis)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2A.1 | El equipo ha definido y documentado la **arquitectura candidata del sistema**: indica el patrón arquitectónico elegido (capas, cliente-servidor, MVC, REST + SPA, microservicios, etc.) con una justificación técnica que relaciona la elección con los requisitos no funcionales del proyecto. | | | | | |
| 2A.2 | Existe un **diagrama de componentes** (UML o equivalente) que muestra los módulos principales del sistema, sus interfaces y cómo se comunican entre sí. El diagrama es coherente con la arquitectura declarada. | | | | | |
| 2A.3 | El equipo puede explicar **al menos dos principios SOLID** y demostrar cómo una decisión de diseño o código del proyecto los aplica o los tuvo en cuenta. | | | | | |
| 2A.4 | Existen **diagramas de casos de uso** en UML que cubren todos los actores y los casos de uso del sistema, con relaciones `include` y `extend` donde corresponde, y son completamente trazables al SRS del T1. | | | | | |
| 2A.5 | Para los casos de uso críticos (mínimo 5) existen **plantillas extendidas** con flujo básico, flujos alternativos, precondiciones, postcondiciones y condiciones de excepción claramente especificadas. | | | | | |
| 2A.6 | Existe un **modelo de dominio** actualizado que refleja las clases conceptuales identificadas, sus atributos relevantes y las relaciones del negocio. Se distingue claramente del diagrama de clases de diseño. | | | | | |
| 2A.7 | Existe al menos un **diagrama de actividades UML** por cada proceso de negocio principal, con calles de responsabilidad (swimlanes) cuando intervienen múltiples actores. | | | | | |

### Bloque 2B — Propuesta técnica del software (RA 01, 02 y 03 de Propuesta Técnica)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2B.1 | Existe una **propuesta técnica formal** que incluye: descripción del alcance, stack tecnológico seleccionado con justificación, estimación de esfuerzo por sprints y cronograma de desarrollo. | | | | | |
| 2B.2 | La propuesta incluye **fichas técnicas** de los componentes tecnológicos principales (servidor de aplicaciones, motor de base de datos, framework de backend, framework de frontend) con sus características, versión y tipo de licencia. | | | | | |
| 2B.3 | El equipo ha realizado una **estimación de costos** del proyecto: aunque sea a nivel de ejercicio formativo, incluye al menos costos de licencias de software (si aplica), infraestructura estimada (hosting, nube) y costo del talento humano expresado en horas de trabajo. | | | | | |
| 2B.4 | Existe un **análisis comparativo de al menos dos alternativas tecnológicas** para algún componente crítico del sistema (motor de BD, framework backend, plataforma de nube, etc.) con una decisión argumentada sobre cuál se elige y por qué. | | | | | |
| 2B.5 | El equipo puede presentar el análisis de **propiedad intelectual**: si el sistema usará software de terceros, puede indicar el tipo de licencia de cada componente (MIT, GPL, Apache, propietaria) y si esa licencia es compatible con el uso que le darán. | | | | | |

### Bloque 2C — Modelo de datos relacional (RA 02 de Construcción de BD — resultado parcial)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2C.1 | El **modelo lógico relacional** está completo y normalizado hasta 3FN. El equipo puede demostrar que aplicó las reglas de normalización y puede explicar al menos un caso concreto de descomposición por una forma normal. | | | | | |
| 2C.2 | Existe un **diccionario de datos** completo para todas las tablas del modelo: nombre de cada columna, tipo de dato con precisión (VARCHAR(100), INT, DATE, etc.), restricciones (PK, FK, NOT NULL, UNIQUE, CHECK) y descripción breve del dato. | | | | | |
| 2C.3 | El equipo ha definido **políticas de seguridad de datos** básicas: qué campos deben cifrarse o enmascararse (contraseñas, datos personales sensibles), qué niveles de acceso tendrán los roles del sistema y cómo se garantiza la integridad referencial. | | | | | |
| 2C.4 | Existe un **script SQL** (DDL) que crea la estructura de la base de datos a partir del modelo lógico, con las restricciones definidas. El script debe poder ejecutarse sin errores en el motor seleccionado. | | | | | |

### Bloque 2D — Diseño de interfaz y HTML/CSS/Responsive

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2D.1 | Existe un **sistema de diseño básico** definido para el proyecto: paleta de colores con mínimo 3 tonos, tipografías elegidas (una para títulos, una para cuerpo de texto), y criterios de espaciado coherentes. Puede estar en Figma, en un documento o en variables CSS. | | | | | |
| 2D.2 | Existe un **prototipo web en HTML semántico** para las pantallas principales del sistema (mínimo 5), aplicando correctamente las etiquetas estructurales (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`). | | | | | |
| 2D.3 | El prototipo usa un **framework CSS o CSS puro con metodología** (Tailwind, Bootstrap, BEM, etc.) de manera consistente. No hay mezcla caótica de estilos inline con clases de framework. | | | | | |
| 2D.4 | El prototipo es completamente **responsive**: funciona correctamente en tres puntos de quiebre como mínimo (móvil < 768 px, tablet 768–1024 px, escritorio > 1024 px). El equipo puede demostrarlo en las DevTools durante la sustentación. | | | | | |
| 2D.5 | El equipo puede mostrar un **mapa de navegación** (sitemap) del sistema que indique cómo se conectan todas las vistas entre sí y cuáles requieren autenticación. | | | | | |

---

## DIMENSIÓN 3 — Documentación (20 %)

> En Cadena de Formación la exigencia documental es mayor porque los aprendices ya tienen experiencia previa. Se espera documentación que un desarrollador externo pueda leer y entender sin necesidad de preguntarle al equipo.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 3.1 | El **repositorio** tiene un `README.md` completo que describe el proyecto, la arquitectura elegida, el stack tecnológico, los pasos de instalación del entorno de desarrollo y cómo ejecutar el proyecto localmente. | | | | | |
| 3.2 | El **informe de análisis** (o documento de análisis y diseño) tiene portada, control de versiones, tabla de contenido, y está redactado de acuerdo con NTC 1486 o APA. Incluye como mínimo: descripción del sistema, diagramas UML referenciados, modelo de datos y decisiones arquitectónicas. | | | | | |
| 3.3 | La **propuesta técnica** es un documento independiente bien estructurado, no integrado al informe de análisis. Incluye: portada, resumen ejecutivo, alcance, stack tecnológico, fichas técnicas, estimación de costos y cronograma por sprints. | | | | | |
| 3.4 | Todos los **diagramas** (UML, modelo de datos, arquitectura) están en el repositorio en formato editable (archivo del modelador) y en formato imagen/PDF para consulta rápida. | | | | | |
| 3.5 | La **estrategia de ramas en Git** está documentada: el equipo usa al menos `main`, `develop` y ramas por funcionalidad o historia de usuario. Los pull requests (o merges) tienen descripción de lo que integran. | | | | | |

---

## DIMENSIÓN 4 — Trabajo en Equipo (10 %)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 4.1 | El **historial de commits** por rama muestra que todos los integrantes del equipo contribuyeron activamente. El jurado puede revisar la pestaña de contribuidores del repositorio durante la sesión. | | | | | |
| 4.2 | Todos los integrantes presentes **participan en la sustentación** con conocimiento real del artefacto que exponen. No hay "testigos mudos". | | | | | |
| 4.3 | El equipo puede describir **cómo resolvió un conflicto técnico o de equipo** durante el trimestre (desacuerdo sobre una decisión de diseño, integrante con bajo rendimiento, dificultad de coordinación de horarios) y qué estrategia aplicó. | | | | | |
| 4.4 | La **distribución de tareas** en el tablero de gestión es equitativa. Si el jurado revisa la herramienta, no debería encontrar que un solo integrante tiene el 90 % de las tareas asignadas y cerradas. | | | | | |

---

## DIMENSIÓN 5 — Calidad y Mejores Prácticas (10 %)

> Los aprendices de Cadena deben demostrar criterio técnico más allá de lo básico. No basta con que el código funcione: debe estar bien construido, documentado y tener trazabilidad de calidad.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 5.1 | El equipo tiene definido y documentado su **estándar de codificación**: convenciones de nombrado para variables, métodos, clases y tablas; reglas de indentación; política de comentarios en el código. | | | | | |
| 5.2 | Los **prototipos o código de frontend** cumplen criterios básicos de accesibilidad web (WCAG nivel A como mínimo): texto alternativo en imágenes, contraste de color suficiente, formularios con labels asociados. | | | | | |
| 5.3 | El equipo realizó al menos una **revisión técnica entre pares** (peer review) de algún artefacto del trimestre (código, diagrama o documento) con evidencia del proceso: comentarios en GitHub, acta o lista de chequeo interna. | | | | | |
| 5.4 | El equipo puede identificar **al menos tres decisiones de diseño** del sistema —en la arquitectura, en el modelo de datos o en la interfaz— que fueron tomadas conscientemente pensando en la mantenibilidad, escalabilidad o seguridad del software. | | | | | |
| 5.5 | Los **modelos UML y el modelo de datos** son coherentes entre sí: si el jurado toma una entidad del modelo de dominio, debería encontrar su correspondencia en el modelo relacional. Si hay diferencias, el equipo puede explicarlas técnicamente. | | | | | |

---

## Resumen de evaluación

| Dimensión | Peso | Calificación del jurado (✅/🟡/🔴) | Notas |
|-----------|------|------------------------------------|-------|
| D1 — Gestión del Proyecto | 20 % | | |
| D2 — Artefactos Técnicos | 40 % | | |
| D3 — Documentación | 20 % | | |
| D4 — Trabajo en Equipo | 10 % | | |
| D5 — Calidad y Mejores Prácticas | 10 % | | |

---

## Decisión del jurado

| Decisión | Seleccionar |
|----------|-------------|
| ☐ **Aprobado sin condiciones** | El equipo continúa al T3 con el proyecto vigente. |
| ☐ **Aprobado con condicionamientos** | El equipo continúa pero debe resolver los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora** | El grupo tiene hasta [fecha] para subsanar los ítems críticos y presentar nuevamente ante el mismo jurado. |

### Condicionamientos o ajustes requeridos (diligenciar si la decisión no es aprobación sin condiciones)

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
|-------------------------------|-----------------|--------------|
| | | |
| | | |

---

## Retroalimentación cualitativa del jurado

| Jurado | Fortaleza principal observada en el equipo este trimestre | Oportunidad de mejora más urgente para el T3 |
|--------|-----------------------------------------------------------|-----------------------------------------------|
| Jurado 1 | | |
| Jurado 2 | | |

---

## Firmas

| Rol | Nombre completo | Firma |
|-----|----------------|-------|
| Jurado 1 | | |
| Jurado 2 | | |
| Vocero del grupo (constancia de recibido del feedback) | | |

---

*Instrumento de evaluación formativa — Programa ADSO 228118 · Cadena de Formación · Trimestre II (equivale a Trim III–IV del plan interno)*  
*Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital*