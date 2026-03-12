# Lista de Chequeo — Trimestre V
## Seguimiento de Proyecto Formativo · Oferta Abierta
### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Fase del proyecto formativo:** Construcción del Software — Proyecto V
>
> **Resultados de Aprendizaje activos este trimestre:**
> - Construcción del Software → RA 04: Codificar el software de acuerdo con el diseño — **resultado parcial** (módulos: REST Express + Desarrollo Móvil optativo)
> - Construcción del Software → RA 02: Construir la base de datos para el software a partir del modelo de datos — **resultado FINAL** (NoSQL: MongoDB y/o Redis)
>
> **Módulos técnicos activos:**
> - REST JavaScript con Express — tercer backend del programa, obligatorio (6 h/sem)
> - Gestión de Bases de Datos No Relacionales con MongoDB y/o Redis — cierre definitivo del RA de BD, obligatorio (6 h/sem)
> - Fundamentos de Desarrollo Móvil con React Native — **módulo deseable, no obligatorio** (12 h/sem cuando se activa)
>
> **Propósito del trimestre:** T5 consolida la construcción del sistema con un tercer backend REST en JavaScript/Express que complementa los backends anteriores (Spring Boot en T3 y FastAPI en T4), y cierra definitivamente el RA de bases de datos con la integración de un motor NoSQL al proyecto. El componente móvil es un enriquecimiento del proyecto formativo: si el equipo lo incorpora, amplía el alcance del sistema y demuestra dominio de React Native; si no lo incorpora, el proyecto sigue siendo válido y completo. La pregunta central del trimestre es: **¿el sistema ahora tiene todos sus componentes de datos integrados — relacional y no relacional — y un nuevo servicio backend funcionando de manera coherente con lo construido en T3 y T4?**

---

## Datos de la sesión

| Campo | Valor |
|-------|-------|
| Número de Ficha | |
| Nombre del grupo de proyecto | |
| Nombre del sistema / software | |
| Stack tecnológico activo en T5 | |
| URL del repositorio | |
| ¿El proyecto incorpora componente móvil? | Sí ☐ / No ☐ |
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

| Dimensión | Peso (sin móvil) | Peso (con móvil) |
|-----------|-----------------|-----------------|
| D1 — Gestión del Proyecto | 10 % | 10 % |
| D2 — Artefactos Técnicos | 50 % | 45 % |
| D3 — Documentación | 15 % | 15 % |
| D4 — Trabajo en Equipo | 10 % | 10 % |
| D5 — Calidad y Mejores Prácticas | 15 % | 15 % |
| **Bloque optativo — Desarrollo Móvil** | — | **+5 % bonificación** |

> **Nota pedagógica:** Cuando el proyecto incorpora el componente móvil, el Bloque 2D se evalúa como bonificación sobre el total de D2, lo que puede llevar esa dimensión hasta 50 % efectivo. Esto reconoce el esfuerzo adicional sin penalizar a los equipos que no lo incorporan. El jurado debe marcar claramente al inicio de la sesión si el Bloque 2D aplica o no, según la declaración del equipo.

---

## DIMENSIÓN 1 — Gestión del Proyecto (10 %)

> En T5 el equipo trabaja en dos o tres frentes técnicos simultáneos. La gestión se evalúa principalmente en su capacidad de planear trabajo paralelo sin que un frente bloquee a otro, y de mantener la coherencia del proyecto como sistema integrado a pesar de la dispersión tecnológica del trimestre.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 1.1 | El **tablero de seguimiento** distingue visiblemente las tareas de Express, NoSQL y (si aplica) móvil. El estado de cada frente es verificable de manera independiente. No hay un único carril genérico de "desarrollo" que mezcla todo sin contexto. | | | | | |
| 1.2 | El equipo tiene al menos **dos sprints documentados** del trimestre con sus objetivos, compromisos y resultados. Si algún sprint no cumplió su objetivo, la razón está documentada y el equipo puede describirla con honestidad técnica. | | | | | |
| 1.3 | El equipo puede describir cómo **coordinó la integración entre los módulos**: cómo decidió qué datos maneja Express versus FastAPI, cómo definió qué colecciones MongoDB complementan el esquema relacional, y si hay un documento o decisión registrada que explique la arquitectura de datos completa del sistema. | | | | | |
| 1.4 | El **backlog total del proyecto** está actualizado: el equipo sabe cuántas historias de usuario están completadas acumulando T1 a T5, cuántas quedan para T6 y T7, y si el alcance original del SRS sigue siendo realista para el tiempo restante. Si hay ajustes de alcance, están documentados y justificados. | | | | | |

