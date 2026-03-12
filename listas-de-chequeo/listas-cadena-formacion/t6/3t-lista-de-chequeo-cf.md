# Lista de Chequeo — Trimestre III
## Seguimiento de Proyecto Formativo · Cadena de Formación
### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Modalidad:** Cadena de Formación (aprendices graduados como Técnicos en Desarrollo de Software)  
> **Equivalencia en el semáforo interno:** Trimestre V–VI del plan de formación  
> **Fase del proyecto formativo:** Construcción del Software — Proyecto III / IV  
> **Resultados de Aprendizaje activos:**
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

| Campo | Valor |
|-------|-------|
| Número de Ficha | |
| Nombre del grupo de proyecto | |
| Nombre del sistema / software | |
| Stack tecnológico activo | |
| URL del repositorio | |
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
| 🟡 | **Satisfactorio** | Cumple parcialmente o hay evidencia incompleta pero válida |
| 🔴 | **Insuficiente** | No cumple, evidencia muy débil o ausente |
| ➖ | **No aplica** | El ítem no corresponde al tipo o contexto de este proyecto |

---

## Ponderación por dimensión

| Dimensión | Peso |
|-----------|------|
| D1 — Gestión del Proyecto | 15 % |
| D2 — Artefactos Técnicos | 45 % |
| D3 — Documentación | 15 % |
| D4 — Trabajo en Equipo | 10 % |
| D5 — Calidad, Pruebas y Mejores Prácticas | 15 % |

> **Nota sobre la ponderación:** En T3 de Cadena la Dimensión 5 sube a 15 % porque el RA de pruebas es un resultado de aprendizaje completo (no parcial) que se cierra en este trimestre. Las pruebas no son un adorno: son parte integral de la construcción del software. La documentación baja a 15 % porque en esta fase los artefactos documentales ya están consolidados de T1 y T2; lo que se evalúa es que el código está documentado de manera técnica y que el repositorio refleja un flujo de trabajo profesional.

---

## DIMENSIÓN 1 — Gestión del Proyecto (15 %)

> En la fase de construcción la gestión ágil se vuelve operativa, no solo declarativa. El equipo debe poder mostrar que Scrum (o la metodología elegida) les está sirviendo para entregar software funcionando de manera incremental, no solo para organizar tareas en tarjetas de colores.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 1.1 | El **product backlog** está actualizado, priorizado y refleja el estado real del proyecto: las historias completadas están cerradas, las que están en progreso son las que el equipo puede demostrar en la sesión, y las pendientes están estimadas con puntos o talla de camiseta. | | | | | |
| 1.2 | El equipo puede mostrar **al menos dos sprints completados** este trimestre con sus sprint reviews documentados: qué se comprometió, qué se entregó, qué no se alcanzó y por qué. La demo de cada sprint review debería ser código funcionando, no diapositivas. | | | | | |
| 1.3 | Existe evidencia de las **ceremonias de seguimiento diario** (daily standup): puede ser un canal de Slack/Discord con mensajes de estado, un tablero con tarjetas de "bloqueado" o capturas de reuniones cortas. El jurado no necesita ver todas las dailies, sino evidencia de que el equipo se comunica activamente sobre el avance. | | | | | |
| 1.4 | El equipo realizó al menos una **retrospectiva formal** del período y puede presentar sus conclusiones: qué mejoró respecto a T2 en términos de proceso, qué práctica nueva adoptaron y si hubo ajustes al backlog como resultado de la retrospectiva. | | | | | |
| 1.5 | El **ritmo de commits en el repositorio** es consistente durante las semanas del trimestre, no concentrado en los días previos a la sustentación. Esto es verificable en el gráfico de actividad de GitHub/GitLab. | | | | | |

---

## DIMENSIÓN 2 — Artefactos Técnicos (45 %)

> Este es el núcleo de la evaluación en T3. Se divide en cinco bloques correspondientes a los módulos técnicos activos. El jurado debe verificar cada bloque mediante demostración en vivo cuando sea posible: ver código corriendo es mucho más fiable que ver diapositivas con capturas de pantalla.

### Bloque 2A — Backend con Django: planificación y construcción (RA 01 y RA 04 parciales)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2A.1 | El proyecto Django arranca **sin errores** en el entorno local del equipo. El jurado puede solicitar una demostración: `python manage.py runserver` y verificar que el servidor levanta correctamente. | | | | | |
| 2A.2 | El proyecto tiene una **estructura de carpetas organizada** acorde con la arquitectura Django (apps separadas por dominio, carpeta de configuración `settings/`, templates o API views según el enfoque elegido). | | | | | |
| 2A.3 | El equipo implementa al menos **dos apps Django** del proyecto con sus modelos, vistas (o ViewSets si usan Django REST Framework) y rutas (`urls.py`) correctamente configuradas. | | | | | |
| 2A.4 | El backend expone una **API REST funcional** con al menos un CRUD completo para el recurso principal del sistema. Los endpoints pueden demostrarse con Postman o el Swagger/Redoc generado automáticamente por DRF. | | | | | |
| 2A.5 | El proyecto usa **variables de entorno** para la configuración sensible (cadena de conexión a BD, claves secretas, credenciales de servicios externos). No hay contraseñas ni API keys escritas directamente en el código (`settings.py` no contiene secretos en texto plano). | | | | | |
| 2A.6 | Existe un archivo `requirements.txt` o `pyproject.toml` actualizado que **lista todas las dependencias del proyecto**. Otro desarrollador puede instalarlas con un solo comando y levantar el proyecto. | | | | | |

### Bloque 2B — Base de datos NoSQL: MongoDB y/o Redis (RA 02 — resultado FINAL)

> Este es el único RA que se cierra como **resultado FINAL** en este trimestre. Por esa razón los criterios son más exigentes: no se acepta un resultado parcial ni "en progreso". El equipo debe demostrar dominio completo de al menos un motor NoSQL integrado al sistema.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2B.1 | El equipo puede demostrar una **instancia de MongoDB o Redis funcionando** en su entorno local o en la nube, con al menos una colección o estructura de datos del proyecto real (no datos de tutorial genérico). | | | | | |
| 2B.2 | Existe una **justificación técnica documentada** de por qué el proyecto usa NoSQL y para qué casos de uso específicos: qué tipo de datos se almacenan en el motor NoSQL, por qué ese tipo de datos no encaja bien en el modelo relacional, y qué ventaja concreta aporta la solución NoSQL elegida. | | | | | |
| 2B.3 | Si usan **MongoDB**: el equipo puede demostrar operaciones de inserción, consulta con filtros y operadores (`$eq`, `$gt`, `$in`, `$and`), actualización y eliminación sobre documentos del proyecto. El esquema de los documentos está justificado (documentos embebidos vs. referencias) según las necesidades del sistema. | | | | | |
| 2B.4 | Si usan **Redis**: el equipo puede demostrar al menos uno de estos casos de uso reales en el proyecto: caché de consultas frecuentes, gestión de sesiones, cola de tareas o almacenamiento de datos de tiempo real. El equipo puede explicar la política de expiración de claves y por qué se eligió ese tiempo de vida. | | | | | |
| 2B.5 | La integración del motor NoSQL con el backend está **documentada en el repositorio**: hay al menos un módulo o servicio en el código que demuestra la conexión, la lectura y la escritura en el motor NoSQL desde la aplicación. | | | | | |

### Bloque 2C — Frontend SPA con React/TypeScript (RA 03)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2C.1 | El proyecto React/TypeScript **compila y corre** sin errores de compilación. El jurado puede solicitar `npm run dev` (o el equivalente) y verificar que la aplicación abre en el navegador. | | | | | |
| 2C.2 | El frontend tiene **enrutamiento implementado** (React Router u otra solución) con al menos cinco rutas funcionales que corresponden a vistas reales del sistema. Las rutas que requieren autenticación están protegidas. | | | | | |
| 2C.3 | El frontend **consume la API REST del backend**: hay al menos dos módulos o páginas que hacen peticiones HTTP reales (no datos hardcodeados) al backend de Django o Express, y muestran los datos en la interfaz. | | | | | |
| 2C.4 | El código TypeScript usa **tipado explícito** para los modelos de datos del dominio: hay interfaces o tipos definidos para las entidades principales del sistema, y las peticiones a la API usan esos tipos. No hay `any` generalizado. | | | | | |
| 2C.5 | El equipo implementa **manejo de estado** de manera organizada: Context API, Zustand, Redux u otra solución. El estado global no está duplicado en múltiples componentes sin justificación, y el flujo de datos es predecible. | | | | | |
| 2C.6 | La interfaz es **responsive**: funciona correctamente en móvil y escritorio, verificable en las DevTools del navegador durante la sustentación. | | | | | |

### Bloque 2D — Backend REST con JavaScript/Express (RA 04 parcial)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2D.1 | El servidor Express **arranca sin errores** y el equipo puede demostrarlo en el momento. Existen al menos dos módulos de rutas organizados por dominio (por ejemplo, `routes/usuarios.js` y `routes/productos.js`). | | | | | |
| 2D.2 | El servidor implementa **middleware de validación de datos** para al menos las rutas de creación y actualización: los campos requeridos son verificados antes de llegar a la capa de lógica de negocio, y las respuestas de error son informativas (no solo `500 Internal Server Error`). | | | | | |
| 2D.3 | Hay implementado un **sistema básico de autenticación con JWT**: las rutas protegidas verifican el token antes de ejecutar la lógica, y el flujo de login/logout funciona correctamente con el frontend. | | | | | |
| 2D.4 | El servidor tiene **configuración de CORS correcta**: el frontend puede consumir la API sin errores de acceso cruzado, y la configuración de CORS no está abierta indiscriminadamente a todos los orígenes en el entorno de desarrollo. | | | | | |

### Bloque 2E — Pruebas de software (RA 05 — resultado completo)

> Al igual que el RA de BD NoSQL, el RA de pruebas se cierra en este trimestre como resultado completo. No se evalúa solo si el equipo "hizo algunas pruebas": se evalúa si el equipo tiene un proceso de pruebas documentado, reproducible y conectado a los requisitos del sistema.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 2E.1 | Existe un **plan de pruebas** del proyecto que define: alcance de las pruebas, niveles aplicados (unitarias, integración, sistema), herramientas usadas, ambiente de prueba y criterios de entrada y salida del proceso. | | | | | |
| 2E.2 | Existe una **matriz de casos de prueba** con al menos 15 casos documentados: identificador, nombre descriptivo, precondiciones, datos de entrada, pasos de ejecución, resultado esperado y resultado obtenido. Los casos están distribuidos entre al menos tres funcionalidades diferentes del sistema. | | | | | |
| 2E.3 | El equipo implementó **pruebas unitarias automatizadas** para al menos un módulo del backend (Django con pytest/unittest o Express con Jest/Mocha). Las pruebas corren con un comando y producen un reporte de resultados. El equipo puede ejecutarlas en el momento. | | | | | |
| 2E.4 | El equipo realizó **pruebas de los endpoints REST** con Postman o herramienta equivalente. Existe una colección de pruebas exportada en el repositorio que incluye casos positivos (datos válidos) y casos negativos (datos inválidos, campos faltantes, sin autenticación). | | | | | |
| 2E.5 | Existe un **reporte de ejecución de pruebas** que documenta: número de casos ejecutados, número de casos pasados, número de casos fallidos, defectos encontrados y estado de cada defecto (abierto, cerrado, postergado). | | | | | |
| 2E.6 | Los **defectos encontrados en las pruebas** están registrados en el sistema de seguimiento del equipo (Jira, GitHub Issues, Trello) con al menos: descripción del defecto, pasos para reproducirlo, severidad y el integrante asignado para corregirlo. | | | | | |

---

## DIMENSIÓN 3 — Documentación (15 %)

> En T3 de Cadena la documentación prioriza la utilidad técnica sobre el volumen. Un `README.md` que permite a otro desarrollador levantar el proyecto en 15 minutos vale más que 80 páginas de especificación que nadie lee.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 3.1 | El `README.md` del repositorio describe claramente: **propósito del sistema, arquitectura resumida, stack tecnológico con versiones, requisitos de entorno y pasos para instalar y ejecutar cada componente** (backend Django, backend Express, frontend React, bases de datos). Un desarrollador externo debe poder levantar el proyecto siguiendo ese README. | | | | | |
| 3.2 | El **código del backend** tiene comentarios técnicos en las funciones o métodos más complejos. No se buscan comentarios en cada línea, sino explicaciones de la lógica no obvia: por qué se hace una validación específica, qué formato espera un campo, qué retorna una función con lógica de negocio no trivial. | | | | | |
| 3.3 | Los **endpoints de la API están documentados** de alguna forma accesible: Swagger/OpenAPI generado automáticamente (DRF con `drf-spectacular` o similar), Postman collection exportada, o un archivo `API.md` en el repositorio con la descripción de cada endpoint. | | | | | |
| 3.4 | El **plan de pruebas y la matriz de casos de prueba** están en el repositorio en formato Markdown, Excel o la herramienta de gestión del equipo, y son accesibles desde el README. No deben estar en un archivo local en la máquina de un integrante. | | | | | |
| 3.5 | La **estrategia de ramas** del repositorio es coherente y visible: hay ramas para desarrollo, para funcionalidades específicas y la rama principal solo recibe código revisado. El log de merges/pull requests es legible y descriptivo. | | | | | |

---

## DIMENSIÓN 4 — Trabajo en Equipo (10 %)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 4.1 | El **historial de contribuciones** del repositorio muestra participación activa de todos los integrantes. No hay integrantes con cero commits en el período del trimestre. El jurado puede revisar el gráfico de contribuidores en el momento. | | | | | |
| 4.2 | Los **roles de Scrum** son operativos y visibles: el Product Owner puede hablar sobre las prioridades del negocio y las decisiones de alcance, el Scrum Master puede describir los impedimentos que gestionó y los developers pueden explicar las decisiones técnicas de su área. | | | | | |
| 4.3 | El equipo demuestra **integración técnica real**: el frontend funciona con el backend, el backend se conecta a las bases de datos, y las pruebas cubren el sistema integrado. No hay componentes aislados que solo funcionan en la máquina del integrante que los desarrolló. | | | | | |
| 4.4 | El equipo puede describir **cómo resolvió un conflicto técnico o de coordinación** durante el trimestre (un merge conflict complejo, un diseño de API que cambió afectando al frontend, un integrante que bloqueó al resto). El jurado evalúa la madurez del proceso, no si hubo o no problemas. | | | | | |

---

## DIMENSIÓN 5 — Calidad, Pruebas y Mejores Prácticas (15 %)

> Esta dimensión tiene mayor peso en T3 porque el RA de pruebas se cierra aquí. Se evalúa tanto la calidad del código como la calidad del proceso de verificación. Un equipo que solo prueba manualmente "a ojo" antes de la sustentación no cumple este estándar.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|----|
| 5.1 | El equipo tiene y aplica un **estándar de codificación** documentado para cada tecnología del stack: convenciones de nombres en Python (PEP 8), convenciones en TypeScript/JavaScript (camelCase, interfaces con `I` prefijo o no), nomenclatura de tablas y campos en la BD. El código en el repositorio es consistente con ese estándar. | | | | | |
| 5.2 | El proyecto tiene configuradas **herramientas de análisis de código estático**: ESLint para JavaScript/TypeScript, Flake8 o Pylint para Python. Estas herramientas no reportan errores críticos en el código actual del proyecto. | | | | | |
| 5.3 | El sistema implementa **manejo de errores adecuado** en todos los niveles: el frontend muestra mensajes de error útiles al usuario (no alertas genéricas del navegador), el backend retorna códigos HTTP correctos con mensajes descriptivos, y no hay `console.log` de depuración ni `print` de Python dejados en el código de producción. | | | | | |
| 5.4 | Las **pruebas unitarias tienen una cobertura razonable** de los módulos de lógica de negocio: al menos el 50 % de las funciones o métodos del módulo más crítico del backend están cubiertos por pruebas automatizadas. El equipo puede demostrar la cobertura con el reporte del framework de pruebas. | | | | | |
| 5.5 | El equipo aplica **principios de seguridad básica** verificables en el código: las contraseñas se almacenan con hash (no en texto plano), los tokens JWT tienen tiempo de expiración definido, las consultas a la base de datos no son vulnerables a inyección SQL (uso de ORM o consultas parametrizadas). | | | | | |

---

## Resumen de evaluación

| Dimensión | Peso | Calificación del jurado | Notas |
|-----------|------|-------------------------|-------|
| D1 — Gestión del Proyecto | 15 % | | |
| D2 — Artefactos Técnicos | 45 % | | |
| D3 — Documentación | 15 % | | |
| D4 — Trabajo en Equipo | 10 % | | |
| D5 — Calidad, Pruebas y Mejores Prácticas | 15 % | | |

---

## Decisión del jurado

| Decisión | Seleccionar |
|----------|-------------|
| ☐ **Aprobado sin condiciones** | El equipo continúa al T4 con el proyecto vigente. |
| ☐ **Aprobado con condicionamientos** | Continúa pero debe resolver los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora** | El grupo tiene hasta [fecha] para subsanar los ítems críticos y presentar nuevamente. |

### Condicionamientos o ajustes requeridos

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
|-------------------------------|-----------------|--------------|
| | | |
| | | |

---

## Retroalimentación cualitativa del jurado

| Jurado | Fortaleza principal observada este trimestre | Riesgo más importante a gestionar en T4 |
|--------|----------------------------------------------|------------------------------------------|
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

*Instrumento de evaluación formativa — Programa ADSO 228118 · Cadena de Formación · Trimestre III (equivale a Trim V–VI del plan interno)*  
*Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital*