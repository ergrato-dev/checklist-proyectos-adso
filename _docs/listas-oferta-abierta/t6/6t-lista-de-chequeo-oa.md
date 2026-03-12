# Lista de Chequeo — Trimestre VI
## Seguimiento de Proyecto Formativo · Oferta Abierta
### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Fase del proyecto formativo:** Construcción del Software — Proyecto VI (cierre de la fase de codificación)
>
> **Resultados de Aprendizaje activos este trimestre:**
> - Construcción del Software → RA 01: Planear actividades de construcción del software — **resultado parcial**
> - Construcción del Software → RA 04: Codificar el software de acuerdo con el diseño — **resultado FINAL** (módulo Flask como cuarto y último backend)
> - Construcción del Software → RA 05: Realizar pruebas al software para verificar su funcionalidad — **resultado completo**
>
> **Módulos técnicos activos:**
> - Asesoría de Desarrollo / Codificación con Flask — cierre definitivo del RA de Codificación, obligatorio (6 h/sem)
> - Pruebas de Software — cierre del RA 05, obligatorio (6 h/sem)
> - Fundamentos de Tecnologías Emergentes (Python - IoT con Tinkercad/Arduino) — **deseable, no obligatorio** (12 h/sem cuando se activa)
>
> **Propósito del trimestre:** T6 cierra la fase de construcción del sistema. Tiene dos hitos pedagógicos simultáneos e igualmente importantes: el equipo demuestra que puede construir un servicio REST con Flask (cuarto backend del programa, lo que consolida la competencia de codificación en múltiples tecnologías), y por primera vez en Oferta Abierta el equipo enfrenta el proceso formal de pruebas de software — plan de pruebas, casos de prueba, ejecución, registro de defectos y reporte. El módulo de IoT enriquece el proyecto si el equipo lo incorpora, pero el sistema es válido y completo sin él. La pregunta central de T6 es doble: **¿el sistema está completamente codificado con todos sus componentes integrados, y el equipo ha verificado su funcionamiento mediante un proceso de pruebas documentado y reproducible?**

---

## Datos de la sesión

| Campo | Valor |
|-------|-------|
| Número de Ficha | |
| Nombre del grupo de proyecto | |
| Nombre del sistema / software | |
| Stack tecnológico completo del sistema | |
| URL del repositorio | |
| ¿El proyecto incorpora componente IoT? | Sí ☐ / No ☐ |
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

| Dimensión | Peso (sin IoT) | Peso (con IoT) |
|-----------|---------------|---------------|
| D1 — Gestión del Proyecto | 10 % | 10 % |
| D2 — Artefactos Técnicos: Flask + integración | 35 % | 30 % |
| D3 — Pruebas de Software | 25 % | 22 % |
| D4 — Documentación | 15 % | 15 % |
| D5 — Calidad y Mejores Prácticas | 15 % | 15 % |
| **Bloque optativo — IoT / Tecnologías Emergentes** | — | **+8 % bonificación** |

> **Nota pedagógica sobre la ponderación:** Las Pruebas de Software suben a 25 % porque el RA 05 se cierra definitivamente en T6 para Oferta Abierta. Es el RA más subestimado por los equipos durante todo el programa: la mayoría llega a T6 habiendo "probado" el sistema de manera informal (abrir el navegador y ver si funciona) pero sin ningún artefacto de pruebas formal. Un resultado FINAL no admite pruebas informales como evidencia. El jurado debe ser riguroso en este punto: plan de pruebas escrito, casos de prueba documentados, ejecución registrada y reporte de defectos son obligatorios, no opcionales.
>
> La bonificación de IoT es mayor que la de Móvil en T5 (8 % vs 5 %) porque el módulo tiene más horas semanales (12 h/sem vs el esquema de T5) y porque la integración de hardware o simulación IoT al proyecto formativo representa un nivel de complejidad técnica significativamente mayor que el componente móvil.

---

## DIMENSIÓN 1 — Gestión del Proyecto (10 %)

> T6 es el penúltimo trimestre lectivo de Oferta Abierta. La gestión en este punto debe reflejar madurez completa y una visión clara del cierre: el equipo sabe exactamente qué queda por hacer, cuánto tiempo tiene y qué es alcanzable en T7. Un backlog sin revisar o un equipo que no puede responder "¿cuántas historias les quedan?" es una señal de alerta seria a estas alturas del programa.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 1.1 | El equipo tiene una **visión de cierre documentada**: puede presentar qué funcionalidades estarán completamente terminadas al final de T6, cuáles se llevan a T7 y si el alcance total del proyecto sigue siendo realista para los dos trimestres restantes. Esta proyección debe ser honesta, no optimista sin fundamento. | | | | | |
| 1.2 | El tablero de seguimiento distingue claramente las **tareas de construcción** (Flask, integración) de las **tareas de pruebas** (diseño de casos, ejecución, registro de defectos), porque en T6 ambas ocurren en paralelo y los equipos que no las separan tienden a descuidar una de las dos. | | | | | |
| 1.3 | El equipo tiene al menos **dos sprints documentados** con objetivo, compromisos, resultado y retrospectiva. Al menos una retrospectiva de T6 incluye reflexión específica sobre el proceso de pruebas: qué tan útiles fueron los casos diseñados, qué defectos encontraron que no esperaban, cómo afectaron el plan de construcción. | | | | | |

---

## DIMENSIÓN 2 — Artefactos Técnicos: Flask e integración del sistema (35 % / 30 % con IoT)

### Bloque 2A — Backend REST con Python / Flask (RA 04 — resultado FINAL)

> Flask es el cuarto backend del programa. A diferencia de los anteriores (Spring Boot, FastAPI, Express), Flask no tiene opiniones fuertes sobre cómo estructurar el proyecto: es un microframework que requiere que el equipo tome todas las decisiones arquitectónicas. Eso lo hace pedagógicamente valioso como cierre de la competencia de codificación: demuestra que el aprendiz puede construir una API bien estructurada incluso cuando el framework no lo obliga. El jurado debe evaluar no solo si el código funciona, sino si las decisiones de diseño del equipo son coherentes y justificadas.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2A.1 | El proyecto Flask **arranca sin errores** y el jurado puede verificarlo en el momento. La estructura del proyecto está organizada de manera explícita por el equipo (blueprints por dominio, carpeta de modelos, servicios, y configuración separada por ambiente). | | | | | |
| 2A.2 | El equipo puede justificar **por qué existe este servicio Flask** en la arquitectura del sistema: qué responsabilidad específica tiene que no está cubierta por los backends anteriores (FastAPI, Spring Boot, Express). Las respuestas aceptables son arquitectónicamente coherentes; la respuesta "porque el módulo lo pedía" no es aceptable en el trimestre de cierre de la competencia. | | | | | |
| 2A.3 | El proyecto usa **Flask-RESTful, Flask-RESTX o Blueprints** para organizar los endpoints en módulos por dominio. Hay al menos dos blueprints activos con sus rutas, y el archivo de entrada (`app.py` o equivalente) solo configura la aplicación sin contener lógica de negocio. | | | | | |
| 2A.4 | La API Flask implementa **validación de datos de entrada** en las rutas de creación y actualización: se usa Marshmallow, Pydantic, WTForms o validación manual explícita. Las peticiones con datos inválidos reciben una respuesta de error descriptiva (código 400 con detalle de los campos problemáticos), no un error genérico 500. | | | | | |
| 2A.5 | La API tiene **autenticación JWT funcional** integrada con el sistema: las rutas protegidas verifican el token antes de ejecutar la lógica, y ese token es compatible con el sistema de autenticación del proyecto (no hay un segundo sistema de login desconectado del resto). | | | | | |
| 2A.6 | Existe un archivo `requirements.txt` actualizado, un `.env.example` con todas las variables de entorno requeridas, y el equipo puede demostrar que el proyecto **se instala y ejecuta desde cero** siguiendo las instrucciones del README. | | | | | |
| 2A.7 | El equipo puede describir las **diferencias prácticas entre Flask y FastAPI** que experimentó al trabajar con ambos: qué hace Flask que FastAPI no hace por defecto, cuándo elegiría cada uno en un proyecto real y qué tuvo que configurar manualmente en Flask que FastAPI le daba automáticamente. Esta reflexión demuestra que el aprendizaje fue consciente, no mecánico. | | | | | |

### Bloque 2B — Coherencia e integración del sistema completo

> Con cuatro backends, un frontend, BD relacional y NoSQL, el sistema en T6 es el más complejo que el equipo ha gestionado. Este bloque evalúa que esa complejidad está bajo control arquitectónico: cada componente tiene una responsabilidad clara, los componentes se comunican correctamente y el sistema como un todo es demostrable en vivo.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2B.1 | El equipo tiene un **diagrama de arquitectura actualizado** que muestra todos los componentes del sistema en T6: frontend, los cuatro backends, BD relacional, BD NoSQL y cualquier servicio externo. El diagrama incluye los protocolos de comunicación entre componentes y es coherente con el código real. | | | | | |
| 2B.2 | El jurado puede solicitar una **demostración end-to-end** de al menos un caso de uso complejo que cruce múltiples capas del sistema. El flujo debe funcionar sin intervención manual del equipo para "arreglarlo" durante la demo. | | | | | |
| 2B.3 | El equipo puede describir la **estrategia de autenticación centralizada** del sistema: cómo se emite el token, qué servicio lo valida, y cómo los diferentes backends verifican la identidad del usuario sin duplicar la lógica de autenticación. Si hay múltiples sistemas de login independientes, el equipo debe justificar por qué. | | | | | |

### Bloque 2C — IoT / Tecnologías Emergentes *(bloque optativo — bonificación de hasta 8 %)*

> Este bloque solo se evalúa si el proyecto incorpora IoT o tecnologías emergentes. Si el equipo marcó "No" en la portada, todos los ítems se marcan ➖. Si marcó "Sí", todos son obligatorios dentro del bloque y su resultado determina la bonificación sobre D2.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2C.1 | El equipo puede demostrar **al menos un prototipo IoT funcional** (físico con Arduino, o simulado con Tinkercad) que genera datos con sentido en el contexto del proyecto formativo: el sensor mide algo relevante para el dominio del sistema (temperatura, presencia, movimiento, nivel, u otro). | | | | | |
| 2C.2 | Los datos del dispositivo IoT **llegan al sistema**: hay al menos un endpoint en alguno de los backends del proyecto que recibe el dato del sensor, lo almacena en la base de datos (relacional o NoSQL según la naturaleza del dato) y lo hace disponible para el frontend. | | | | | |
| 2C.3 | El equipo puede explicar el **protocolo de comunicación utilizado** (HTTP, MQTT, WebSocket u otro), la frecuencia de envío de datos, y cómo el sistema maneja la desconexión del dispositivo sin colapsar. | | | | | |
| 2C.4 | Existe documentación del componente IoT en el repositorio: esquema de conexiones del circuito, código del microcontrolador comentado, y descripción del protocolo de comunicación. Otro aprendiz debe poder reproducir el prototipo siguiendo esa documentación. | | | | | |

---

## DIMENSIÓN 3 — Pruebas de Software (25 % / 22 % con IoT)

> Esta dimensión recibe el mayor peso individual del artefacto porque el RA 05 se cierra definitivamente en T6. No se evalúa si el sistema "funciona": eso lo evalúa D2. Se evalúa si el equipo tiene un **proceso de pruebas documentado, ejecutado y registrado**, que cualquier persona pueda reproducir y auditar. La diferencia es fundamental: un sistema que funciona sin pruebas documentadas es un sistema que nadie puede mantener ni mejorar de manera controlada.

### Bloque 3A — Planificación de pruebas

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3A.1 | Existe un **plan de pruebas** del proyecto que define como mínimo: alcance (qué módulos y funcionalidades se prueban), tipos de pruebas aplicadas (unitarias, integración, sistema, aceptación), herramientas seleccionadas para cada tipo, ambiente de prueba configurado, criterios de entrada al proceso (cuándo está el sistema listo para ser probado) y criterios de salida (cuándo se considera que las pruebas están completas). | | | | | |
| 3A.2 | El plan de pruebas tiene una **estrategia de niveles** coherente con el sistema: las pruebas unitarias cubren la lógica de negocio de los módulos más críticos, las pruebas de integración verifican la comunicación entre capas (frontend-backend, backend-BD), y las pruebas de sistema verifican los flujos completos de los casos de uso más importantes. | | | | | |
| 3A.3 | El **ambiente de prueba está configurado y separado** del ambiente de desarrollo: hay una base de datos de prueba distinta a la de desarrollo, con datos de prueba representativos que no son los mismos datos que el equipo usa al desarrollar. Los tests no pueden contaminar la BD de desarrollo. | | | | | |

### Bloque 3B — Diseño y ejecución de casos de prueba

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3B.1 | Existe una **matriz de casos de prueba** con al menos 20 casos documentados que cubren como mínimo cuatro módulos o funcionalidades diferentes del sistema. Cada caso tiene: identificador único, nombre descriptivo, tipo de prueba, precondiciones, datos de entrada, pasos de ejecución, resultado esperado, resultado obtenido y estado (pasa / falla). | | | | | |
| 3B.2 | La matriz incluye **casos positivos y negativos** en proporción razonable: no solo los flujos felices (datos válidos, usuario autenticado, servidor disponible) sino también los flujos de error (datos inválidos, campos requeridos vacíos, token expirado, recurso no encontrado). Los sistemas fallidos solo en condiciones perfectas no son robustos. | | | | | |
| 3B.3 | El equipo tiene **pruebas unitarias automatizadas** ejecutables con un solo comando para al menos un módulo de lógica de negocio del backend (pytest para Flask/FastAPI o JUnit para Spring Boot). Las pruebas corren en el momento y producen un reporte visible. La cobertura mínima del módulo probado es del 50 % de sus funciones. | | | | | |
| 3B.4 | Hay una **colección de pruebas de API** en Postman (o herramienta equivalente) exportada en el repositorio que cubre todos los endpoints de Flask y al menos los endpoints principales de los demás backends. La colección incluye tests automatizados de Postman (scripts en la pestaña "Tests") que verifican código de respuesta, estructura del JSON y al menos un campo del cuerpo de la respuesta. | | | | | |

### Bloque 3C — Reporte de pruebas y gestión de defectos

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3C.1 | Existe un **reporte de ejecución de pruebas** que consolida: número total de casos ejecutados, casos aprobados, casos fallidos, porcentaje de cobertura alcanzado, y una tabla de defectos encontrados con su severidad (crítica, mayor, menor) y estado (abierto, resuelto, postergado con justificación). | | | | | |
| 3C.2 | Los **defectos encontrados están registrados en el sistema de seguimiento del equipo** (GitHub Issues, Jira, Trello u otro) con al menos: descripción clara del problema, pasos para reproducirlo, comportamiento esperado vs. comportamiento obtenido, severidad asignada y responsable de la corrección. No se acepta una lista de defectos en un documento de texto plano sin sistema de trazabilidad. | | | | | |
| 3C.3 | El equipo puede demostrar al menos **dos defectos que encontró en las pruebas y que corrigió**: muestra el caso de prueba que falló, explica cuál era el defecto en el código, muestra el commit que lo corrigió, y confirma que el caso de prueba ahora pasa. Este ciclo detectar → corregir → verificar es el corazón del RA de pruebas. | | | | | |

---

## DIMENSIÓN 4 — Documentación (15 %)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 4.1 | El **README del repositorio** está actualizado para T6 y describe cómo levantar todos los componentes del sistema incluyendo Flask. Tiene una sección específica sobre el ambiente de pruebas: cómo configurarlo, cómo ejecutar las pruebas automatizadas y cómo interpretar el reporte de resultados. | | | | | |
| 4.2 | La **documentación de la API Flask** está disponible en el repositorio: colección Postman exportada, especificación OpenAPI generada por Flask-RESTX, o un archivo `API.md` con la descripción de cada endpoint, sus parámetros, esquemas de entrada/salida y códigos de respuesta posibles. | | | | | |
| 4.3 | El **plan de pruebas y la matriz de casos** están versionados en el repositorio (en formato Markdown, Excel o la herramienta del equipo) y son accesibles desde el README. No deben estar únicamente en la máquina local de un integrante ni en un correo de email. | | | | | |
| 4.4 | El historial de commits del trimestre muestra **mensajes descriptivos** que permiten distinguir los commits de construcción de Flask de los commits de corrección de defectos encontrados en pruebas. Idealmente los commits de corrección referencian el número del issue o defecto correspondiente (e.g., `fix: corrige validación de email en endpoint POST /usuarios closes #42`). | | | | | |
| 4.5 | Si el proyecto incorpora **componente IoT**, la documentación del circuito, el código del microcontrolador y el protocolo de comunicación están en el repositorio en una carpeta dedicada con su propio README que explica cómo montar el prototipo o ejecutar la simulación en Tinkercad. | | | | | |

---

## DIMENSIÓN 5 — Calidad y Mejores Prácticas (15 %)

> En el trimestre de cierre de la codificación la calidad no se evalúa como una aspiración sino como una evidencia verificable. El equipo lleva seis trimestres construyendo software; a estas alturas debe poder demostrar estándares de calidad consistentes y conscientes, no solo en el código más reciente sino en el sistema completo.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 5.1 | El código Flask sigue **PEP 8 y el estándar de codificación del equipo**: nombres descriptivos, funciones con responsabilidad única, sin bloques de código comentado masivamente, sin `print()` de depuración en el código de producción. El equipo tiene Flake8, Ruff o Pylint configurado y sin errores críticos. | | | | | |
| 5.2 | El sistema completo en T6 **no tiene regresiones visibles** respecto a T5: las funcionalidades que funcionaban en la sustentación anterior siguen funcionando. Si alguna se rompió durante la integración de Flask o las correcciones de defectos, el equipo lo tiene documentado como defecto con su estado y plan de corrección. | | | | | |
| 5.3 | La **cobertura de pruebas automatizadas** del módulo más crítico del sistema supera el 50 % de sus funciones, demostrable con el reporte del framework de pruebas. El equipo puede explicar qué funciones no están cubiertas y por qué (dificultad técnica real o baja prioridad justificada), no simplemente "no alcanzó el tiempo". | | | | | |
| 5.4 | El equipo puede presentar una **reflexión comparativa de los cuatro backends** del programa (Spring Boot, FastAPI, Express, Flask): fortalezas y debilidades de cada uno, cuándo elegiría cada uno en un proyecto real según el contexto (equipo, tipo de sistema, escala, ecosistema), y cuál dominó mejor el equipo y por qué. Esta reflexión demuestra aprendizaje acumulativo, no solo dominio del último módulo. | | | | | |
| 5.5 | La **deuda técnica del sistema está documentada y priorizada**: hay un registro en el backlog de los ítems técnicos pendientes de mejora, ordenados por impacto. El equipo puede explicar cuál deuda se llevará a T7 para resolver antes de la implantación y cuál quedará abierta con justificación. | | | | | |

---

## Resumen de evaluación

| Dimensión | Peso base | Bonif. IoT | Calificación del jurado | Notas |
|-----------|-----------|-----------|-------------------------|-------|
| D1 — Gestión del Proyecto | 10 % | — | | |
| D2 — Artefactos Técnicos | 35 % | hasta +8 % | | |
| D3 — Pruebas de Software | 25 % | — | | |
| D4 — Documentación | 15 % | — | | |
| D5 — Calidad y Mejores Prácticas | 15 % | — | | |

---

## Decisión del jurado

| Decisión | Seleccionar |
|----------|-------------|
| ☐ **Aprobado sin condiciones** | El equipo continúa al T7 con el proyecto vigente. |
| ☐ **Aprobado con condicionamientos** | Continúa pero debe resolver los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora** | El grupo tiene hasta [fecha] para subsanar los ítems críticos y presentar nuevamente. |

### Condicionamientos o ajustes requeridos

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
|-------------------------------|-----------------|--------------|
| | | |
| | | |

---

## Retroalimentación cualitativa del jurado

| Jurado | Fortaleza principal observada en T6 | Riesgo más importante a gestionar en T7 |
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

*Instrumento de evaluación formativa — Programa ADSO 228118 · Oferta Abierta · Trimestre VI*
*Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital*