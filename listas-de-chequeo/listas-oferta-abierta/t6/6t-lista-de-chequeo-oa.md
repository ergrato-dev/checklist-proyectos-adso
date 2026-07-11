# Lista de Chequeo — Trimestre VI

## Seguimiento de Proyecto Formativo · Oferta Abierta

### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Fase del proyecto formativo:** Construcción del Software — Proyecto VI (cierre de la fase de codificación)
>
> **Resultados de Aprendizaje activos este trimestre:**
>
> - Construcción del Software → RA 01: Planear actividades de construcción del software — **resultado parcial**
> - Construcción del Software → RA 04: Codificar el software de acuerdo con el diseño — **resultado FINAL** (módulo Flask como cuarto y último backend)
> - Construcción del Software → RA 05: Realizar pruebas al software para verificar su funcionalidad — **resultado completo**
>
> **Módulos técnicos activos:**
>
> - Asesoría de Desarrollo / Codificación Backend — cierre definitivo del RA de Codificación, obligatorio (6 h/sem)
> - Pruebas de Software — cierre del RA 05, obligatorio (6 h/sem)
> - Fundamentos de Tecnologías Emergentes (Python - IoT con Tinkercad/Arduino) — **deseable, no obligatorio** (12 h/sem cuando se activa)
>
> **Propósito del trimestre:** T6 cierra la fase de construcción del sistema. Tiene dos hitos pedagógicos simultáneos e igualmente importantes: el equipo demuestra que puede construir un servicio REST adicional (cuarto backend del programa, lo que consolida la competencia de codificación en múltiples tecnologías), y por primera vez en Oferta Abierta el equipo enfrenta el proceso formal de pruebas de software — plan de pruebas, casos de prueba, ejecución, registro de defectos y reporte. El módulo de IoT enriquece el proyecto si el equipo lo incorpora, pero el sistema es válido y completo sin él. La pregunta central de T6 es doble: **¿el sistema está completamente codificado con todos sus componentes integrados, y el equipo ha verificado su funcionamiento mediante un proceso de pruebas documentado y reproducible?**

---

## Datos de la sesión

| Campo                                  | Valor       |
| -------------------------------------- | ----------- |
| Número de Ficha                        |             |
| Nombre del grupo de proyecto           |             |
| Nombre del sistema / software          |             |
| Stack tecnológico completo del sistema |             |
| URL del repositorio                    |             |
| ¿El proyecto incorpora componente IoT? | Sí ☐ / No ☐ |
| Integrantes presentes                  |             |
| Integrantes ausentes                   |             |
| Fecha de sustentación                  |             |
| Jurado 1                               |             |
| Jurado 2                               |             |

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

| Dimensión                                          | Peso (sin IoT) | Peso (con IoT)        |
| ---------------------------------------------------- | -------------- | ---------------------- |
| D1 — Gestión del Proyecto                          | 10 %           | 10 %                  |
| D2 — Artefactos Técnicos: Flask + integración      | 35 %           | 30 %                  |
| D3 — Pruebas de Software                           | 25 %           | 22 %                  |
| D4 — Documentación                                 | 15 %           | 15 %                  |
| D5 — Calidad y Mejores Prácticas                   | 15 %           | 15 %                  |
| **Bloque optativo — IoT / Tecnologías Emergentes** | —              | **+8 % bonificación** |

> **Nota pedagógica sobre la ponderación:** Las Pruebas de Software suben a 25 % porque el RA 05 se cierra definitivamente en T6 para Oferta Abierta. Es el RA más subestimado por los equipos durante todo el programa: la mayoría llega a T6 habiendo "probado" el sistema de manera informal (abrir el navegador y ver si funciona) pero sin ningún artefacto de pruebas formal. Un resultado FINAL no admite pruebas informales como evidencia. El jurado debe ser riguroso en este punto: plan de pruebas escrito, casos de prueba documentados, ejecución registrada y reporte de defectos son obligatorios, no opcionales.
>
> La bonificación de IoT es mayor que la de Móvil en T5 (8 % vs 5 %) porque el módulo tiene más horas semanales (12 h/sem vs el esquema de T5) y porque la integración de hardware o simulación IoT al proyecto formativo representa un nivel de complejidad técnica significativamente mayor que el componente móvil.

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

> T6 es el penúltimo trimestre lectivo de Oferta Abierta. La gestión en este punto debe reflejar madurez completa y una visión clara del cierre: el equipo sabe exactamente qué queda por hacer, cuánto tiempo tiene y qué es alcanzable en T7. Un backlog sin revisar o un equipo que no puede responder "¿cuántas historias les quedan?" es una señal de alerta seria a estas alturas del programa.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                               | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 1.1 | 🎤 El equipo tiene una **visión de cierre documentada**: qué funcionalidades estarán completamente terminadas al final de T6, cuáles se llevan a T7 y si el alcance total sigue siendo realista para los dos trimestres restantes. Debe ser honesta, no optimista sin fundamento.          |     |     |     |     |                          |
| 1.2 | 👁 El tablero de seguimiento distingue claramente las **tareas de construcción** (Flask, integración) de las **tareas de pruebas** (diseño de casos, ejecución, registro de defectos).                                      |     |     |     |     |                          |
| 1.3 | 🎤 El equipo tiene al menos **dos sprints documentados** con objetivo, compromisos, resultado y retrospectiva. Al menos una retrospectiva incluye reflexión específica sobre el proceso de pruebas: qué tan útiles fueron los casos diseñados, qué defectos encontraron que no esperaban. |     |     |     |     |                          |

---

## DIMENSIÓN 2 — Artefactos Técnicos: Backend e integración del sistema (35 % / 30 % con IoT)

### Bloque 2A — Backend REST: cuarto servicio funcional (RA 04 — resultado FINAL)

> El equipo elige la tecnología backend que mejor se alinee con su arquitectura. Este es el cuarto backend del programa, lo que consolida la competencia de codificación en múltiples tecnologías. El jurado debe evaluar no solo si el código funciona, sino si las decisiones de diseño del equipo son coherentes y justificadas.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                                      | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2A.1 | 👁 El proyecto backend **arranca sin errores** y la estructura del proyecto separa claramente rutas/controladores, modelos, servicios y configuración por ambiente.                                                                                                                                                      |     |     |     |     |                          |
| 2A.2 | 🎤 El equipo justifica **por qué existe este servicio** en la arquitectura (respuesta inaceptable: "porque el módulo lo pedía") y puede **comparar la tecnología elegida** con los otros backends del sistema: ventajas, desventajas, cuándo elegiría cada uno, y qué tuvo que configurar manualmente que otros frameworks dan más automáticamente.                                                                      |     |     |     |     |                          |
| 2A.3 | 👁 La API implementa **validación de datos de entrada** en las rutas de creación y actualización; las peticiones inválidas reciben un 400 con detalle de los campos problemáticos, no un error genérico 500.                                                                                                               |     |     |     |     |                          |
| 2A.4 | 🎤 La API tiene **autenticación JWT funcional** integrada con el sistema: rutas protegidas verifican el token, compatible con el sistema de autenticación del proyecto. Demo en vivo.                                                                                                                                             |     |     |     |     |                          |
| 2A.5 | 👁 Existe un archivo de dependencias actualizado, `.env.example` con las variables requeridas, y el equipo puede demostrar que el proyecto **se instala y ejecuta desde cero** siguiendo el README.                                                                                                                                                                                   |     |     |     |     |                          |

### Bloque 2B — Coherencia e integración del sistema completo

> Con múltiples backends, un frontend, BD relacional y NoSQL, el sistema en T6 es el más complejo que el equipo ha gestionado. Este bloque evalúa que esa complejidad está bajo control arquitectónico: cada componente tiene una responsabilidad clara, los componentes se comunican correctamente y el sistema como un todo es demostrable en vivo.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                  | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2B.1 | 👁 El equipo tiene un **diagrama de arquitectura actualizado** con todos los componentes del sistema en T6, incluidos protocolos de comunicación, coherente con el código real.                                  |     |     |     |     |                          |
| 2B.2 | 🎤 **Demostración end-to-end** de al menos un caso de uso complejo que cruce múltiples capas del sistema, sin intervención manual del equipo para "arreglarlo" durante la demo.                                                                                                                      |     |     |     |     |                          |
| 2B.3 | 🎤 El equipo describe la **estrategia de autenticación centralizada**: cómo se emite el token, qué servicio lo valida, cómo los diferentes backends verifican identidad sin duplicar lógica. |     |     |     |     |                          |

### Bloque 2C — IoT / Tecnologías Emergentes _(bloque optativo — bonificación de hasta 8 %)_

> Este bloque solo se evalúa si el proyecto incorpora IoT o tecnologías emergentes. Si el equipo marcó "No" en la portada, todos los ítems se marcan ➖. Si marcó "Sí", todos son obligatorios dentro del bloque y su resultado determina la bonificación sobre D2.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                              | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 2C.1 | 🎤 El equipo demuestra **al menos un prototipo IoT funcional** (físico con Arduino, o simulado con Tinkercad) que genera datos con sentido en el contexto del proyecto.                    |     |     |     |     |                          |
| 2C.2 | 👁 Los datos del dispositivo IoT **llegan al sistema**: hay al menos un endpoint que recibe el dato, lo almacena en BD y lo hace disponible para el frontend.                        |     |     |     |     |                          |
| 2C.3 | 🎤 El equipo explica el **protocolo de comunicación** utilizado (HTTP, MQTT, WebSocket), frecuencia de envío y manejo de la desconexión, y existe **documentación del circuito/código del microcontrolador** que permite a otro aprendiz reproducir el prototipo. |     |     |     |     |                          |

---

## DIMENSIÓN 3 — Pruebas de Software (25 % / 22 % con IoT)

> Esta dimensión recibe el mayor peso individual del artefacto porque el RA 05 se cierra definitivamente en T6. No se evalúa si el sistema "funciona": eso lo evalúa D2. Se evalúa si el equipo tiene un **proceso de pruebas documentado, ejecutado y registrado**, que cualquier persona pueda reproducir y auditar.

### Bloque 3A — Planificación de pruebas

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                                                   | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 3A.1 | 👁 Existe un **plan de pruebas** que define alcance, tipos de prueba aplicados, herramientas seleccionadas para cada tipo, criterios de entrada y salida del proceso, y una **estrategia de niveles** coherente (unitarias en lógica crítica, integración en comunicación entre capas, sistema en flujos completos). |     |     |     |     |                          |
| 3A.2 | 👁 El **ambiente de prueba está configurado y separado** del ambiente de desarrollo: BD de prueba distinta con datos representativos que no contaminan la BD de desarrollo.                                                                                                                                                     |     |     |     |     |                          |

### Bloque 3B — Diseño y ejecución de casos de prueba

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                      | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 3B.1 | 👁 Existe una **matriz de casos de prueba** con al menos 20 casos que cubren mínimo cuatro módulos, incluyendo **casos positivos y negativos** en proporción razonable, cada uno con ID, tipo, precondiciones, datos, pasos, resultado esperado/obtenido y estado.                                                 |     |     |     |     |                          |
| 3B.2 | 🎤 El equipo tiene **pruebas unitarias automatizadas** ejecutables con un solo comando para al menos un módulo del backend (pytest, JUnit, etc.), con cobertura mínima del 50 % del módulo probado, y puede ejecutarlas en el momento.                                                                      |     |     |     |     |                          |
| 3B.3 | 👁 Hay una **colección de pruebas de API** en Postman (o equivalente) que cubre todos los endpoints del backend principal y al menos los principales de los demás servicios, con tests automatizados que verifican código de respuesta, estructura del JSON y al menos un campo. |     |     |     |     |                          |

### Bloque 3C — Reporte de pruebas y gestión de defectos

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                    | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 3C.1 | 👁 Existe un **reporte de ejecución de pruebas** con casos ejecutados/aprobados/fallidos, porcentaje de cobertura, y una tabla de defectos con severidad y estado.                                                                                                                                               |     |     |     |     |                          |
| 3C.2 | 👁 Los **defectos están registrados en el sistema de seguimiento del equipo** (GitHub Issues, Jira, Trello) con descripción, pasos para reproducir, severidad y responsable. No se acepta una lista en texto plano sin trazabilidad. |     |     |     |     |                          |
| 3C.3 | 🎤 El equipo demuestra al menos **dos defectos que encontró y corrigió**: muestra el caso de prueba que falló, explica el defecto, muestra el commit que lo corrigió, y confirma que el caso ahora pasa. Este ciclo detectar → corregir → verificar es el corazón del RA de pruebas.                                                                                                                                |     |     |     |     |                          |

---

## DIMENSIÓN 4 — Documentación (15 %)

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                 | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 4.1 | 👁 El **README** describe cómo levantar todos los componentes del sistema incluyendo Flask, con una sección sobre el ambiente de pruebas (configuración, ejecución, interpretación del reporte).                                                                                 |     |     |     |     |                          |
| 4.2 | 👁 La **documentación de la API** (colección Postman, OpenAPI o `API.md`) y el **plan de pruebas con matriz de casos** están versionados en el repositorio y accesibles desde el README, no solo en la máquina local de un integrante.                                                                                           |     |     |     |     |                          |
| 4.3 | 👁 El historial de commits del trimestre muestra **mensajes descriptivos** que distinguen los commits de construcción de Flask de los commits de corrección de defectos, idealmente referenciando el número del issue (`fix: ... closes #42`). |     |     |     |     |                          |
| 4.4 | 👁 Si el proyecto incorpora **componente IoT**, la documentación del circuito, el código del microcontrolador y el protocolo de comunicación están en el repositorio en una carpeta dedicada con su propio README.                                                                                             |     |     |     |     |                          |

---

## DIMENSIÓN 5 — Calidad y Mejores Prácticas (15 %)

> En el trimestre de cierre de la codificación la calidad no se evalúa como una aspiración sino como una evidencia verificable. El equipo lleva seis trimestres construyendo software; a estas alturas debe poder demostrar estándares de calidad consistentes y conscientes, no solo en el código más reciente sino en el sistema completo.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                                | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 5.1 | 👁 El código Flask sigue **PEP 8 y el estándar del equipo** con linter configurado (Flake8, Ruff o Pylint) sin errores críticos, y la **cobertura de pruebas automatizadas** del módulo más crítico supera el 50 %, demostrable con el reporte del framework.                                                                                                                   |     |     |     |     |                          |
| 5.2 | 👁 El sistema completo en T6 **no tiene regresiones visibles** respecto a T5: las funcionalidades que funcionaban en la sustentación anterior siguen funcionando, o están documentadas como defecto con estado y plan de corrección.                                                                                                                                    |     |     |     |     |                          |
| 5.3 | 🎤 El equipo presenta una **reflexión comparativa de los cuatro backends** del programa (Spring Boot, FastAPI, Express, Flask): fortalezas, debilidades, cuándo elegiría cada uno, y cuál dominó mejor y por qué. |     |     |     |     |                          |
| 5.4 | 🎤 La **deuda técnica del sistema está documentada y priorizada** en el backlog. El equipo explica cuál deuda se llevará a T7 y cuál quedará abierta con justificación.                                                                                                                                                                                                |     |     |     |     |                          |

---

## Resumen de evaluación

| Dimensión                        | Peso base | Bonif. IoT | Calificación del jurado | Notas |
| -------------------------------- | --------- | ---------- | ----------------------- | ----- |
| D1 — Gestión del Proyecto        | 10 %      | —          |                         |       |
| D2 — Artefactos Técnicos         | 35 %      | hasta +8 % |                         |       |
| D3 — Pruebas de Software         | 25 %      | —          |                         |       |
| D4 — Documentación               | 15 %      | —          |                         |       |
| D5 — Calidad y Mejores Prácticas | 15 %      | —          |                         |       |

---

## Decisión del jurado

| Decisión                             | Seleccionar                                                                                    |
| ------------------------------------ | ---------------------------------------------------------------------------------------------- |
| ☐ **Aprobado sin condiciones**       | El equipo continúa al T7 con el proyecto vigente.                                              |
| ☐ **Aprobado con condicionamientos** | Continúa pero debe resolver los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora**      | El grupo tiene hasta [fecha] para subsanar los ítems críticos y presentar nuevamente.          |

### Condicionamientos o ajustes requeridos

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
| ------------------------------ | ---------------- | ------------ |
|                                |                  |              |
|                                |                  |              |

---

## Retroalimentación cualitativa del jurado

| Jurado   | Fortaleza principal observada en T6 | Riesgo más importante a gestionar en T7 |
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

_Instrumento de evaluación formativa — Programa ADSO 228118 · Oferta Abierta · Trimestre VI_
_Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital_
