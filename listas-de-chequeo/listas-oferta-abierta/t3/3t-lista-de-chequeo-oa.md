# Lista de Chequeo — Trimestre III

## Seguimiento de Proyecto Formativo · Oferta Abierta

### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Fase del proyecto formativo:** Arquitectura de Software — Proyecto III  
> **Competencias activas este trimestre:**
>
> - Análisis de la Especificación de Requisitos del Software → RA 01: Planear actividades de análisis según la metodología seleccionada
> - Modelado de los Artefactos del Software → RA 01: Elaborar artefactos de diseño · RA 04: Verificar entregables de diseño
> - Construcción del Software (inicio) → RA 02: Construir la BD — resultado parcial
> - Módulos técnicos de soporte: Arquitectura de Software · JavaScript ES6 · REST Backend (Express, FastAPI o Spring Boot) · Consultas SQL (parcial)
>
> **Propósito del trimestre:** Es el trimestre bisagra del programa: cierra la fase de análisis/diseño y abre la fase de construcción real. El equipo debe producir los artefactos de diseño del sistema (diagrama de clases, diagrama de secuencia, arquitectura candidata documentada, vistas de componentes y despliegue), verificarlos formalmente con listas de chequeo internas, avanzar en la construcción de la BD con consultas SQL reales y presentar los primeros módulos de código funcionando: al menos un endpoint REST funcional (usando Express, FastAPI o Spring Boot) y ejercicios funcionales en JavaScript ES6. Es el primer trimestre donde el jurado puede pedir una **demostración en vivo** de código ejecutándose.

---

## Datos de la sesión

| Campo                                     | Valor |
| ----------------------------------------- | ----- |
| Número de Ficha                           |       |
| Nombre del grupo de proyecto              |       |
| Nombre del sistema / software             |       |
| Stack tecnológico declarado por el equipo |       |
| Integrantes presentes                     |       |
| Integrantes ausentes                      |       |
| Fecha de sustentación                     |       |
| Jurado 1                                  |       |
| Jurado 2                                  |       |

---

## Escala de valoración

| Símbolo | Nivel             | Descripción                                                          |
| ------- | ----------------- | ---------------------------------------------------------------------|
| ✅      | **Excelente**     | Cumple completamente con evidencia sólida, demostrable en el momento |
| 🟡      | **Satisfactorio** | Cumple parcialmente o la evidencia es incompleta pero válida         |
| 🔴      | **Insuficiente**  | No cumple, la evidencia es muy débil o ausente                       |
| ➖      | **No aplica**     | El ítem no corresponde al tipo o contexto de este proyecto           |

**Tiers de verificación** (ver [6.tiempos-de-sesion.md](../../../6.tiempos-de-sesion.md)): 🎤 verificación viva (demo/explicación oral, 1-1.5 min) · 👁 inspección rápida (vistazo binario, 20-30 seg).

---

## Ponderación por dimensión

| Dimensión                        | Peso |
| -------------------------------- | ---- |
| D1 — Gestión del Proyecto        | 15 % |
| D2 — Artefactos Técnicos         | 45 % |
| D3 — Documentación               | 20 % |
| D4 — Trabajo en Equipo           | 10 % |
| D5 — Calidad y Mejores Prácticas | 10 % |

> **Nota sobre el peso:** En T3 el peso de artefactos técnicos sube a 45 % porque este es el trimestre donde por primera vez conviven artefactos de diseño (diagramas) y código ejecutable. El jurado tiene la obligación de verificar que ambos tipos de evidencia estén presentes y sean coherentes entre sí. La gestión baja ligeramente a 15 % porque se asume que el equipo ya la internalizó en T1 y T2; lo que se evalúa ahora es que la usa de manera autónoma.

---

## Distribución del tiempo de sesión (20 min)

| Bloque | Minutos |
| --- | --- |
| Contexto y datos de sesión | 1 |
| 🎤 Demo en vivo + preguntas (10 ítems 🎤, bloque serial) | 13 |
| 👁 Inspección rápida — en paralelo durante el bloque 🎤 (Jurado 2), no resta minutos | — |
| Retroalimentación, decisión y firmas | 4 |
| **Total** | **18-20** |

---

## DIMENSIÓN 1 — Gestión del Proyecto (15 %)

> A estas alturas el equipo debe gestionar simultáneamente artefactos de diseño y tareas de construcción. El tablero de seguimiento debería reflejar esa dualidad: no solo "completar diagrama de clases" sino también "implementar endpoint de autenticación" con criterio de aceptación verificable.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                       | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 1.1 | 👁 El **tablero de seguimiento** está actualizado a la fecha de la sustentación, distingue tareas de diseño de tareas de construcción y muestra el estado real de cada una (pendiente / en progreso / terminado). El equipo no debería mostrar un tablero recién ordenado para la presentación. |     |     |     |     |                          |
| 1.2 | 👁 El equipo ha completado al menos **dos sprints documentados** durante el trimestre. Cada sprint tiene objetivo definido, lista de historias comprometidas y acta o evidencia del sprint review con lo logrado y lo que quedó pendiente.                                                      |     |     |     |     |                          |
| 1.3 | 🎤 El equipo puede presentar una **retrospectiva** del trimestre (qué funcionó, qué no, qué van a cambiar en T4) y describir al menos un **riesgo** que identificó durante el trimestre y cómo lo manejó.                                                                          |     |     |     |     |                          |

---

## DIMENSIÓN 2 — Artefactos Técnicos (45 %)

> Esta dimensión evalúa cinco frentes simultáneos. El jurado debe verificar cada bloque de manera independiente: un equipo puede tener artefactos de diseño excelentes y código débil, o viceversa. La coherencia entre bloques también se evalúa en D5.

### Bloque 2A — Artefactos de diseño del software (RA 01 de Modelado)