---

## DIMENSIÓN 2 — Artefactos Técnicos (50 % / 45 % con móvil)

### Bloque 2A — REST con JavaScript / Express: tercer backend del sistema (RA 04 parcial)

> Express es el tercer backend del programa, después de Spring Boot (T3) y FastAPI (T4). El equipo ya tiene experiencia construyendo APIs REST: lo que se evalúa en T5 no es si saben hacer un CRUD básico, sino si saben articular un tercer servicio al sistema existente con una responsabilidad clara y diferenciada. Un servicio Express que duplica exactamente lo que ya hace FastAPI no aporta valor arquitectónico al sistema.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2A.1 | El servidor Express **arranca sin errores** y el jurado puede verificarlo en el momento. Los módulos de rutas están organizados por dominio en archivos separados, y el archivo de entrada (`app.js` o `index.js`) solo contiene la configuración del servidor, no lógica de negocio. | | | | | |
| 2A.2 | El equipo puede justificar **por qué existe este servicio Express** en la arquitectura del sistema y qué responsabilidad tiene que no está cubierta por los backends anteriores. Las respuestas aceptables incluyen: manejo de eventos en tiempo real con WebSockets, servicio de notificaciones, pasarela de API, integración con servicios externos, lógica de dominio diferenciada. La respuesta inaceptable es "porque el módulo lo pedía". | | | | | |
| 2A.3 | El servicio implementa al menos **un recurso REST completo** específico del proyecto con los verbos HTTP correctos, códigos de respuesta semánticos y respuestas JSON consistentes con el estándar del resto de la API del sistema. | | | | | |
| 2A.4 | El servicio tiene **middleware de autenticación JWT** funcionando: las rutas protegidas verifican el token antes de ejecutar la lógica, y ese token es el mismo que emite el backend principal del sistema (no hay dos sistemas de login paralelos sin razón). | | | | | |
| 2A.5 | El servicio tiene **manejo de errores centralizado** con un middleware de error: los errores de validación, autenticación y excepciones no esperadas producen respuestas JSON con estructura consistente (código HTTP correcto + mensaje descriptivo) en lugar de stack traces expuestos. | | | | | |
| 2A.6 | El proyecto tiene un archivo `package.json` actualizado con todas las dependencias declaradas, un script `start` funcional y un archivo `.env.example` con las variables de entorno requeridas. El equipo puede demostrar que el servicio arranca desde cero con `npm install` y el comando de inicio documentado. | | | | | |

### Bloque 2B — Bases de Datos No Relacionales: MongoDB y/o Redis (RA 02 — resultado FINAL)

> Este es el RA que se cierra definitivamente en T5. A diferencia de los RA parciales, un resultado FINAL no admite "estamos avanzando" ni "lo terminamos en T6". El jurado debe evaluar este bloque con la misma rigurosidad con que evaluaría un entregable de cierre: el equipo domina el motor NoSQL elegido, lo tiene integrado al sistema real del proyecto, y puede demostrar su funcionamiento en el momento.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2B.1 | El equipo tiene una **justificación técnica documentada** de por qué el proyecto usa NoSQL: qué tipo de datos se almacenan en el motor no relacional, por qué ese tipo de datos encaja mejor en un modelo de documentos o clave-valor que en el modelo relacional, y qué ventaja concreta aporta la solución NoSQL al sistema. Esta justificación debe ser específica del proyecto, no una definición genérica de NoSQL copiada de Wikipedia. | | | | | |
| 2B.2 | La instancia del motor NoSQL elegido está **corriendo y conectada al sistema**: el jurado puede solicitar que el equipo abra MongoDB Compass, RedisInsight u otra herramienta de administración y muestre los datos reales del proyecto almacenados en el motor. No se aceptan colecciones vacías ni datos de tutorial genérico. | | | | | |
| 2B.3 | **Si el equipo eligió MongoDB:** existe al menos una colección del proyecto con documentos reales cuya estructura está justificada. El equipo puede demostrar operaciones CRUD con filtros, operadores de consulta (`$eq`, `$gt`, `$in`, `$elemMatch` u otros relevantes al dominio), y puede explicar las decisiones de modelado: qué datos están embebidos en el documento y qué datos se referencian con `ObjectId`, y por qué en cada caso. | | | | | |
| 2B.4 | **Si el equipo eligió Redis:** existe al menos un caso de uso real del proyecto implementado con Redis: caché de consultas costosas, gestión de sesiones, contador en tiempo real, cola de tareas u otro. El equipo puede demostrar la operación en vivo: guardar, leer y verificar la expiración de una clave. Puede explicar por qué eligió ese tiempo de vida (`TTL`) y qué pasa con el sistema si Redis no está disponible. | | | | | |
| 2B.5 | La integración NoSQL con el backend está **codificada y versionada en el repositorio**: hay al menos un módulo, servicio o repositorio en el código que muestra la conexión, la lectura y la escritura en el motor NoSQL desde la aplicación. No es una conexión de prueba en un script suelto: está integrada al flujo real de al menos un caso de uso del sistema. | | | | | |
| 2B.6 | Existen **scripts o instrucciones documentadas** para inicializar el motor NoSQL del proyecto: cómo crear la base de datos o los índices iniciales, cómo cargar datos de semilla si aplica, y qué variables de entorno controlan la conexión. Otro desarrollador puede seguir esas instrucciones y reproducir el ambiente en su máquina. | | | | | |

### Bloque 2C — Integración del sistema en T5: coherencia arquitectónica

> Con tres backends, dos motores de BD y un frontend, el sistema del proyecto en T5 es el más complejo que el equipo ha manejado. Este bloque evalúa que esa complejidad está bajo control: los componentes se comunican correctamente, la autenticación es consistente, y no hay duplicación innecesaria de responsabilidades entre los servicios.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2C.1 | El equipo puede presentar un **diagrama de arquitectura actualizado** del sistema que muestre todos los componentes activos en T5: frontend (React/TS), backends (Spring Boot, FastAPI, Express), bases de datos (relacional + NoSQL) y las relaciones de comunicación entre ellos. El diagrama refleja el estado real del código, no el diseño original del T3 sin actualizar. | | | | | |
| 2C.2 | El jurado puede solicitar una **demo del flujo completo** de al menos un caso de uso que involucre datos tanto del motor relacional como del NoSQL: el frontend hace la petición, el backend correspondiente consulta o escribe en ambos motores, y el resultado se refleja en la interfaz sin errores. | | | | | |
| 2C.3 | No existe **duplicación de lógica de negocio** entre los tres backends sin justificación: si Spring Boot y Express tienen endpoints similares, el equipo puede explicar por qué ambos existen y cuál se usa en cada contexto. La duplicación accidental por falta de planificación es un indicador de deuda técnica que debe documentarse. | | | | | |

### Bloque 2D — Desarrollo Móvil con React Native *(bloque optativo — bonificación)*

