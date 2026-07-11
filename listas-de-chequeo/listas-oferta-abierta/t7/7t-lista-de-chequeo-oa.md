# Lista de Chequeo — Trimestre VII
## Seguimiento de Proyecto Formativo · Oferta Abierta
### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Fase del proyecto formativo:** Implantación del Software + Aseguramiento de la Calidad — Proyecto VII *(cierre de la etapa lectiva)*
>
> **Resultados de Aprendizaje que se cierran definitivamente en este trimestre:**
>
> **Competencia Construcción del Software:**
> - RA 01: Planear actividades de construcción del software de acuerdo con el diseño establecido — **resultado FINAL**
>
> **Competencia Adopción de Buenas Prácticas en el Proceso de Desarrollo de Software:**
> - RA 01: Incorporar actividades de aseguramiento de la calidad del software de acuerdo con estándares de la industria
> - RA 02: Verificar la calidad del software de acuerdo con las prácticas asociadas en los procesos de desarrollo
> - RA 03: Realizar actividades de mejora de la calidad del software a partir de los resultados de la verificación
>
> **Competencia Implantación del Software:**
> - RA 01: Planear actividades de implantación del software de acuerdo con las condiciones del sistema
> - RA 02: Desplegar el software de acuerdo con la arquitectura y las políticas establecidas
> - RA 03: Documentar el proceso de implantación de software siguiendo estándares de calidad
> - RA 04: Implantar el software de acuerdo con los niveles de servicio establecidos con el cliente
>
> **Módulos técnicos activos:** Asesoría de Desarrollo / Codificación final del proyecto (6 h/sem) · Buenas Prácticas de Software (12 h/sem) · Implantación, Despliegue, Diseño y Elaboración de Manuales Técnicos y de Usuario (12 h/sem)
>
> **Propósito del trimestre:** T7 es el cierre de la etapa lectiva del programa de Oferta Abierta. No se trata de seguir construyendo funcionalidades: se trata de llevar el sistema al estado en que puede ser entregado y operado por un cliente real. El trimestre tiene tres frentes simultáneos que deben converger: terminar y pulir el código del proyecto (cierre de construcción), aplicar un proceso formal de aseguramiento de calidad con estándares reconocidos por la industria, y ejecutar la implantación completa del sistema — despliegue en un ambiente real o simulado de producción, manuales técnicos y de usuario, plan de capacitación y pruebas de aceptación con el cliente. La pregunta central del trimestre es la misma que en T4 de Cadena, pero ahora con siete trimestres de trabajo detrás: **¿este sistema está listo para ser entregado y operado por alguien que no perteneció al equipo de desarrollo?**

---

## Datos de la sesión

| Campo | Valor |
|-------|-------|
| Número de Ficha | |
| Nombre del grupo de proyecto | |
| Nombre del sistema / software | |
| Stack tecnológico completo del sistema | |
| URL del repositorio | |
| URL del sistema desplegado | |
| Integrantes presentes | |
| Integrantes ausentes | |
| Fecha de sustentación | |
| Jurado 1 | |
| Jurado 2 | |

---

## Escala de valoración

| Símbolo | Nivel | Descripción |
|---------|-------|-------------|
| ✅ | **Excelente** | Cumple completamente con evidencia demostrable en el momento |
| 🟡 | **Satisfactorio** | Cumple parcialmente; evidencia incompleta pero válida |
| 🔴 | **Insuficiente** | No cumple o la evidencia es muy débil / ausente |
| ➖ | **No aplica** | El ítem no corresponde al tipo o contexto de este proyecto |

**Tiers de verificación** (ver [6.tiempos-de-sesion.md](../../../6.tiempos-de-sesion.md)): 🎤 verificación viva (demo/explicación oral, 1-1.5 min) · 👁 inspección rápida (vistazo binario, 20-30 seg).

---

## Ponderación por dimensión

| Dimensión | Peso |
|-----------|------|
| D1 — Cierre de la Construcción del Software | 20 % |
| D2 — Implantación y Despliegue | 25 % |
| D3 — Aseguramiento de la Calidad | 25 % |
| D4 — Documentación de Entrega | 20 % |
| D5 — Proceso, Equipo y Reflexión Final | 10 % |

> **Nota pedagógica sobre la ponderación:** En T7 la estructura de dimensiones cambia completamente respecto a los trimestres anteriores porque las competencias nuevas —Implantación y Calidad— tienen cada una el mismo peso que la construcción del sistema. Esto es deliberado: un tecnólogo que construye software excelente pero no sabe desplegarlo, documentarlo ni garantizar su calidad bajo estándares reconocidos no está completamente formado. Las cinco dimensiones tienen el mismo orden de importancia que los RA del semáforo: primero se cierra la construcción, luego se implanta, luego se verifica la calidad, luego se documenta la entrega, y finalmente se evalúa el proceso y la madurez del equipo como colectivo de trabajo.

---

## Distribución del tiempo de sesión (20 min)

| Bloque | Minutos |
| --- | --- |
| Contexto y datos de sesión | 1 |
| 🎤 Demo en vivo + preguntas (12 ítems 🎤: sistema desplegado, capacitación simulada, cierre, bloque serial) | 15 |
| 👁 Inspección rápida (manuales, plan de calidad, evidencia de repo) — en paralelo, Jurado 2 | — |
| Retroalimentación, decisión y firmas | 4 |
| **Total** | **20** |

---

## DIMENSIÓN 1 — Cierre de la Construcción del Software (20 %)

> Esta dimensión cierra definitivamente el RA 01 de Construcción (planeación) que ha venido como resultado parcial desde T6, y evalúa el estado final del código del proyecto. No se esperan funcionalidades nuevas revolucionarias en T7: se espera un sistema terminado, limpio, estable y con la deuda técnica documentada y gestionada.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 1.1 | 🎤 El sistema completo **funciona de manera integrada y estable**: todos los componentes activos (frontend, cuatro backends, BD relacional, BD NoSQL) operan sin errores críticos en el entorno desplegado. El jurado puede solicitar la ejecución de cualquier caso de uso del sistema durante la sesión y el equipo debe poder demostrarlo sin intervención de corrección en el momento. | | | | | |
| 1.2 | 🎤 El equipo presenta el **estado final del backlog del proyecto**: porcentaje de historias completadas respecto al SRS original, con una justificación documentada y honesta para las historias que quedaron fuera del alcance de la etapa lectiva. | | | | | |
| 1.3 | 👁 El **plan de construcción final** documenta las funcionalidades entregadas en T7 y lo que queda pendiente para la etapa productiva con su prioridad, y el código fuente está **limpio y organizado para entrega definitiva**: sin archivos de depuración, ramas de experimentos sin cerrar, código comentado masivamente, ni `console.log`/`print` de desarrollo. | | | | | |
| 1.4 | 👁 El sistema implementa **seguridad básica verificable**: contraseñas con hash (bcrypt u otro), tokens JWT con expiración definida, consultas a BD parametrizadas o vía ORM (sin inyección SQL), y rutas protegidas que rechazan peticiones sin autenticación válida. | | | | | |

---

## DIMENSIÓN 2 — Implantación y Despliegue (25 %)

> La implantación es la competencia que más frecuentemente los aprendices subestiman porque asumen que "terminar el código" es el destino final. T7 les demuestra que el software que solo corre en el laptop del desarrollador no le sirve a nadie. Esta dimensión evalúa los cuatro RA de Implantación de manera secuencial: primero la planeación, luego el despliegue real, luego la documentación del proceso, y finalmente la entrega formal con capacitación y pruebas de aceptación.

### Bloque 2A — Planeación de la implantación (RA 01 de Implantación)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2A.1 | 👁 Existe un **plan de implantación documentado**: actividades de despliegue con secuencia y responsables, requisitos de infraestructura, criterios de éxito, y plan de contingencia. | | | | | |
| 2A.2 | 👁 El plan incluye una **estrategia de migración de datos** (o justifica explícitamente por qué no aplica) y una **estrategia de copias de seguridad**: datos críticos, frecuencia, almacenamiento separado del servidor principal y procedimiento de restauración. | | | | | |

### Bloque 2B — Despliegue del sistema (RA 02 de Implantación)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2B.1 | 🎤 El sistema está **desplegado en un entorno diferente al local** de desarrollo (nube, servidor del centro, o Docker Compose reproducible). El jurado accede al sistema desplegado desde un navegador durante la sesión usando la URL declarada. | | | | | |
| 2B.2 | 👁 El despliegue usa **separación de configuración por ambiente** (variables sensibles fuera del repositorio, `.env.example` documentado) y, si usa **contenedores Docker**, tiene `Dockerfile` por servicio y `docker-compose.yml` funcional; si no, tiene script de instalación o README de despliegue verificado en ambiente limpio. | | | | | |
| 2B.3 | 🎤 El equipo demuestra que el sistema se **puede desplegar desde cero** siguiendo únicamente el manual de instalación: clonar, configurar variables, ejecutar scripts de BD y levantar servicios, sin conocimiento implícito. | | | | | |

### Bloque 2C — Implantación con el cliente (RA 04 de Implantación)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2C.1 | 👁 El equipo elaboró un **plan de capacitación de usuarios**: perfiles a capacitar, temas, duración, materiales de apoyo y criterios de éxito de la capacitación. | | | | | |
| 2C.2 | 🎤 El equipo presenta o demuestra al menos **una sesión de capacitación simulada**: asume el rol de capacitador y guía a los jurados (como usuarios finales) por las funcionalidades principales, usando el sistema real desplegado y el manual de usuario como soporte. | | | | | |
| 2C.3 | 👁 Existen **pruebas de aceptación documentadas**: al menos cinco casos de uso verificados con el cliente simulado, con resultado (aceptado / rechazado / con observaciones) y constancia de quien actuó como cliente. | | | | | |

---

## DIMENSIÓN 3 — Aseguramiento de la Calidad (25 %)

> Esta dimensión cubre los tres RA de la competencia de Buenas Prácticas, que operan en secuencia obligatoria: incorporar prácticas de calidad → verificar que el software las cumple → mejorar a partir de los resultados. El jurado debe verificar que el equipo ejecutó esas tres fases de manera real y documentada, no que las declaró en un documento de presentación.

### Bloque 3A — Incorporación de estándares de calidad (RA 01 de Calidad)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3A.1 | 🎤 El equipo adoptó al menos **un estándar o referente de calidad reconocido** (ISO/IEC 25010, CMMI, PSP, o una selección documentada de prácticas de XP/Scrum) y puede mostrar cómo influyó en decisiones concretas del proyecto. | | | | | |
| 3A.2 | 👁 El equipo tiene un **plan de aseguramiento de calidad** (atributos de calidad priorizados, actividades de QA, métricas) y un **pipeline de CI** (o un script único que ejecuta todas las pruebas con un comando), demostrable con el historial de ejecuciones. | | | | | |

### Bloque 3B — Verificación de la calidad (RA 02 de Calidad)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3B.1 | 👁 Existe un **informe de evaluación de calidad** del sistema: cumplimiento de requisitos no funcionales del SRS (tiempo de respuesta, disponibilidad, comportamiento bajo carga) y al menos dos atributos del modelo adoptado con métricas medidas vs. metas. | | | | | |
| 3B.2 | 👁 Se realizaron **pruebas de atributos de calidad no funcionales**: rendimiento (JMeter, Locust, k6 u otra), usabilidad (usuario externo al equipo con observaciones registradas), o seguridad básica (OWASP Top 10 aplicado al sistema). | | | | | |
| 3B.3 | 🎤 El equipo elaboró una **bitácora de lecciones aprendidas** de T1 a T7: decisiones técnicas buenas y malas, prácticas de proceso que funcionaron, y al menos tres aprendizajes concretos transferibles a un proyecto profesional. | | | | | |

### Bloque 3C — Mejora de la calidad (RA 03 de Calidad)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3C.1 | 👁 Existe un **plan de mejora** con al menos tres acciones correctivas o preventivas concretas: problema que las originó, acción, responsable y estado. | | | | | |
| 3C.2 | 🎤 El equipo demuestra **al menos dos mejoras implementadas** como resultado directo de la verificación de calidad: refactorización, corrección de vulnerabilidad, mejora de tiempo de respuesta, o ajuste basado en pruebas de usabilidad. | | | | | |
| 3C.3 | 🎤 El equipo presenta una **autoevaluación del proceso de desarrollo** de los siete trimestres: nivel de madurez según el referente adoptado, qué mejoró desde T1 y qué queda como oportunidad. El jurado evalúa la calidad del análisis crítico, no si el proceso fue perfecto. | | | | | |

---

## DIMENSIÓN 4 — Documentación de Entrega (20 %)

> En T7 la documentación no es un acompañamiento del software: es parte integral del producto entregable. Un sistema sin documentación de usuario no puede ser operado; sin documentación técnica no puede ser mantenido; sin plan de soporte no puede ser sostenido en el tiempo. El jurado debe evaluar esta dimensión con la misma rigurosidad con que un cliente evaluaría el paquete de entrega de un proveedor de software.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 4.1 | 👁 El **manual técnico** describe arquitectura con diagrama actualizado, stack con versiones exactas, estructura del repositorio, guía de instalación y despliegue paso a paso, descripción de la BD (MER + diccionario) y de los endpoints principales. Suficiente para que un técnico externo mantenga el sistema. | | | | | |
| 4.2 | 👁 El **manual de usuario** cubre todos los roles con sus flujos principales, en lenguaje no técnico, con capturas del sistema real desplegado (no mockups), preguntas frecuentes, y cómo interpretar los mensajes de error más comunes. | | | | | |
| 4.3 | 👁 Existe un **plan de mantenimiento y soporte**: tipos de mantenimiento previstos, frecuencia, procedimientos de respaldo/restauración, criterios de escalamiento y tiempo de respuesta esperado por severidad. | | | | | |
| 4.4 | 👁 El **repositorio está organizado para entrega definitiva** (README como puerta de entrada, carpeta de documentación con manuales/plan de pruebas/informe de calidad, sin archivos temporales ni `node_modules`/`__pycache__` commiteados), y la **documentación de la API** cubre todos los servicios activos con ejemplos de petición y respuesta. | | | | | |

---

## DIMENSIÓN 5 — Proceso, Equipo y Reflexión Final (10 %)

> En el cierre de la etapa lectiva esta dimensión evalúa la madurez del equipo como unidad de trabajo y su capacidad de hacer un balance honesto de siete trimestres de construcción colaborativa. No hay respuestas incorrectas aquí: hay respuestas superficiales (que revelan que no hubo reflexión real) y respuestas profundas (que revelan aprendizaje genuino). El jurado debe escuchar con atención y hacer preguntas que desafíen las respuestas preparadas.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 5.1 | 👁 El **historial del repositorio** en T7 muestra actividad distribuida y coherente entre integrantes hasta la semana de sustentación, sin actividad artificial concentrada en los días previos. | | | | | |
| 5.2 | 🎤 Cada integrante puede **defender el sistema completo** ante el jurado: si se le pregunta sobre un componente que no desarrolló principalmente, puede explicar su propósito, arquitectura básica e integración con el resto. | | | | | |
| 5.3 | 🎤 El equipo presenta una **hoja de ruta hacia la etapa productiva**: funcionalidades pendientes y su priorización, deuda técnica documentada con su impacto real, y qué necesitan hacer para llevar el sistema a producción real. | | | | | |
| 5.4 | 🎤 El equipo hace una **reflexión comparativa de los siete trimestres** con pensamiento crítico genuino: lo más difícil técnicamente y cómo lo superaron, el punto de inflexión en el aprendizaje, y qué llevan como aprendizaje transferible para su primer trabajo. El jurado evalúa la profundidad del análisis, no si el proceso fue exitoso. | | | | | |

---

## Resumen de evaluación

| Dimensión | Peso | Calificación del jurado | Notas |
|-----------|------|-------------------------|-------|
| D1 — Cierre de la Construcción del Software | 20 % | | |
| D2 — Implantación y Despliegue | 25 % | | |
| D3 — Aseguramiento de la Calidad | 25 % | | |
| D4 — Documentación de Entrega | 20 % | | |
| D5 — Proceso, Equipo y Reflexión Final | 10 % | | |

---

## Decisión del jurado

| Decisión | Seleccionar |
|----------|-------------|
| ☐ **Aprobado para etapa productiva** | El sistema y la documentación están en condiciones de ser presentados ante un cliente real en la etapa productiva. |
| ☐ **Aprobado con condicionamientos** | Puede iniciar etapa productiva pero debe resolver los ítems indicados en las primeras semanas. |
| ☐ **Aplazado — plan de mejora** | El grupo tiene hasta [fecha] para resolver los ítems críticos antes de aprobar el cierre de la etapa lectiva. |

### Condicionamientos o ajustes requeridos para ingreso a etapa productiva

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
|-------------------------------|-----------------|--------------|
| | | |
| | | |

---

## Retroalimentación cualitativa del jurado — Cierre de etapa lectiva

| Jurado | Logro más significativo del equipo en los siete trimestres | Recomendación más importante para la etapa productiva |
|--------|--------------------------------------------------------------|----------------------------------------------------------|
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

*Instrumento de evaluación formativa — Programa ADSO 228118 · Oferta Abierta · Trimestre VII — Cierre de etapa lectiva*
*Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital*