> El diseño orientado a objetos en este trimestre no es solo "dibujar diagramas": es tomar decisiones técnicas fundamentadas sobre cómo se va a construir el sistema. El jurado debe verificar que los diagramas reflejan decisiones reales, no plantillas copiadas.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                     | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2A.1 | 👁 Existe un **diagrama de clases de diseño** en UML con atributos tipados, métodos con firma completa, modificadores de acceso (+, -, #) y relaciones de herencia, composición, agregación y dependencia donde corresponde. Coherente con el modelo de dominio del T2. |     |     |     |     |                          |
| 2A.2 | 🎤 El diagrama de clases incorpora al menos **un patrón de diseño GOF** (Factory, Singleton, Observer, Strategy, Facade u otro) y el equipo explica qué problema del sistema resuelve ese patrón y por qué eligió ese y no otro.                                                                 |     |     |     |     |                          |
| 2A.3 | 👁 Existen **diagramas de secuencia** para los tres flujos más importantes del sistema (por ejemplo: inicio de sesión, creación del recurso principal, generación de un reporte), con interacción entre objetos y mensajes síncronos/asincrónicos.                                       |     |     |     |     |                          |
| 2A.4 | 👁 Existen **diagrama de componentes** (módulos del sistema e interfaces de comunicación) y **diagrama de despliegue** (nodos de infraestructura y distribución de componentes), coherentes con la arquitectura declarada.                                                                                            |     |     |     |     |                          |
| 2A.5 | 🎤 El equipo puede describir la **arquitectura candidata** del sistema: patrón arquitectónico principal (MVC, capas, REST + SPA, etc.), justificación en términos de atributos de calidad (escalabilidad, mantenibilidad, seguridad) y plataformas tecnológicas seleccionadas para cada capa.             |     |     |     |     |                          |

### Bloque 2B — Verificación de entregables de diseño (RA 04 de Diseño)

> Este resultado de aprendizaje es poco visible en las sustentaciones porque los equipos lo omiten o lo confunden con "revisar el documento antes de imprimirlo". El RA exige un proceso formal de verificación: listas de chequeo internas, criterios de aceptación de los artefactos y evidencia de los ajustes realizados tras la revisión.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                               | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2B.1 | 👁 El equipo elaboró y aplicó una **lista de chequeo de verificación** sobre sus propios artefactos de diseño, con criterios concretos (¿atributos tipados? ¿relaciones UML bien representadas? ¿el diagrama de secuencia cubre flujos alternativos?). |     |     |     |     |                          |
| 2B.2 | 👁 Existe un **registro de hallazgos** de la verificación: al menos tres ítems que el equipo encontró inconsistentes o incompletos en sus artefactos durante la revisión interna, con la corrección aplicada.                                                                               |     |     |     |     |                          |
| 2B.3 | 🎤 El equipo puede demostrar **trazabilidad de diseño**: si el jurado elige un requisito funcional del SRS, el equipo puede identificar el caso de uso correspondiente (T2), el diagrama de secuencia que lo detalla (T3) y la clase o clases responsables de su implementación.                        |     |     |     |     |                          |

### Bloque 2C — Base de datos: consultas SQL (RA 02 de Construcción de BD — resultado parcial)

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                           | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 2C.1 | 👁 La base de datos está **creada y poblada con datos de prueba** en el motor seleccionado (PostgreSQL, MySQL u otro), demostrable en la herramienta de administración (pgAdmin, MySQL Workbench, DBeaver u otra), y existe un conjunto de **scripts SQL DDL** versionados que reconstruyen el esquema completo desde una BD vacía.                             |     |     |     |     |                          |
| 2C.2 | 🎤 El equipo domina las **consultas DML esenciales** (SELECT con WHERE, ORDER BY, JOIN, agregaciones, GROUP BY/HAVING) y tiene al menos **tres consultas específicas del proyecto** (no genéricas) documentadas y versionadas en el repositorio, que puede escribir o explicar en el momento.                                                                                                        |     |     |     |     |                          |

### Bloque 2D — REST Backend: primer servicio funcional (Express, FastAPI o Spring Boot)

> El equipo elige la tecnología backend que mejor se alinee con su arquitectura declarada. Lo que se evalúa aquí no es la tecnología específica, sino que el equipo demuestre un backend REST funcional con integración a BD, arquitectura clara y calidad de código.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                  | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2D.1 | 🎤 El equipo tiene un **servidor REST funcional** (Express, FastAPI o Spring Boot) que arranca sin errores. El jurado puede solicitar una demostración en vivo: ejecutar el proyecto y verificar que el servidor inicia correctamente sin excepciones.                                                     |     |     |     |     |                          |
| 2D.2 | 👁 El servidor implementa al menos **un CRUD completo** (Create, Read, Update, Delete) para el recurso principal del sistema, con los verbos HTTP correctos y respuestas JSON bien estructuradas.                                                                                                                           |     |     |     |     |                          |
| 2D.3 | 👁 El proyecto sigue **arquitectura clara en capas** (rutas/controladores, servicios, acceso a datos) y está **integrado con la base de datos** mediante el ORM o driver apropiado para la tecnología elegida (Spring Data JPA, SQLAlchemy, Sequelize/Prisma). No hay lógica de negocio mezclada con las rutas. |     |     |     |     |                          |
| 2D.4 | 👁 Los endpoints pueden ser **probados con Postman o Thunder Client**: el equipo tiene una colección de peticiones exportada y disponible en el repositorio que demuestra el funcionamiento del CRUD.                                                                                                                        |     |     |     |     |                          |

### Bloque 2E — JavaScript ES6: fundamentos del frontend

| #    | Criterio de evaluación                                                                                                                                                                                                                | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2E.1 | 👁 El equipo muestra **scripts JS funcionales** que usen sintaxis ES6 correcta (`let`/`const`, arrow functions, template strings, desestructuración) y el código está **organizado en módulos** (`import`/`export`) con al menos dos archivos separados por responsabilidad.                    |     |     |     |     |                          |
| 2E.2 | 👁 Existen ejercicios o módulos del proyecto que demuestran el uso de **métodos modernos de arreglos**: `map`, `filter`, `reduce`, con un caso concreto relacionado con los datos del sistema (no solo con arrays de números genéricos). |     |     |     |     |                          |
| 2E.3 | 🎤 El equipo puede explicar y demostrar **manejo de asincronismo** con Promesas o `async/await`, típicamente una llamada a la API REST del proyecto desde JavaScript.                |     |     |     |     |                          |

---

## DIMENSIÓN 3 — Documentación (20 %)

> En T3 la documentación debe servir como puente entre los artefactos de diseño y el código. Un documento de diseño bien hecho permite que cualquier integrante del equipo retome el trabajo de otro sin tener que preguntarle. El jurado debe verificar que la documentación cumple esa función.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                 | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 3.1 | 👁 Existe un **documento de diseño** (Software Design Document o equivalente) que consolida todos los artefactos de diseño del trimestre: arquitectura candidata, diagrama de clases, diagramas de secuencia, componentes y despliegue. Estructurado, con control de versiones y legible por alguien externo al equipo. |     |     |     |     |                          |
| 3.2 | 👁 El **repositorio refleja una estructura de carpetas coherente** con la arquitectura declarada, y el `README.md` está **actualizado para T3** con instrucciones de instalación local: requisitos de software, dependencias, motor de BD, y cómo ejecutar el backend y poblar la BD con el script DDL.                     |     |     |     |     |                          |
| 3.3 | 👁 Los **commits del repositorio** siguen un patrón de mensaje convencional o al menos descriptivo. El historial muestra una evolución real del proyecto durante las semanas del trimestre, no picos de actividad justo antes de la sustentación.                                                         |     |     |     |     |                          |
| 3.4 | 👁 La **colección de Postman** para probar los endpoints está exportada como archivo JSON en el repositorio, con al menos los casos de prueba del CRUD principal y sus respuestas esperadas documentadas como ejemplos.                                                                                                                                   |     |     |     |     |                          |

---

## DIMENSIÓN 4 — Trabajo en Equipo (10 %)

> Se observa en simultáneo con las demos de D2, sin tiempo adicional en la sesión.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                     | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 4.1 | 👁 El **historial de commits por integrante** muestra contribuciones reales distribuidas: hay commits de al menos el 80 % del equipo en el período del trimestre. El jurado puede revisar la pestaña de Insights → Contributors del repositorio durante la sesión.            |     |     |     |     |                          |
| 4.2 | 👁 El equipo usa **ramas (branches)** para el desarrollo: se puede ver en el historial del repositorio que las funcionalidades se desarrollaron en ramas separadas y se integraron por medio de merges o pull requests.                                                       |     |     |     |     |                          |
| 4.3 | 🎤 Durante la sustentación, **todos los integrantes presentes demuestran conocimiento** del proyecto completo: si el jurado pregunta a un integrante de frontend sobre la arquitectura de la BD, debe poder responder con coherencia básica, aunque no sea su área principal. |     |     |     |     |                          |
| 4.4 | 🎤 El equipo puede mostrar **al menos una decisión técnica tomada colectivamente** durante el trimestre: qué patrón de diseño usar, qué motor de BD elegir, cómo estructurar las capas del backend. El equipo explica el proceso de discusión y argumenta la decisión final.  |     |     |     |     |                          |

---

## DIMENSIÓN 5 — Calidad y Mejores Prácticas (10 %)

> T3 es el primer trimestre donde la calidad del código es evaluable directamente. No se busca perfección: se busca evidencia de que el equipo tiene criterio de calidad y lo aplica de manera consciente.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                   | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 5.1 | 🎤 Los **diagramas de diseño son coherentes con el código**: si el diagrama de clases declara una entidad con ciertos atributos o un servicio con ciertos métodos, esa estructura debe existir en el código. El jurado hace una verificación cruzada al azar.                                                        |     |     |     |     |                          |
| 5.2 | 👁 El código aplica principios básicos de **Clean Code** (responsabilidad única, nombres descriptivos, sin comentado masivo, sin números mágicos) y **buenas prácticas de ES6** (sin `var`, sin funciones anónimas innecesariamente largas, uso de `map`/`filter` donde corresponde).                                                                       |     |     |     |     |                          |
| 5.3 | 👁 La API REST sigue **convenciones REST básicas**: rutas con sustantivos en plural, verbos HTTP correspondientes a la acción, y códigos de respuesta HTTP correctos (200, 201, 400, 404, 500). |     |     |     |     |                          |
| 5.4 | 👁 El equipo tiene un **estándar de codificación documentado** (archivo `CONTRIBUTING.md` o documento en la carpeta de documentación) que define convenciones de nombres, estructura de carpetas y reglas de commit.                                                                      |     |     |     |     |                          |

---

## Resumen de evaluación

| Dimensión                        | Peso | Calificación del jurado | Notas |
| -------------------------------- | ---- | ----------------------- | ----- |
| D1 — Gestión del Proyecto        | 15 % |                         |       |
| D2 — Artefactos Técnicos         | 45 % |                         |       |
| D3 — Documentación               | 20 % |                         |       |
| D4 — Trabajo en Equipo           | 10 % |                         |       |
| D5 — Calidad y Mejores Prácticas | 10 % |                         |       |

---

## Decisión del jurado

| Decisión                             | Seleccionar                                                                                    |
| ------------------------------------ | ---------------------------------------------------------------------------------------------- |
| ☐ **Aprobado sin condiciones**       | El equipo continúa al T4 con el proyecto vigente.                                              |
| ☐ **Aprobado con condicionamientos** | Continúa pero debe resolver los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora**      | El grupo tiene hasta [fecha] para subsanar los ítems críticos y presentar nuevamente.          |

### Condicionamientos o ajustes requeridos

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
| ------------------------------ | ---------------- | ------------ |
|                                |                  |              |
|                                |                  |              |

---

## Retroalimentación cualitativa del jurado

| Jurado   | Fortaleza principal observada este trimestre | Riesgo más importante a gestionar en T4 |
| -------- | -------------------------------------------- | --------------------------------------- |
| Jurado 1 |                                              |                                         |
| Jurado 2 |                                              |                                         |

---

## Firmas

| Rol                                                    | Nombre completo | Firma |
| ------------------------------------------------------ | --------------- | ----- |
| Jurado 1                                               |                 |       |
| Jurado 2                                               |                 |       |
| Vocero del grupo (constancia de recibido del feedback) |                 |       |

---

_Instrumento de evaluación formativa — Programa ADSO 228118 · Oferta Abierta · Trimestre III_  
_Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital_