> Este bloque solo se evalúa si el proyecto formativo incorpora un componente móvil. Si el equipo marcó "No" en el campo de la portada, todos los ítems de este bloque se marcan ➖ y no afectan la calificación. Si el equipo marcó "Sí", todos los ítems son obligatorios dentro del bloque y su resultado se suma como bonificación de hasta 5 % sobre D2.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2D.1 | La aplicación React Native **corre en un dispositivo o emulador** sin errores. El jurado puede solicitar que el equipo abra Expo Go en un dispositivo físico o lance el emulador y navegue por la app en el momento. | | | | | |
| 2D.2 | La app móvil tiene al menos **tres pantallas funcionales** que corresponden a casos de uso reales del sistema: no son pantallas de ejercicio genérico, sino vistas del mismo dominio del proyecto formativo con datos reales provenientes de la API. | | | | | |
| 2D.3 | La app **consume la API REST del sistema**: hay al menos dos pantallas que hacen peticiones HTTP reales al backend (no datos hardcodeados) y muestran los resultados al usuario. El manejo del estado de carga y los errores de red es visible en la interfaz. | | | | | |
| 2D.4 | La app implementa **navegación entre pantallas** con React Navigation u otra solución: las rutas protegidas (que requieren login) redirigen al usuario no autenticado a la pantalla de login, y el flujo de autenticación funciona de manera consistente con el resto del sistema. | | | | | |
| 2D.5 | El código de la app está **organizado en componentes reutilizables**: no hay pantallas monolíticas de 400 líneas sin estructura. Hay al menos una separación visible entre pantallas, componentes compartidos y lógica de llamadas a la API. | | | | | |

---

## DIMENSIÓN 3 — Documentación (15 %)

> En T5 la documentación tiene un reto específico: el sistema ya tiene múltiples componentes y la documentación debe reflejar esa arquitectura distribuida. Un README que solo describe cómo correr el frontend ya no es suficiente.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3.1 | El **README del repositorio** está actualizado para T5 y describe cómo levantar todos los componentes del sistema: frontend React, backend Spring Boot, backend FastAPI, backend Express, base de datos relacional y motor NoSQL. Incluye versiones de las herramientas requeridas, variables de entorno necesarias y el orden correcto de arranque de los servicios si hay dependencias entre ellos. | | | | | |
| 3.2 | La **justificación de la arquitectura de datos** está documentada: hay un documento o sección del README que explica qué tipo de datos vive en el motor relacional, qué tipo de datos vive en NoSQL y por qué esa separación tiene sentido para el dominio del proyecto. Esto es parte del cierre del RA de BD. | | | | | |
| 3.3 | Los **endpoints del servicio Express** están documentados: hay una colección de Postman exportada, un archivo Swagger/OpenAPI o un `API.md` en el repositorio con la descripción de cada ruta, el método HTTP, los parámetros esperados, los esquemas de entrada/salida y los posibles códigos de respuesta. | | | | | |
| 3.4 | Los **commits del trimestre** siguen el patrón convencional o descriptivo establecido por el equipo, y el historial de ramas muestra que las funcionalidades de Express, NoSQL y móvil (si aplica) se desarrollaron en ramas separadas e integradas por pull request. El log de actividad no muestra commits masivos en los días previos a la sustentación. | | | | | |
| 3.5 | Si el proyecto incorpora **componente móvil**, existe documentación mínima de cómo configurar y ejecutar el proyecto React Native: versión de Expo, cómo obtener el QR para Expo Go, y qué variables de entorno controlan la URL base de la API que consume la app. | | | | | |

---

## DIMENSIÓN 4 — Trabajo en Equipo (10 %)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 4.1 | El **historial de contribuciones** muestra actividad distribuida entre todos los integrantes durante las semanas del trimestre. El jurado puede revisar el gráfico de contribuidores del repositorio en el momento. No hay integrantes activos en un solo módulo aislado sin ninguna contribución al resto del sistema. | | | | | |
| 4.2 | El equipo puede describir cómo **distribuyó el trabajo** entre los tres frentes técnicos del trimestre: quién lideró cada módulo, cómo coordinaron para que Express se integrara con el resto del sistema sin romper lo que ya funcionaba, y si alguien tuvo que intervenir en el módulo de otro para resolver un bloqueo. | | | | | |
| 4.3 | Durante la sustentación, **todos los integrantes presentes demuestran comprensión** del sistema completo: si el jurado pregunta a un integrante que trabajó principalmente en NoSQL sobre la estructura del servicio Express, debe poder responder con coherencia básica. La especialización es válida; el desconocimiento total de otros módulos no. | | | | | |
| 4.4 | El equipo puede describir **al menos una decisión técnica colectiva** del trimestre relacionada con la arquitectura multi-backend o la integración NoSQL: qué debatieron, qué opciones consideraron y cómo llegaron a la decisión final. Las decisiones tomadas por una sola persona sin consultar al equipo son un indicador de disfunción que el jurado debe registrar. | | | | | |

---

## DIMENSIÓN 5 — Calidad y Mejores Prácticas (15 %)

> En un trimestre con tres tecnologías simultáneas la calidad es más difícil de mantener, y precisamente por eso vale más cuando se logra. El jurado debe verificar que el estándar de codificación del equipo sobrevivió la presión del trimestre y que la deuda técnica acumulada es reconocida y documentada, no ignorada.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 5.1 | El código del servicio Express cumple el **estándar de codificación del equipo**: los mismos criterios de nomenclatura, estructura de carpetas y convenciones que aplica el equipo en los demás módulos se reflejan también en el código de Express. No hay un módulo claramente más descuidado que los demás. | | | | | |
| 5.2 | El equipo tiene **linters configurados y sin errores críticos** en el código JavaScript de Express: ESLint con un ruleset definido, sin `var`, sin funciones sin nombre descriptivo, sin `console.log` de depuración en el código de producción. | | | | | |
| 5.3 | Los **índices del motor NoSQL** están justificados: si hay índices en MongoDB (sobre campos de búsqueda frecuente, campos de texto completo, índices compuestos), el equipo puede explicar por qué ese índice existe y qué consulta específica del sistema optimiza. No se busca optimización prematura; se busca que el equipo entienda el propósito de los índices que tiene. | | | | | |
| 5.4 | El equipo puede identificar y describir al menos **dos ítems de deuda técnica** del sistema acumulada en T5: código que funciona pero que saben que tiene problemas de mantenibilidad, endpoints que no tienen validación completa, módulos que no tienen pruebas. Estos ítems deben estar registrados en el backlog como historias técnicas, no ignorados. El jurado evalúa la honestidad del equipo con su propio código, no la perfección del código. | | | | | |
| 5.5 | El sistema completo en T5 no tiene **regresiones visibles** respecto a T4: las funcionalidades que funcionaban en la sustentación anterior siguen funcionando. Si hay algo que se rompió al integrar los módulos de T5, el equipo lo tiene documentado como defecto abierto con su plan de corrección. | | | | | |

---

## Resumen de evaluación

| Dimensión | Peso base | Bonif. móvil | Calificación del jurado | Notas |
|-----------|-----------|-------------|-------------------------|-------|
| D1 — Gestión del Proyecto | 10 % | — | | |
| D2 — Artefactos Técnicos | 50 % | hasta +5 % | | |
| D3 — Documentación | 15 % | — | | |
| D4 — Trabajo en Equipo | 10 % | — | | |
| D5 — Calidad y Mejores Prácticas | 15 % | — | | |

---

## Decisión del jurado

| Decisión | Seleccionar |
|----------|-------------|
| ☐ **Aprobado sin condiciones** | El equipo continúa al T6 con el proyecto vigente. |
| ☐ **Aprobado con condicionamientos** | Continúa pero debe resolver los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora** | El grupo tiene hasta [fecha] para subsanar los ítems críticos y presentar nuevamente. |

### Condicionamientos o ajustes requeridos

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
|-------------------------------|-----------------|--------------|
| | | |
| | | |

---

## Retroalimentación cualitativa del jurado

| Jurado | Fortaleza principal observada en T5 | Riesgo más importante a gestionar en T6 |
|--------|-------------------------------------|------------------------------------------|
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

*Instrumento de evaluación formativa — Programa ADSO 228118 · Oferta Abierta · Trimestre V*
*Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital*