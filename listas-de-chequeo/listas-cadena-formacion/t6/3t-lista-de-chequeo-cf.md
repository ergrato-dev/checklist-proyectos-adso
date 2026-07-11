# Lista de Chequeo — Trimestre III

## Seguimiento de Proyecto Formativo · Cadena de Formación

### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Modalidad:** Cadena de Formación (aprendices graduados como Técnicos en Desarrollo de Software)  
> **Equivalencia en el semáforo interno:** Trimestre V–VI del plan de formación  
> **Fase del proyecto formativo:** Construcción del Software — Proyecto III / IV  
> **Resultados de Aprendizaje activos:**
>
> - RA 01: Planear actividades de construcción del software de acuerdo con el diseño establecido — **resultado parcial**
> - RA 02: Construir la base de datos para el software a partir del modelo de datos — **resultado FINAL**
> - RA 03: Crear componentes front-end del software de acuerdo con el diseño
> - RA 04: Codificar el software de acuerdo con el diseño establecido — **resultado parcial**
> - RA 05: Realizar pruebas al software para verificar su funcionalidad
>
> **Módulos técnicos activos:** Asesoría de Desarrollo / Django (backend) · Gestión de BD No Relacionales (MongoDB/Redis) · Front End 1 SPA con React/TypeScript · REST con JavaScript / Express · Pruebas de Software
>
> **Propósito del trimestre:** Este es el trimestre de construcción intensiva. Los aprendices, que ya completaron análisis, diseño y propuesta técnica en T1 y T2, deben mostrar ahora un **sistema funcionando**: frontend SPA conectado a uno o más backends REST, base de datos relacional y no relacional integradas, y al menos un ciclo completo de pruebas documentado. El jurado evalúa software que se puede ejecutar y probar, no solo diagramas. La pregunta central de este trimestre es: **¿el equipo está construyendo lo que diseñó?**

---

## Datos de la sesión

| Campo                         | Valor |
| ----------------------------- | ----- |
| Número de Ficha               |       |
| Nombre del grupo de proyecto  |       |
| Nombre del sistema / software |       |
| Stack tecnológico activo      |       |
| URL del repositorio           |       |
| Integrantes presentes         |       |
| Integrantes ausentes          |       |
| Fecha de sustentación         |       |
| Jurado 1                      |       |
| Jurado 2                      |       |

---

## Escala de valoración

| Símbolo | Nivel             | Descripción                                                  |
| ------- | ----------------- | ------------------------------------------------------------ |
| ✅      | **Excelente**     | Cumple completamente con evidencia demostrable en el momento |
| 🟡      | **Satisfactorio** | Cumple parcialmente o hay evidencia incompleta pero válida   |
| 🔴      | **Insuficiente**  | No cumple, evidencia muy débil o ausente                     |
| ➖      | **No aplica**     | El ítem no corresponde al tipo o contexto de este proyecto   |

**Tiers de verificación** (ver [6.tiempos-de-sesion.md](../../../6.tiempos-de-sesion.md)): 🎤 verificación viva (demo/explicación oral, 1-1.5 min) · 👁 inspección rápida (vistazo binario, 20-30 seg).

---

## Ponderación por dimensión

| Dimensión                                 | Peso |
| ----------------------------------------- | ---- |
| D1 — Gestión del Proyecto                 | 15 % |
| D2 — Artefactos Técnicos                  | 45 % |
| D3 — Documentación                        | 15 % |
| D4 — Trabajo en Equipo                    | 10 % |
| D5 — Calidad, Pruebas y Mejores Prácticas | 15 % |

> **Nota sobre la ponderación:** En T3 de Cadena la Dimensión 5 sube a 15 % porque el RA de pruebas es un resultado de aprendizaje completo (no parcial) que se cierra en este trimestre. Las pruebas no son un adorno: son parte integral de la construcción del software. La documentación baja a 15 % porque en esta fase los artefactos documentales ya están consolidados de T1 y T2; lo que se evalúa es que el código está documentado de manera técnica y que el repositorio refleja un flujo de trabajo profesional.

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

## DIMENSIÓN 1 — Gestión del Proyecto (15 %)

> En la fase de construcción la gestión ágil se vuelve operativa, no solo declarativa. El equipo debe poder mostrar que Scrum (o la metodología elegida) les está sirviendo para entregar software funcionando de manera incremental, no solo para organizar tareas en tarjetas de colores.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                 | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 1.1 | 👁 El **product backlog** está actualizado, priorizado y refleja el estado real del proyecto: historias completadas cerradas, en progreso demostrables en la sesión, y pendientes estimadas.                                                    |     |     |     |     |                          |
| 1.2 | 🎤 El equipo puede mostrar **al menos dos sprints completados** este trimestre con sus sprint reviews documentados (qué se comprometió, qué se entregó, qué no se alcanzó y por qué). La demo de cada sprint review debería ser código funcionando, no diapositivas.                                                                       |     |     |     |     |                          |
| 1.3 | 👁 Existe evidencia de **comunicación diaria del equipo** (daily standup, canal de Slack/Discord con mensajes de estado) y el **ritmo de commits** es consistente durante las semanas del trimestre, no concentrado en los días previos a la sustentación. |     |     |     |     |                          |
| 1.4 | 👁 El equipo realizó al menos una **retrospectiva formal** del período (documentada): qué mejoró respecto a T2 en proceso, qué práctica nueva adoptaron y si hubo ajustes al backlog como resultado.                                                                                 |     |     |     |     |                          |

---

## DIMENSIÓN 2 — Artefactos Técnicos (45 %)

> Este es el núcleo de la evaluación en T3. Se divide en cinco bloques correspondientes a los módulos técnicos activos. El jurado debe verificar cada bloque mediante demostración en vivo cuando sea posible: ver código corriendo es mucho más fiable que ver diapositivas con capturas de pantalla.

### Bloque 2A — Backend con Django: planificación y construcción (RA 01 y RA 04 parciales)

| #    | Criterio de evaluación                                                                                                                                                                                                                                                         | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2A.1 | 🎤 El proyecto Django arranca **sin errores** en el entorno local. Demostración en vivo: `python manage.py runserver` y verificación de que el servidor levanta correctamente.                                                                         |     |     |     |     |                          |
| 2A.2 | 👁 El proyecto tiene una **estructura de carpetas organizada** acorde con Django (apps separadas por dominio, carpeta de configuración `settings/`, templates o API views según el enfoque).                                                              |     |     |     |     |                          |
| 2A.3 | 👁 El equipo implementa al menos **dos apps Django** con sus modelos, vistas (o ViewSets si usan DRF) y rutas (`urls.py`) correctamente configuradas.                                                                                              |     |     |     |     |                          |
| 2A.4 | 👁 El backend expone una **API REST funcional** con al menos un CRUD completo para el recurso principal, demostrable con Postman o el Swagger/Redoc generado por DRF.                                                            |     |     |     |     |                          |
| 2A.5 | 👁 El proyecto usa **variables de entorno** para configuración sensible y tiene un archivo de dependencias (`requirements.txt`/`pyproject.toml`) actualizado; otro desarrollador puede instalarlas y levantar el proyecto. |     |     |     |     |                          |

### Bloque 2B — Base de datos NoSQL: MongoDB y/o Redis (RA 02 — resultado FINAL)

> Este es el único RA que se cierra como **resultado FINAL** en este trimestre. Por esa razón los criterios son más exigentes: no se acepta un resultado parcial ni "en progreso". El equipo debe demostrar dominio completo de al menos un motor NoSQL integrado al sistema.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                   | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 2B.1 | 🎤 El equipo demuestra una **instancia del motor NoSQL funcionando** (MongoDB, Redis u otro) con datos reales del proyecto (no de tutorial genérico), y la **integración con el backend está documentada** en el repositorio (módulo/servicio de conexión, lectura y escritura).                                                                                                                                    |     |     |     |     |                          |
| 2B.2 | 🎤 Existe una **justificación técnica documentada** de por qué el proyecto usa NoSQL: qué tipo de datos se almacenan, por qué no encajan bien en el modelo relacional, y qué ventaja concreta aporta la solución elegida.                                              |     |     |     |     |                          |
| 2B.3 | 🎤 **Si el equipo eligió un motor de documentos (MongoDB u otro):** demuestra inserción, consulta con filtros y operadores, actualización y eliminación sobre documentos del proyecto. El esquema (embebidos vs. referencias) está justificado.                         |     |     |     |     |                          |
| 2B.4 | 🎤 **Si el equipo eligió un motor clave-valor (Redis u otro):** demuestra al menos un caso de uso real (caché, sesiones, cola de tareas, tiempo real) y explica la política de expiración (TTL) y por qué eligió ese tiempo de vida. |     |     |     |     |                          |

### Bloque 2C — Frontend SPA con React/TypeScript (RA 03)

| #    | Criterio de evaluación                                                                                                                                                                                                                  | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2C.1 | 🎤 El proyecto React/TypeScript **compila y corre** sin errores de compilación. Demostración en vivo: `npm run dev` (o equivalente) y verificación en el navegador.                                                             |     |     |     |     |                          |
| 2C.2 | 👁 El frontend tiene **enrutamiento implementado** (React Router u otra) con al menos cinco rutas funcionales de vistas reales, y las rutas que requieren autenticación están protegidas.               |     |     |     |     |                          |
| 2C.3 | 👁 El frontend **consume la API REST del backend**: al menos dos módulos o páginas hacen peticiones HTTP reales (no datos hardcodeados) al backend de Django o Express, mostrando los datos en la interfaz.                       |     |     |     |     |                          |
| 2C.4 | 👁 El código TypeScript usa **tipado explícito** para los modelos de datos del dominio (no `any` generalizado) y el equipo implementa **manejo de estado** de manera organizada (Context API, Zustand, Redux u otra), explicando qué estado es global y por qué.          |     |     |     |     |                          |
| 2C.5 | 👁 La interfaz es **responsive**: funciona correctamente en móvil y escritorio, verificable en las DevTools del navegador.                                                                                                     |     |     |     |     |                          |

### Bloque 2D — Backend REST con JavaScript/Express (RA 04 parcial)

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                    | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2D.1 | 🎤 El servidor Express **arranca sin errores**, con al menos dos módulos de rutas organizados por dominio. Demostración en vivo.                                                                       |     |     |     |     |                          |
| 2D.2 | 👁 El servidor implementa **middleware de validación de datos** para las rutas de creación y actualización, con respuestas de error informativas (no solo `500`).                                                 |     |     |     |     |                          |
| 2D.3 | 🎤 Hay implementado un **sistema básico de autenticación con JWT**: rutas protegidas verifican el token, y el flujo de login/logout funciona correctamente con el frontend. Demo en vivo.                                                                                  |     |     |     |     |                          |
| 2D.4 | 👁 El servidor tiene **configuración de CORS correcta**: el frontend consume la API sin errores de acceso cruzado, sin CORS abierto indiscriminadamente en desarrollo.                                                                                   |     |     |     |     |                          |

### Bloque 2E — Pruebas de software (RA 05 — resultado completo)

> Al igual que el RA de BD NoSQL, el RA de pruebas se cierra en este trimestre como resultado completo. No se evalúa solo si el equipo "hizo algunas pruebas": se evalúa si el equipo tiene un proceso de pruebas documentado, reproducible y conectado a los requisitos del sistema.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                  | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2E.1 | 👁 Existe un **plan de pruebas** (alcance, niveles aplicados, herramientas, ambiente, criterios de entrada/salida) y una **matriz de casos de prueba** con al menos 15 casos documentados (ID, precondiciones, datos, pasos, resultado esperado/obtenido), distribuidos en al menos tres funcionalidades. |     |     |     |     |                          |
| 2E.2 | 🎤 El equipo implementó **pruebas unitarias automatizadas** para al menos un módulo del backend (Django con pytest/unittest o Express con Jest/Mocha). Ejecutables con un comando; el equipo las corre en el momento.                                   |     |     |     |     |                          |
| 2E.3 | 👁 El equipo realizó **pruebas de los endpoints REST** con Postman o equivalente: colección exportada en el repositorio con casos positivos y negativos.                            |     |     |     |     |                          |
| 2E.4 | 👁 Existe un **reporte de ejecución de pruebas** (casos ejecutados/pasados/fallidos) y los **defectos encontrados** están registrados en el sistema de seguimiento del equipo (Jira, GitHub Issues, Trello) con descripción, pasos para reproducir, severidad y responsable.                                                                                                                               |     |     |     |     |                          |

---

## DIMENSIÓN 3 — Documentación (15 %)

> En T3 de Cadena la documentación prioriza la utilidad técnica sobre el volumen. Un `README.md` que permite a otro desarrollador levantar el proyecto en 15 minutos vale más que 80 páginas de especificación que nadie lee.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                          | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 3.1 | 👁 El `README.md` describe claramente **propósito, arquitectura, stack con versiones, requisitos de entorno y pasos para instalar y ejecutar cada componente** (Django, Express, React, bases de datos). Un desarrollador externo debe poder levantar el proyecto siguiendo ese README. |     |     |     |     |                          |
| 3.2 | 👁 El **código del backend** tiene comentarios técnicos en las funciones o métodos más complejos: no en cada línea, sino explicaciones de la lógica no obvia.                                              |     |     |     |     |                          |
| 3.3 | 👁 Los **endpoints de la API están documentados** (Swagger/OpenAPI con `drf-spectacular` o similar, Postman collection, o `API.md`).                                                                                            |     |     |     |     |                          |
| 3.4 | 👁 El **plan de pruebas y la matriz de casos** están en el repositorio y accesibles desde el README, y la **estrategia de ramas** es coherente y visible (ramas para desarrollo y funcionalidades, main protegida, PRs descriptivos).                                                                                                                                        |     |     |     |     |                          |

---

## DIMENSIÓN 4 — Trabajo en Equipo (10 %)

> Se observa en simultáneo con las demos de D2, sin tiempo adicional en la sesión.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                           | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 4.1 | 👁 El **historial de contribuciones** muestra participación activa de todos los integrantes. No hay integrantes con cero commits en el período.                                                   |     |     |     |     |                          |
| 4.2 | 👁 Los **roles de Scrum** son operativos y visibles: el Product Owner habla sobre prioridades y decisiones de alcance, el Scrum Master describe impedimentos gestionados y los developers explican decisiones técnicas de su área.                |     |     |     |     |                          |
| 4.3 | 🎤 El equipo demuestra **integración técnica real**: el frontend funciona con el backend, el backend se conecta a las bases de datos, y las pruebas cubren el sistema integrado. No hay componentes aislados.                    |     |     |     |     |                          |
| 4.4 | 🎤 El equipo describe **cómo resolvió un conflicto técnico o de coordinación** durante el trimestre. El jurado evalúa la madurez del proceso, no si hubo o no problemas. |     |     |     |     |                          |

---

## DIMENSIÓN 5 — Calidad, Pruebas y Mejores Prácticas (15 %)

> Esta dimensión tiene mayor peso en T3 porque el RA de pruebas se cierra aquí. Se evalúa tanto la calidad del código como la calidad del proceso de verificación. Un equipo que solo prueba manualmente "a ojo" antes de la sustentación no cumple este estándar.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                      | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 5.1 | 👁 El equipo aplica y tiene documentado un **estándar de codificación** por tecnología (PEP 8, convenciones TS/JS, nomenclatura de BD) y tiene configuradas **herramientas de análisis estático** (ESLint, Flake8/Pylint) sin errores críticos.  |     |     |     |     |                          |
| 5.2 | 👁 El sistema implementa **manejo de errores adecuado** en todos los niveles: mensajes útiles en frontend, códigos HTTP correctos en backend, sin `console.log`/`print` de depuración en producción. |     |     |     |     |                          |
| 5.3 | 👁 Las **pruebas unitarias tienen cobertura razonable**: al menos el 50 % de las funciones del módulo más crítico del backend cubiertas, demostrable con el reporte del framework.                                     |     |     |     |     |                          |
| 5.4 | 👁 El equipo aplica **principios de seguridad básica**: contraseñas con hash, tokens JWT con expiración definida, consultas parametrizadas o vía ORM (sin inyección SQL).                                 |     |     |     |     |                          |

---

## Resumen de evaluación

| Dimensión                                 | Peso | Calificación del jurado | Notas |
| ----------------------------------------- | ---- | ----------------------- | ----- |
| D1 — Gestión del Proyecto                 | 15 % |                         |       |
| D2 — Artefactos Técnicos                  | 45 % |                         |       |
| D3 — Documentación                        | 15 % |                         |       |
| D4 — Trabajo en Equipo                    | 10 % |                         |       |
| D5 — Calidad, Pruebas y Mejores Prácticas | 15 % |                         |       |

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

_Instrumento de evaluación formativa — Programa ADSO 228118 · Cadena de Formación · Trimestre III (equivale a Trim V–VI del plan interno)_  
_Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital_
