# Lista de Chequeo — Trimestre V

## Seguimiento de Proyecto Formativo · Oferta Abierta

### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Fase del proyecto formativo:** Construcción del Software — Proyecto V
>
> **Resultados de Aprendizaje activos este trimestre:**
>
> - Construcción del Software → RA 04: Codificar el software de acuerdo con el diseño — **resultado parcial** (módulos: REST Express + Desarrollo Móvil optativo)
> - Construcción del Software → RA 02: Construir la base de datos para el software a partir del modelo de datos — **resultado FINAL** (NoSQL: MongoDB y/o Redis)
>
> **Módulos técnicos activos:**
>
> - REST Backend (Express, FastAPI o Spring Boot) — tercer backend del programa, obligatorio (6 h/sem)
> - Gestión de Bases de Datos No Relacionales con MongoDB y/o Redis — cierre definitivo del RA de BD, obligatorio (6 h/sem)
> - Fundamentos de Desarrollo Móvil con React Native — **módulo deseable, no obligatorio** (12 h/sem cuando se activa)
>
> **Propósito del trimestre:** T5 consolida la construcción del sistema con un tercer backend REST que complementa los backends anteriores, y cierra definitivamente el RA de bases de datos con la integración de un motor NoSQL al proyecto. El componente móvil es un enriquecimiento del proyecto formativo: si el equipo lo incorpora, amplía el alcance del sistema y demuestra dominio de React Native; si no lo incorpora, el proyecto sigue siendo válido y completo. La pregunta central del trimestre es: **¿el sistema ahora tiene todos sus componentes de datos integrados — relacional y no relacional — y un nuevo servicio backend funcionando de manera coherente con lo construido en trimestres anteriores?**

---

## Datos de la sesión

| Campo                                    | Valor       |
| ----------------------------------------- | ----------- |
| Número de Ficha                          |             |
| Nombre del grupo de proyecto             |             |
| Nombre del sistema / software            |             |
| Stack tecnológico activo en T5           |             |
| URL del repositorio                      |             |
| ¿El proyecto incorpora componente móvil? | Sí ☐ / No ☐ |
| Integrantes presentes                    |             |
| Integrantes ausentes                     |             |
| Fecha de sustentación                    |             |
| Jurado 1                                 |             |
| Jurado 2                                 |             |

---

## Escala de valoración

| Símbolo | Nivel             | Descripción                                                  |
| ------- | ----------------- | ------------------------------------------------------------ |
| ✅      | **Excelente**     | Cumple completamente con evidencia demostrable en el momento |
| 🟡      | **Satisfactorio** | Cumple parcialmente; evidencia incompleta pero válida        |
| 🔴      | **Insuficiente**  | No cumple o la evidencia es muy débil / ausente              |
| ➖      | **No aplica**     | El ítem no corresponde al tipo o contexto de este proyecto   |

**Tiers de verificación** (ver [6.tiempos-de-sesion.md](../../../6.tiempos-de-sesion.md)): 🎤 verificación viva (demo/explicación oral, 1-1.5 min) · 👁 inspección rápida (vistazo binario, 20-30 seg).

---

## Ponderación por dimensión

| Dimensión                              | Peso (sin móvil) | Peso (con móvil)      |
| ---------------------------------------- | ---------------- | ---------------------- |
| D1 — Gestión del Proyecto              | 10 %             | 10 %                  |
| D2 — Artefactos Técnicos               | 50 %             | 45 %                  |
| D3 — Documentación                     | 15 %             | 15 %                  |
| D4 — Trabajo en Equipo                 | 10 %             | 10 %                  |
| D5 — Calidad y Mejores Prácticas       | 15 %             | 15 %                  |
| **Bloque optativo — Desarrollo Móvil** | —                | **+5 % bonificación** |

> **Nota pedagógica:** Cuando el proyecto incorpora el componente móvil, el Bloque 2D se evalúa como bonificación sobre el total de D2, lo que puede llevar esa dimensión hasta 50 % efectivo. Esto reconoce el esfuerzo adicional sin penalizar a los equipos que no lo incorporan. El jurado debe marcar claramente al inicio de la sesión si el Bloque 2D aplica o no, según la declaración del equipo.

---

## Distribución del tiempo de sesión (20 min)

| Bloque | Minutos |
| --- | --- |
| Contexto y datos de sesión | 1 |
| 🎤 Demo en vivo + preguntas (12 ítems 🎤, bloque serial) | 15 |
| 👁 Inspección rápida — en paralelo durante el bloque 🎤 (Jurado 2), no resta minutos | — |
| Retroalimentación, decisión y firmas | 4 |
| **Total** | **20** |

---

## DIMENSIÓN 1 — Gestión del Proyecto (10 %)

> En T5 el equipo trabaja en dos o tres frentes técnicos simultáneos. La gestión se evalúa principalmente en su capacidad de planear trabajo paralelo sin que un frente bloquee a otro, y de mantener la coherencia del proyecto como sistema integrado a pesar de la dispersión tecnológica del trimestre.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                               | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 1.1 | 👁 El **tablero de seguimiento** distingue visiblemente las tareas de Express, NoSQL y (si aplica) móvil. El estado de cada frente es verificable de manera independiente.                                                                |     |     |     |     |                          |
| 1.2 | 👁 El equipo tiene al menos **dos sprints documentados** del trimestre con sus objetivos, compromisos y resultados. Si algún sprint no cumplió su objetivo, la razón está documentada.                                                                             |     |     |     |     |                          |
| 1.3 | 🎤 El equipo puede describir cómo **coordinó la integración entre los módulos** (qué datos maneja Express versus el backend anterior, qué colecciones MongoDB complementan el esquema relacional) y presentar el **backlog total del proyecto** actualizado, con ajustes de alcance documentados si los hubo. |     |     |     |     |                          |

---

## DIMENSIÓN 2 — Artefactos Técnicos (50 % / 45 % con móvil)

### Bloque 2A — REST con JavaScript / Express: tercer backend del sistema (RA 04 parcial)

> Express es el tercer backend del programa, después de Spring Boot (T3) y FastAPI (T4). El equipo ya tiene experiencia construyendo APIs REST: lo que se evalúa en T5 no es si saben hacer un CRUD básico, sino si saben articular un tercer servicio al sistema existente con una responsabilidad clara y diferenciada. Un servicio Express que duplica exactamente lo que ya hace FastAPI no aporta valor arquitectónico al sistema.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                                   | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 2A.1 | 👁 El servidor **arranca sin errores**, con módulos de rutas/controladores organizados por dominio, y el archivo de entrada solo contiene configuración del servidor.                                                                                                                                           |     |     |     |     |                          |
| 2A.2 | 🎤 El equipo puede justificar **por qué existe este servicio** en la arquitectura del sistema y qué responsabilidad tiene que no está cubierta por los backends anteriores. La respuesta inaceptable es "porque el módulo lo pedía". |     |     |     |     |                          |
| 2A.3 | 👁 El servicio implementa al menos **un recurso REST completo** específico del proyecto con verbos HTTP correctos, códigos de respuesta semánticos y respuestas JSON consistentes con el resto de la API.                                                                                                                                                                                      |     |     |     |     |                          |
| 2A.4 | 🎤 El servicio tiene **middleware o JWT funcionando** (mismo token que emite el backend principal) y **manejo de errores centralizado** con respuestas JSON consistentes en lugar de stack traces expuestos. Demo en vivo.                                                                                                                                               |     |     |     |     |                          |
| 2A.5 | 👁 El proyecto tiene dependencias actualizadas, script de inicio documentado y `.env.example`; el equipo puede demostrar que el servicio **arranca desde cero** siguiendo la documentación.                                                                                                                                     |     |     |     |     |                          |

### Bloque 2B — Bases de Datos No Relacionales: MongoDB y/o Redis (RA 02 — resultado FINAL)

> Este es el RA que se cierra definitivamente en T5. A diferencia de los RA parciales, un resultado FINAL no admite "estamos avanzando" ni "lo terminamos en T6". El jurado debe evaluar este bloque con la misma rigurosidad con que evaluaría un entregable de cierre: el equipo domina el motor NoSQL elegido, lo tiene integrado al sistema real del proyecto, y puede demostrar su funcionamiento en el momento.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                                                                          | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2B.1 | 👁 El equipo tiene una **justificación técnica documentada** de por qué el proyecto usa NoSQL: qué tipo de datos se almacenan, por qué encaja mejor en un modelo de documentos o clave-valor que en el relacional, y qué ventaja concreta aporta. Específica del proyecto, no una definición genérica de NoSQL. |     |     |     |     |                          |
| 2B.2 | 🎤 La instancia del motor NoSQL elegido está **corriendo y conectada al sistema**: el equipo abre MongoDB Compass, RedisInsight u otra herramienta y muestra los datos reales del proyecto. No se aceptan colecciones vacías ni datos de tutorial.                                                                                                                                |     |     |     |     |                          |
| 2B.3 | 🎤 **Si el equipo eligió MongoDB:** demuestra operaciones CRUD con filtros y operadores de consulta relevantes al dominio, y explica las decisiones de modelado (qué datos están embebidos y cuáles referenciados con `ObjectId`, y por qué en cada caso).                 |     |     |     |     |                          |
| 2B.4 | 🎤 **Si el equipo eligió Redis:** demuestra un caso de uso real (caché, sesiones, contador, cola de tareas) en vivo — guardar, leer y verificar expiración de una clave — y explica por qué eligió ese `TTL` y qué pasa si Redis no está disponible.                 |     |     |     |     |                          |
| 2B.5 | 👁 La integración NoSQL con el backend está **codificada y versionada en el repositorio** (integrada al flujo real de al menos un caso de uso), y existen **scripts o instrucciones** documentadas para inicializar el motor (colecciones/índices, datos de semilla, variables de entorno).                                                                                                                                                                                       |     |     |     |     |                          |

### Bloque 2C — Integración del sistema en T5: coherencia arquitectónica

> Con tres backends, dos motores de BD y un frontend, el sistema en T5 es el más complejo que el equipo ha manejado. Este bloque evalúa que esa complejidad está bajo control: los componentes se comunican correctamente, la autenticación es consistente, y no hay duplicación innecesaria de responsabilidades entre los servicios.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                          | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2C.1 | 👁 El equipo presenta un **diagrama de arquitectura actualizado** con todos los componentes activos en T5 (frontend, backends, BD relacional + NoSQL) y las relaciones de comunicación entre ellos, coherente con el código real. |     |     |     |     |                          |
| 2C.2 | 🎤 Demo del **flujo completo** de al menos un caso de uso que cruce datos del motor relacional y del NoSQL: el frontend hace la petición, el backend consulta o escribe en ambos motores, el resultado se refleja sin errores.                                                                         |     |     |     |     |                          |
| 2C.3 | 👁 No existe **duplicación de lógica de negocio** entre los backends sin justificación: si dos backends tienen endpoints similares, el equipo explica por qué ambos existen y cuál se usa en cada contexto.                                                                                      |     |     |     |     |                          |

### Bloque 2D — Desarrollo Móvil con React Native _(bloque optativo — bonificación)_

> Este bloque solo se evalúa si el proyecto formativo incorpora un componente móvil. Si el equipo marcó "No" en el campo de la portada, todos los ítems de este bloque se marcan ➖ y no afectan la calificación. Si el equipo marcó "Sí", todos los ítems son obligatorios dentro del bloque y su resultado se suma como bonificación de hasta 5 % sobre D2.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                             | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2D.1 | 🎤 La aplicación React Native **corre en un dispositivo o emulador** sin errores. El equipo abre Expo Go o el emulador y navega por la app en el momento.                                                               |     |     |     |     |                          |
| 2D.2 | 👁 La app móvil tiene al menos **tres pantallas funcionales** de casos de uso reales del sistema, con datos reales provenientes de la API (no genéricos).                               |     |     |     |     |                          |
| 2D.3 | 👁 La app **consume la API REST del sistema**: al menos dos pantallas hacen peticiones HTTP reales (no datos hardcodeados) y el manejo del estado de carga y errores de red es visible.                     |     |     |     |     |                          |
| 2D.4 | 👁 La app implementa **navegación entre pantallas** (rutas protegidas redirigen a login) y está **organizada en componentes reutilizables**, sin pantallas monolíticas de 400 líneas sin estructura. |     |     |     |     |                          |

---

## DIMENSIÓN 3 — Documentación (15 %)

> En T5 la documentación tiene un reto específico: el sistema ya tiene múltiples componentes y la documentación debe reflejar esa arquitectura distribuida. Un README que solo describe cómo correr el frontend ya no es suficiente.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 3.1 | 👁 El **README** describe cómo levantar todos los componentes del sistema (frontend, backends, BD relacional y NoSQL), con versiones de herramientas, variables de entorno y orden de arranque, y documenta la **justificación de la arquitectura de datos** (qué vive en el motor relacional, qué vive en NoSQL y por qué). |     |     |     |     |                          |
| 3.2 | 👁 Los **endpoints del servicio Express** están documentados: colección de Postman, Swagger/OpenAPI o `API.md` con descripción de rutas, parámetros, esquemas y códigos de respuesta.                                                                                          |     |     |     |     |                          |
| 3.3 | 👁 Los **commits del trimestre** siguen un patrón convencional o descriptivo, y el historial de ramas muestra que Express, NoSQL y móvil (si aplica) se desarrollaron en ramas separadas integradas por pull request.                                                                                           |     |     |     |     |                          |
| 3.4 | 👁 Si el proyecto incorpora **componente móvil**, existe documentación mínima de cómo configurar y ejecutar el proyecto React Native (versión de Expo, QR, variables de entorno de la URL base).                                                                                                                                   |     |     |     |     |                          |

---

## DIMENSIÓN 4 — Trabajo en Equipo (10 %)

> Se observa en simultáneo con las demos de D2, sin tiempo adicional en la sesión.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                    | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 4.1 | 👁 El **historial de contribuciones** muestra actividad distribuida entre todos los integrantes durante las semanas del trimestre. No hay integrantes activos en un solo módulo aislado sin ninguna contribución al resto del sistema.                                                   |     |     |     |     |                          |
| 4.2 | 🎤 El equipo puede describir cómo **distribuyó el trabajo** entre los tres frentes técnicos: quién lideró cada módulo, cómo coordinaron para que Express se integrara sin romper lo que ya funcionaba.                                                |     |     |     |     |                          |
| 4.3 | 🎤 Durante la sustentación, **todos los integrantes presentes demuestran comprensión** del sistema completo: si el jurado pregunta a un integrante que trabajó principalmente en NoSQL sobre el servicio Express, debe poder responder con coherencia básica.                     |     |     |     |     |                          |
| 4.4 | 🎤 El equipo puede describir **al menos una decisión técnica colectiva** del trimestre relacionada con la arquitectura multi-backend o la integración NoSQL: qué debatieron, qué opciones consideraron y cómo llegaron a la decisión final. |     |     |     |     |                          |

---

## DIMENSIÓN 5 — Calidad y Mejores Prácticas (15 %)

> En un trimestre con tres tecnologías simultáneas la calidad es más difícil de mantener, y precisamente por eso vale más cuando se logra. El jurado debe verificar que el estándar de codificación del equipo sobrevivió la presión del trimestre y que la deuda técnica acumulada es reconocida y documentada, no ignorada.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                                                                   | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 5.1 | 👁 El código del servicio Express cumple el **estándar de codificación del equipo** y tiene **linters configurados sin errores críticos** (ESLint, sin `var`, sin `console.log` de depuración en producción).                                                                                                                                        |     |     |     |     |                          |
| 5.2 | 👁 Los **índices del motor NoSQL** están justificados (documentados con el propósito de cada uno): si hay índices en MongoDB, el equipo explica por qué existen y qué consulta específica optimizan. No se busca optimización prematura; se busca que el equipo entienda el propósito de los índices que tiene.                                                                          |     |     |     |     |                          |
| 5.3 | 🎤 El equipo identifica y describe al menos **dos ítems de deuda técnica** del sistema acumulada en T5, registrados en el backlog como historias técnicas, no ignorados. El jurado evalúa la honestidad del equipo con su propio código, no la perfección del código. |     |     |     |     |                          |
| 5.4 | 👁 El sistema completo en T5 no tiene **regresiones visibles** respecto a T4: las funcionalidades que funcionaban en la sustentación anterior siguen funcionando, o están documentadas como defecto abierto con plan de corrección.                                                                                                                                                   |     |     |     |     |                          |

---

## Resumen de evaluación

| Dimensión                        | Peso base | Bonif. móvil | Calificación del jurado | Notas |
| -------------------------------- | --------- | ------------ | ----------------------- | ----- |
| D1 — Gestión del Proyecto        | 10 %      | —            |                         |       |
| D2 — Artefactos Técnicos         | 50 %      | hasta +5 %   |                         |       |
| D3 — Documentación               | 15 %      | —            |                         |       |
| D4 — Trabajo en Equipo           | 10 %      | —            |                         |       |
| D5 — Calidad y Mejores Prácticas | 15 %      | —            |                         |       |

---

## Decisión del jurado

| Decisión                             | Seleccionar                                                                                    |
| ------------------------------------ | ---------------------------------------------------------------------------------------------- |
| ☐ **Aprobado sin condiciones**       | El equipo continúa al T6 con el proyecto vigente.                                              |
| ☐ **Aprobado con condicionamientos** | Continúa pero debe resolver los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora**      | El grupo tiene hasta [fecha] para subsanar los ítems críticos y presentar nuevamente.          |

### Condicionamientos o ajustes requeridos

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
| ------------------------------ | ---------------- | ------------ |
|                                |                  |              |
|                                |                  |              |

---

## Retroalimentación cualitativa del jurado

| Jurado   | Fortaleza principal observada en T5 | Riesgo más importante a gestionar en T6 |
| -------- | ----------------------------------- | --------------------------------------- |
| Jurado 1 |                                     |                                         |
| Jurado 2 |                                     |                                         |

---

## Firmas

| Rol                                                    | Nombre completo | Firma |
| ------------------------------------------------------ | --------------- | ----- |
| Jurado 1                                               |                 |       |
| Jurado 2                                               |                 |       |
| Vocero del grupo (constancia de recibido del feedback) |                 |       |

---

_Instrumento de evaluación formativa — Programa ADSO 228118 · Oferta Abierta · Trimestre V_
_Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital_
