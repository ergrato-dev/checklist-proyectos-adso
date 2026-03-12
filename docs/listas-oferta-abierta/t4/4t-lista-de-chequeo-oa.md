# Lista de Chequeo — Trimestre IV
## Seguimiento de Proyecto Formativo · Oferta Abierta
### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Fase del proyecto formativo:** Construcción del Software — Proyecto IV
>
> **Resultados de Aprendizaje activos este trimestre:**
> - Construcción del Software → RA 03: Crear componentes front-end de acuerdo con el diseño — **resultado completo**
> - Construcción del Software → RA 04: Codificar el software de acuerdo con el diseño — **resultado parcial**
> - Construcción del Software → RA 02: Construir la base de datos — **resultado parcial**
> - Propuesta Técnica → RA 01: Definir especificaciones técnicas del software
> - Propuesta Técnica → RA 02: Elaborar propuesta técnica
> - Propuesta Técnica → RA 03: Validar condiciones de la propuesta técnica
>
> **Módulos técnicos activos:** Front End 1 React/TypeScript · REST Python FastAPI (resultado parcial) · SQL Extendido — funciones, procedimientos almacenados y triggers · Realización y Estimación de Propuesta Técnica
>
> **Propósito del trimestre:** T4 es el trimestre de construcción activa con el stack completo del programa. Por primera vez el equipo tiene un frontend SPA real (React/TypeScript) comunicándose con un backend REST (FastAPI), respaldado por una base de datos con lógica programada (procedimientos y triggers). Simultáneamente, el equipo debe formalizar la Propuesta Técnica del proyecto, que es el documento que cierra el ciclo análisis → diseño → construcción y le da viabilidad contractual al sistema. El jurado en T4 evalúa **software funcionando de manera integrada**, no módulos aislados: el frontend debe hablar con el backend, el backend debe usar la base de datos, y la propuesta técnica debe describir ese mismo sistema que se está construyendo.

---

## Datos de la sesión

| Campo | Valor |
|-------|-------|
| Número de Ficha | |
| Nombre del grupo de proyecto | |
| Nombre del sistema / software | |
| Stack tecnológico declarado | |
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
| 🟡 | **Satisfactorio** | Cumple parcialmente; evidencia incompleta pero válida |
| 🔴 | **Insuficiente** | No cumple o la evidencia es muy débil / ausente |
| ➖ | **No aplica** | El ítem no corresponde al tipo o contexto de este proyecto |

---

## Ponderación por dimensión

| Dimensión | Peso |
|-----------|------|
| D1 — Gestión del Proyecto | 15 % |
| D2 — Artefactos Técnicos | 45 % |
| D3 — Documentación y Propuesta Técnica | 20 % |
| D4 — Trabajo en Equipo | 10 % |
| D5 — Calidad y Mejores Prácticas | 10 % |

> **Nota pedagógica:** La Documentación sube a 20 % porque en T4 la Propuesta Técnica es un resultado de aprendizaje completo en sí mismo, no un documento de soporte. Es el primer entregable del programa que tiene un valor "contractual": describe qué se construye, a qué costo estimado, con qué tecnología y bajo qué condiciones. Los equipos que la traten como un trámite administrativo lo reflejarán en la nota.

---

## DIMENSIÓN 1 — Gestión del Proyecto (15 %)

> En T4 la gestión debe mostrar madurez real: el equipo lleva cuatro trimestres trabajando juntos y debería poder gestionar su proceso de manera autónoma, anticipar riesgos técnicos y mantener el backlog sincronizado con el estado real de la construcción.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 1.1 | El **tablero de seguimiento** está actualizado a la fecha de sustentación y muestra el avance real del sprint activo: tareas en progreso, completadas y pendientes son consistentes con lo que el equipo demuestra en la sesión. El jurado puede pedir ver el tablero en vivo. | | | | | |
| 1.2 | El equipo tiene documentados al menos **dos sprints completados** este trimestre, cada uno con objetivo de sprint, historias comprometidas, resultado de la demo y retrospectiva con al menos un ítem de mejora implementado. | | | | | |
| 1.3 | El equipo puede presentar el **estado del backlog total del proyecto**: cuántas historias de usuario están terminadas, cuántas en progreso, cuántas pendientes para T5, y si el alcance del sistema ha cambiado respecto a lo definido en el SRS del T2. Si hubo cambios de alcance, están documentados. | | | | | |
| 1.4 | Existe un **registro de impedimentos** del trimestre: al menos dos situaciones que bloquearon o retrasaron el trabajo (deuda técnica, dificultad con una librería, conflicto de integración frontend-backend) con la descripción de cómo se resolvieron o mitigaron. | | | | | |

---

## DIMENSIÓN 2 — Artefactos Técnicos (45 %)

### Bloque 2A — Frontend SPA con React/TypeScript (RA 03 — resultado FINAL)

> Este RA se cierra definitivamente en T4. El jurado no puede aceptar un frontend en construcción preliminar: debe estar funcional, tipado, conectado al backend y demostrable en vivo. La exigencia es proporcional al hecho de que es el cierre del resultado.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2A.1 | La aplicación React/TypeScript **compila sin errores ni warnings de TypeScript**. El jurado puede solicitar que el equipo ejecute `tsc --noEmit` o que abra la consola del navegador durante la demo para verificar que no hay errores en tiempo de ejecución. | | | | | |
| 2A.2 | El frontend implementa **al menos cinco vistas funcionales** que corresponden a los casos de uso del proyecto. Las vistas no son pantallas estáticas: muestran datos reales provenientes de la API, permiten interacción del usuario y responden a las acciones con feedback visual. | | | | | |
| 2A.3 | El código TypeScript usa **interfaces o tipos definidos** para todos los modelos de datos del dominio que viajan entre el frontend y la API. No hay uso de `any` sin justificación técnica documentada. | | | | | |
| 2A.4 | El frontend implementa **autenticación y autorización** funcionales: hay un flujo de login que obtiene un token, ese token se almacena de manera segura (no en `localStorage` sin cifrado para datos sensibles), y las rutas protegidas redirigen al usuario no autenticado. | | | | | |
| 2A.5 | El estado de la aplicación está gestionado de manera **organizada y predecible**: si el equipo usa Context API, Zustand o Redux, puede explicar qué estado vive globalmente y por qué, y qué estado es local a un componente. No hay prop drilling de más de dos niveles sin justificación. | | | | | |
| 2A.6 | La interfaz es **responsive y consistente**: funciona correctamente en móvil, tablet y escritorio. El sistema de estilos (Tailwind, CSS Modules, styled-components u otro) es coherente y no hay mezcla de múltiples enfoques sin razón técnica. | | | | | |
| 2A.7 | El frontend **maneja errores de red y de usuario** de manera explícita: si la API devuelve un error, la interfaz muestra un mensaje útil al usuario; si un formulario tiene campos inválidos, los errores se muestran en línea junto al campo afectado, no en una alerta genérica. | | | | | |

### Bloque 2B — Backend REST con Python FastAPI (RA 04 — resultado parcial)

> FastAPI es el segundo backend del programa y el primero en Python. El resultado es parcial en T4 porque la codificación completa se cierra en T5-T6. Lo que se evalúa aquí es que el equipo domina la estructura de FastAPI, construye endpoints funcionales con tipado Pydantic y conecta el sistema con la base de datos.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2B.1 | El servidor FastAPI **arranca sin errores** y el jurado puede verificarlo en el momento. La documentación automática de Swagger UI (`/docs`) está disponible y muestra todos los endpoints implementados correctamente organizados por router. | | | | | |
| 2B.2 | El proyecto implementa al menos **dos recursos REST completos** (CRUD) para entidades del dominio del sistema. Los schemas Pydantic están definidos para validación de entrada y serialización de salida, con tipos correctos, campos opcionales bien declarados y mensajes de error descriptivos. | | | | | |
| 2B.3 | El proyecto sigue una **estructura de carpetas por capas o por dominio**: hay separación entre routers, schemas, modelos de base de datos (SQLAlchemy u ORM equivalente), servicios o repositorios. El archivo `main.py` no contiene lógica de negocio. | | | | | |
| 2B.4 | La API implementa **autenticación con JWT mediante OAuth2PasswordBearer** de FastAPI. Los endpoints protegidos verifican el token antes de ejecutar la lógica, y el flujo de obtención del token (`/auth/token`) funciona correctamente y es demostrable con Swagger UI o Postman. | | | | | |
| 2B.5 | El proyecto usa **variables de entorno** para toda la configuración sensible: cadena de conexión a la BD, clave secreta del JWT, configuración de CORS. Existe un archivo `.env.example` en el repositorio con las variables necesarias (sin valores reales) para que otro desarrollador configure su entorno. | | | | | |
| 2B.6 | Existe un archivo `requirements.txt` o `pyproject.toml` actualizado y el equipo puede demostrar que el proyecto **se instala y corre en un entorno limpio** con los pasos descritos en el README. | | | | | |

### Bloque 2C — Base de Datos: SQL extendido (RA 02 — resultado parcial)

> En T4 la base de datos deja de ser solo esquemas y consultas para convertirse en una capa con lógica programada. Funciones, procedimientos almacenados y triggers son mecanismos que permiten encapsular reglas de negocio críticas directamente en el motor, garantizando su ejecución independientemente de qué aplicación acceda a la BD. El jurado debe verificar que el equipo entiende cuándo usar cada uno.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2C.1 | El equipo tiene implementada al menos **una función SQL** específica del proyecto (no un ejemplo genérico) que encapsula un cálculo o transformación de datos del dominio. El equipo puede explicar por qué esa lógica vive en la base de datos y no en el backend. | | | | | |
| 2C.2 | Existe al menos **un procedimiento almacenado** del proyecto que ejecuta una operación de negocio compuesta: más de una instrucción DML, uso de variables, control de flujo (IF/CASE) y manejo básico de excepciones. El procedimiento tiene un propósito claro en el contexto del sistema. | | | | | |
| 2C.3 | Existe al menos **un trigger** implementado en el proyecto con un propósito funcional real: auditoría de cambios, validación de integridad no expresable como constraint, actualización automática de datos derivados. El equipo puede explicar qué evento lo dispara y qué acción ejecuta. | | | | | |
| 2C.4 | Todos los objetos programables (función, procedimiento, trigger) están **versionados en el repositorio** como scripts `.sql` ejecutables. El equipo puede demostrar que se pueden correr desde cero en una base de datos vacía. | | | | | |
| 2C.5 | El equipo demuestra dominio de **transacciones SQL**: puede explicar qué operaciones del sistema requieren `BEGIN / COMMIT / ROLLBACK` y por qué, con al menos un ejemplo concreto del proyecto donde la transaccionalidad es crítica para la integridad de los datos. | | | | | |

### Bloque 2D — Integración frontend ↔ backend ↔ base de datos

> Este bloque no corresponde a un módulo aislado: evalúa la coherencia del sistema completo. Es el bloque más representativo del estado real del proyecto y el que el jurado debe verificar siempre con una demostración en vivo, no con capturas de pantalla.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2D.1 | El equipo puede realizar una **demo en vivo del flujo completo** de al menos un caso de uso del sistema: el usuario interactúa con el frontend → el frontend llama a la API de FastAPI → FastAPI consulta o modifica la base de datos → el resultado se refleja en la interfaz. Sin capturas de pantalla: código corriendo en el momento. | | | | | |
| 2D.2 | El sistema maneja correctamente el **ciclo de autenticación completo**: login en el frontend, token enviado al backend en el header `Authorization: Bearer`, validación del token en los endpoints protegidos, y logout que invalida la sesión. | | | | | |
| 2D.3 | No hay **datos hardcodeados** en el frontend: todos los listados, tablas y formularios del sistema consumen datos reales de la API. Si hay datos de ejemplo, están en la base de datos del proyecto, no escritos como constantes en el código JavaScript/TypeScript. | | | | | |

---

## DIMENSIÓN 3 — Documentación y Propuesta Técnica (20 %)

> La Propuesta Técnica es el resultado de aprendizaje estrella de esta dimensión en T4. Es el primer documento del programa con carácter "contractual": representa el acuerdo entre el equipo de desarrollo y el cliente sobre qué se va a construir, con qué tecnología, en cuánto tiempo y a qué costo estimado. El jurado debe evaluarla con la misma rigurosidad con que un comité técnico evaluaría una propuesta de proveedor de software.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3.1 | La **Propuesta Técnica** es un documento formal que incluye al menos: resumen ejecutivo, descripción del problema que resuelve el sistema, alcance del proyecto (qué incluye y qué no incluye explícitamente), stack tecnológico seleccionado con justificación técnica, y metodología de desarrollo. No es un resumen del SRS: es un documento orientado a convencer a un cliente de que el equipo puede construir el sistema. | | | | | |
| 3.2 | La propuesta incluye una **estimación de costos** con desglose: horas de desarrollo por rol (frontend, backend, DBA, QA), costo por hora estimado, subtotal por componente y total del proyecto. Los números deben ser coherentes con el alcance descrito: una propuesta que estima 10 horas para construir un sistema de 30 casos de uso no es creíble. | | | | | |
| 3.3 | La propuesta incluye un **cronograma** (diagrama de Gantt o tabla de sprints) que muestra las fases del proyecto con fechas estimadas, hitos de entrega y dependencias entre actividades. El cronograma debe ser consistente con el backlog del proyecto y con el tiempo transcurrido realmente en la formación. | | | | | |
| 3.4 | La propuesta incluye un **análisis de riesgos técnicos y de gestión**: al menos cinco riesgos identificados con probabilidad estimada (alta/media/baja), impacto (alto/medio/bajo) y estrategia de mitigación concreta. Los riesgos son específicos del proyecto, no genéricos copiados de una plantilla. | | | | | |
| 3.5 | El **README del repositorio** está actualizado para T4: describe cómo levantar el sistema completo (frontend + FastAPI + base de datos), qué variables de entorno se necesitan y cuáles son los pasos de instalación para cada componente. Un desarrollador externo puede seguir las instrucciones y ver el sistema funcionando. | | | | | |
| 3.6 | La **colección de Postman** o la documentación Swagger exportada está en el repositorio y cubre todos los endpoints implementados hasta T4, con ejemplos de petición y respuesta tanto para casos exitosos como para casos de error. | | | | | |

---

## DIMENSIÓN 4 — Trabajo en Equipo (10 %)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 4.1 | El **historial de commits** muestra contribuciones distribuidas entre todos los integrantes durante el período del trimestre. No hay integrantes con cero actividad. El jurado puede revisar el gráfico de contribuidores en vivo. | | | | | |
| 4.2 | El equipo usa **ramas y pull requests** de manera sistemática: las funcionalidades nuevas se desarrollan en ramas separadas, los merges a la rama principal tienen al menos un revisor y el log de pull requests es legible. | | | | | |
| 4.3 | Durante la sustentación, **todos los integrantes presentes demuestran comprensión del sistema completo**: si el jurado pregunta a un integrante de backend sobre el comportamiento de un componente de frontend, debe poder dar una respuesta coherente aunque no sea experto en esa capa. | | | | | |
| 4.4 | El equipo puede describir cómo dividió el trabajo para construir la **integración frontend-backend**: quién definió el contrato de la API, cómo se coordinaron cuando el backend no estaba listo y el frontend lo necesitaba, y si usaron mocking o stubs para desacoplar el desarrollo. | | | | | |

---

## DIMENSIÓN 5 — Calidad y Mejores Prácticas (10 %)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 5.1 | El código Python del backend sigue **PEP 8** y el equipo tiene configurado al menos un linter (Flake8, Ruff o Pylint). No hay errores críticos de estilo en el código del repositorio. | | | | | |
| 5.2 | El código TypeScript del frontend no tiene **errores de compilación de TypeScript** y tiene configurado ESLint con un ruleset razonable (Airbnb, Standard u otro). No hay `@ts-ignore` masivos ni `any` sin comentario justificativo. | | | | | |
| 5.3 | La API de FastAPI sigue **convenciones REST**: rutas con sustantivos en plural, verbos HTTP correctos, códigos de respuesta HTTP semánticamente correctos (200, 201, 204, 400, 401, 403, 404, 422, 500) y los errores de validación de Pydantic se propagan al cliente de manera legible. | | | | | |
| 5.4 | El equipo tiene al menos **pruebas básicas del backend FastAPI** con pytest: al menos un módulo de pruebas que usa el `TestClient` de FastAPI para verificar que los endpoints principales responden correctamente con datos válidos e inválidos. | | | | | |
| 5.5 | Los **objetos SQL programables** (función, procedimiento, trigger) tienen comentarios que explican su propósito, los parámetros de entrada/salida y los casos límite que manejan. No son bloques de código sin documentación. | | | | | |

---

## Resumen de evaluación

| Dimensión | Peso | Calificación del jurado | Notas |
|-----------|------|-------------------------|-------|
| D1 — Gestión del Proyecto | 15 % | | |
| D2 — Artefactos Técnicos | 45 % | | |
| D3 — Documentación y Propuesta Técnica | 20 % | | |
| D4 — Trabajo en Equipo | 10 % | | |
| D5 — Calidad y Mejores Prácticas | 10 % | | |

---

## Decisión del jurado

| Decisión | Seleccionar |
|----------|-------------|
| ☐ **Aprobado sin condiciones** | El equipo continúa al T5 con el proyecto vigente. |
| ☐ **Aprobado con condicionamientos** | Continúa pero debe subsanar los ajustes indicados antes de la siguiente sesión de seguimiento. |
| ☐ **Aplazado — plan de mejora** | El grupo tiene hasta [fecha] para resolver los ítems críticos y presentar nuevamente. |

### Condicionamientos o ajustes requeridos

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
|-------------------------------|-----------------|--------------|
| | | |
| | | |

---

## Retroalimentación cualitativa del jurado

| Jurado | Fortaleza principal observada en T4 | Riesgo más importante a gestionar en T5 |
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

*Instrumento de evaluación formativa — Programa ADSO 228118 · Oferta Abierta · Trimestre IV*
*Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital*