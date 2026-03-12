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

## DIMENSIÓN 1 — Cierre de la Construcción del Software (20 %)

> Esta dimensión cierra definitivamente el RA 01 de Construcción (planeación) que ha venido como resultado parcial desde T6, y evalúa el estado final del código del proyecto. No se esperan funcionalidades nuevas revolucionarias en T7: se espera un sistema terminado, limpio, estable y con la deuda técnica documentada y gestionada.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 1.1 | El sistema completo **funciona de manera integrada y estable**: todos los componentes activos (frontend, cuatro backends, BD relacional, BD NoSQL) operan sin errores críticos en el entorno desplegado. El jurado puede solicitar la ejecución de cualquier caso de uso del sistema durante la sesión y el equipo debe poder demostrarlo sin intervención de corrección en el momento. | | | | | |
| 1.2 | El equipo presenta el **estado final del backlog del proyecto**: porcentaje de historias de usuario completadas respecto al SRS original, con una justificación documentada y honesta para las historias que quedaron fuera del alcance de la etapa lectiva. La deuda de alcance no es un problema per se; no tenerla documentada sí lo es. | | | | | |
| 1.3 | El **plan de construcción final** está documentado: incluye la lista de funcionalidades entregadas en T7, las actividades de estabilización realizadas (corrección de defectos residuales, optimizaciones mínimas, limpieza de código), y la descripción de lo que queda pendiente para la etapa productiva con su prioridad. | | | | | |
| 1.4 | El código fuente está **limpio y organizado para entrega definitiva**: no hay archivos de depuración, ramas de experimentos sin cerrar, código comentado masivamente que revele iteraciones sin resolver, ni `console.log` / `print` de desarrollo en el código de producción. El repositorio en su estado actual debe poder entregarse a un cliente sin vergüenza técnica. | | | | | |
| 1.5 | El sistema implementa **seguridad básica verificable**: las contraseñas están almacenadas con hash (bcrypt u otro), los tokens JWT tienen tiempo de expiración definido, las consultas a BD usan ORM o consultas parametrizadas (sin vulnerabilidades de inyección SQL), y las rutas protegidas rechazan correctamente peticiones sin autenticación válida. | | | | | |

---

## DIMENSIÓN 2 — Implantación y Despliegue (25 %)

> La implantación es la competencia que más frecuentemente los aprendices subestiman porque asumen que "terminar el código" es el destino final. T7 les demuestra que el software que solo corre en el laptop del desarrollador no le sirve a nadie. Esta dimensión evalúa los cuatro RA de Implantación de manera secuencial: primero la planeación, luego el despliegue real, luego la documentación del proceso, y finalmente la entrega formal con capacitación y pruebas de aceptación.

### Bloque 2A — Planeación de la implantación (RA 01 de Implantación)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2A.1 | Existe un **plan de implantación documentado** que describe como mínimo: las actividades de despliegue con su secuencia y responsables, los requisitos de infraestructura del sistema (hardware mínimo, sistema operativo, puertos requeridos, servicios de terceros), los criterios de éxito de la implantación, y el plan de contingencia para el caso en que algo falle durante el despliegue. | | | | | |
| 2A.2 | El plan incluye una **estrategia de migración de datos** o describe explícitamente por qué no aplica: si el sistema reemplaza a uno anterior o importa datos desde fuentes externas, hay un procedimiento documentado. Si el sistema es completamente nuevo sin datos previos, esa decisión está justificada en el plan. | | | | | |
| 2A.3 | El plan define una **estrategia de copias de seguridad**: qué datos son críticos, con qué frecuencia se respaldan, dónde se almacenan los respaldos (separados del servidor principal), y cómo se ejecuta una restauración desde una copia de seguridad. Aunque sea un entorno de prueba, la estrategia debe ser técnicamente viable y coherente con el sistema. | | | | | |

### Bloque 2B — Despliegue del sistema (RA 02 de Implantación)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2B.1 | El sistema está **desplegado en un entorno diferente al local** de desarrollo: nube (Railway, Render, AWS, GCP, Azure, Fly.io u otro), servidor del centro de formación, o un entorno Docker Compose reproducible. El jurado puede acceder al sistema desplegado desde un navegador durante la sesión usando la URL declarada en la portada. | | | | | |
| 2B.2 | El despliegue usa **separación de configuración por ambiente**: las variables sensibles (cadenas de conexión, claves secretas, credenciales de servicios) están en variables de entorno del servidor y no en el repositorio de código. Existe un archivo `.env.example` con las variables requeridas documentadas (sin valores reales). | | | | | |
| 2B.3 | El equipo puede demostrar que el sistema se **puede desplegar desde cero** siguiendo únicamente las instrucciones del manual de instalación: clonar el repositorio, configurar las variables de entorno, ejecutar los scripts de BD y levantar los servicios. No debe requerir conocimiento implícito que solo tiene el equipo. | | | | | |
| 2B.4 | Si el proyecto usa **contenedores Docker**, existe un `Dockerfile` por servicio y un `docker-compose.yml` funcional que levanta todo el sistema con un solo comando. Si no usa contenedores, existe un script de instalación o un README de despliegue con pasos verificados por el equipo en un ambiente limpio. | | | | | |

### Bloque 2C — Implantación con el cliente (RA 04 de Implantación)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2C.1 | El equipo elaboró un **plan de capacitación de usuarios** que define: los perfiles de usuario a capacitar (administrador, usuario regular, otros roles del sistema), los temas de cada sesión de capacitación, la duración estimada, los materiales de apoyo preparados y los criterios para considerar que el usuario fue capacitado exitosamente. | | | | | |
| 2C.2 | El equipo puede presentar o demostrar al menos **una sesión de capacitación simulada**: el equipo asume el rol de capacitador y guía a los jurados (en el rol de usuarios finales) a través de las funcionalidades principales del sistema, usando el sistema real desplegado y el manual de usuario como soporte. | | | | | |
| 2C.3 | Existen **pruebas de aceptación documentadas**: al menos cinco casos de uso verificados con el cliente simulado (jurado o instructor que asume ese rol), con el resultado de cada prueba registrado (aceptado / rechazado / aceptado con observaciones) y la firma o constancia de quien actuó como cliente. | | | | | |

---

## DIMENSIÓN 3 — Aseguramiento de la Calidad (25 %)

> Esta dimensión cubre los tres RA de la competencia de Buenas Prácticas, que operan en secuencia obligatoria: incorporar prácticas de calidad → verificar que el software las cumple → mejorar a partir de los resultados. El jurado debe verificar que el equipo ejecutó esas tres fases de manera real y documentada, no que las declaró en un documento de presentación.

### Bloque 3A — Incorporación de estándares de calidad (RA 01 de Calidad)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3A.1 | El equipo adoptó al menos **un estándar o referente de calidad reconocido** para el proceso de desarrollo del proyecto: puede ser ISO/IEC 25010 (modelo de calidad del producto), CMMI (niveles de madurez de proceso), PSP (proceso personal de software), o una selección documentada de prácticas de XP o Scrum con justificación. La adopción es real si el equipo puede mostrar cómo ese estándar influyó en decisiones concretas del proyecto. | | | | | |
| 3A.2 | El equipo tiene un **plan de aseguramiento de calidad (PAC)** del proyecto que define: los atributos de calidad priorizados para el sistema (funcionalidad, fiabilidad, usabilidad, eficiencia, mantenibilidad, portabilidad u otros de ISO 25010), las actividades de QA incorporadas al proceso de construcción, y las métricas usadas para medirlos. | | | | | |
| 3A.3 | El repositorio tiene configurado al menos un **pipeline de integración continua (CI)** que ejecuta pruebas automatizadas en cada push o pull request a la rama principal. El equipo puede mostrar el historial de ejecuciones del pipeline. Si CI completo no es técnicamente viable en el entorno del equipo, existe al menos un script que ejecuta todas las pruebas con un solo comando y el equipo puede demostrarlo. | | | | | |

### Bloque 3B — Verificación de la calidad (RA 02 de Calidad)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3B.1 | Existe un **informe de evaluación de calidad** del sistema que evalúa el cumplimiento de los requisitos no funcionales definidos en el SRS: tiempo de respuesta de los endpoints más usados, disponibilidad del sistema desplegado, comportamiento bajo carga básica, y al menos dos atributos de calidad del modelo adoptado con sus métricas medidas vs. sus metas. | | | | | |
| 3B.2 | Se realizaron **pruebas de los atributos de calidad no funcionales**: hay evidencia de al menos una prueba de rendimiento (tiempo de respuesta de un endpoint bajo múltiples peticiones, usando JMeter, Locust, k6 u otra herramienta), una prueba de usabilidad (al menos un usuario externo al equipo usó el sistema y sus observaciones fueron registradas), o una evaluación de seguridad básica (OWASP Top 10 checklist aplicada al sistema). | | | | | |
| 3B.3 | El equipo elaboró una **bitácora de lecciones aprendidas** del proyecto completo (T1 a T7) que documenta: decisiones técnicas que resultaron buenas y por qué, decisiones que generaron problemas y qué hubieran hecho diferente, prácticas de proceso que funcionaron y cuáles no, y al menos tres aprendizajes concretos que el equipo llevaría a un proyecto profesional real. | | | | | |

### Bloque 3C — Mejora de la calidad (RA 03 de Calidad)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3C.1 | Existe un **plan de mejora** documentado que nace de los resultados de la verificación de calidad: al menos tres acciones correctivas o preventivas concretas, con el problema que las originó, la acción implementada o propuesta, el responsable y el estado (implementada antes del cierre de T7 o propuesta para la etapa productiva con justificación). | | | | | |
| 3C.2 | El equipo puede demostrar **al menos dos mejoras implementadas** como resultado directo del proceso de verificación de calidad: refactorización de un módulo que tenía alta complejidad ciclomática, corrección de una vulnerabilidad detectada en la evaluación de seguridad, mejora del tiempo de respuesta de un endpoint lento, o ajuste de la interfaz basado en las observaciones de la prueba de usabilidad. | | | | | |
| 3C.3 | El equipo puede presentar una **autoevaluación del proceso de desarrollo** a lo largo de los siete trimestres: en qué nivel de madurez sitúa su proceso (usando el referente adoptado), qué mejoró significativamente desde T1 y qué quedó como área de oportunidad para la etapa productiva. El jurado evalúa la calidad del análisis crítico, no si el proceso fue perfecto. | | | | | |

---

## DIMENSIÓN 4 — Documentación de Entrega (20 %)

> En T7 la documentación no es un acompañamiento del software: es parte integral del producto entregable. Un sistema sin documentación de usuario no puede ser operado; sin documentación técnica no puede ser mantenido; sin plan de soporte no puede ser sostenido en el tiempo. El jurado debe evaluar esta dimensión con la misma rigurosidad con que un cliente evaluaría el paquete de entrega de un proveedor de software.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 4.1 | El **manual técnico** del sistema está completo y describe: arquitectura del sistema con diagrama actualizado, stack tecnológico con versiones exactas, estructura del repositorio, descripción de cada componente, guía de instalación y despliegue paso a paso, descripción de la base de datos (modelo entidad-relación + diccionario de datos), y descripción de los endpoints principales de la API. Debe ser suficiente para que un técnico de sistemas externo al equipo pueda instalar, configurar y mantener el sistema. | | | | | |
| 4.2 | El **manual de usuario** cubre todos los roles del sistema con sus flujos principales: está escrito en lenguaje no técnico, usa capturas de pantalla actualizadas del sistema real desplegado (no mockups ni capturas del entorno local), tiene una sección de preguntas frecuentes, y describe cómo el usuario debe interpretar y reaccionar ante los mensajes de error más comunes del sistema. | | | | | |
| 4.3 | Existe un **plan de mantenimiento y soporte** del sistema: define los tipos de mantenimiento previstos (correctivo, preventivo, adaptativo, perfectivo), la frecuencia de cada uno, los procedimientos de respaldo y restauración, los criterios para escalar un problema al equipo de desarrollo, y el tiempo de respuesta esperado para incidentes de diferente severidad. | | | | | |
| 4.4 | El **repositorio está organizado para entrega definitiva**: el README es la puerta de entrada al sistema y tiene acceso a todos los documentos; la carpeta de documentación contiene los manuales, el plan de pruebas, el informe de calidad y el plan de implantación; los scripts de BD están organizados en orden de ejecución; y no hay archivos temporales, carpetas de prueba vacías ni `node_modules` / `__pycache__` commiteados por error. | | | | | |
| 4.5 | La **documentación de la API** está disponible en el sistema desplegado o en el repositorio: Swagger UI accesible en el ambiente de producción, colección Postman exportada con todos los endpoints, o una especificación OpenAPI generada automáticamente. La documentación cubre todos los servicios activos del sistema (Spring Boot, FastAPI, Express, Flask) con ejemplos de petición y respuesta para cada endpoint. | | | | | |

---

## DIMENSIÓN 5 — Proceso, Equipo y Reflexión Final (10 %)

> En el cierre de la etapa lectiva esta dimensión evalúa la madurez del equipo como unidad de trabajo y su capacidad de hacer un balance honesto de siete trimestres de construcción colaborativa. No hay respuestas incorrectas aquí: hay respuestas superficiales (que revelan que no hubo reflexión real) y respuestas profundas (que revelan aprendizaje genuino). El jurado debe escuchar con atención y hacer preguntas que desafíen las respuestas preparadas.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 5.1 | El **historial del repositorio** en T7 muestra actividad distribuida y coherente: hay commits de construcción, de corrección de defectos y de documentación, distribuidos entre los integrantes hasta la semana de sustentación. La proporción de commits por integrante es razonablemente equilibrada y el log no muestra actividad artificial concentrada en los días anteriores a la presentación. | | | | | |
| 5.2 | Cada integrante puede **defender el sistema completo** ante el jurado: si se le pregunta sobre un componente que no desarrolló principalmente, puede explicar su propósito, su arquitectura básica y cómo se integra con el resto. La especialización es válida y esperable; el desconocimiento total de componentes del sistema propio no es aceptable en el cierre lectivo. | | | | | |
| 5.3 | El equipo puede presentar una **hoja de ruta hacia la etapa productiva** con criterio técnico: qué funcionalidades quedan pendientes y por qué se priorizaron así, qué deuda técnica existe documentada y cuál es su impacto real en el sistema, qué mejorarían de la arquitectura si empezaran de nuevo, y qué necesitan hacer en la etapa productiva para llevar el sistema a un estado de producción real frente a un cliente externo. | | | | | |
| 5.4 | El equipo puede hacer una **reflexión comparativa de los siete trimestres** con pensamiento crítico genuino: qué fue lo más difícil técnicamente del programa y cómo lo superaron, qué trimestre fue el punto de inflexión en el aprendizaje del equipo, cómo cambió su forma de trabajar desde T1 hasta T7, y qué llevan como aprendizaje transferible para su primer trabajo como tecnólogos. El jurado evalúa la profundidad del análisis, no si el proceso fue exitoso. | | | | | |

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
|--------|------------------------------------------------------------|-------------------------------------------------------|
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