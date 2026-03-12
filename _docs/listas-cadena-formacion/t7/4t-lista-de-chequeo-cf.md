# Lista de Chequeo — Trimestre IV
## Seguimiento de Proyecto Formativo · Cadena de Formación
### Programa ADSO Cód. 228118 | SENA — Centro de Gestión de Mercados, Logística y TI | Regional Distrito Capital

---

> **Modalidad:** Cadena de Formación (aprendices graduados como Técnicos en Desarrollo de Software)
> **Equivalencia en el semáforo interno:** Trimestre VII del plan de formación
> **Fase del proyecto formativo:** Construcción final + Implantación del Software — Proyecto IV (cierre de etapa lectiva)
>
> **Resultados de Aprendizaje que se cierran definitivamente en este trimestre:**
>
> **Competencia Construcción del Software:**
> - RA 01: Planear actividades de construcción del software — **resultado FINAL**
> - RA 04: Codificar el software de acuerdo con el diseño — **resultado FINAL**
>
> **Competencia Implantación del Software:**
> - RA 01: Planear actividades de implantación del software de acuerdo con las condiciones del sistema
> - RA 02: Desplegar el software de acuerdo con la arquitectura y las políticas establecidas
> - RA 03: Documentar el proceso de implantación siguiendo estándares de calidad
> - RA 04: Implantar el software de acuerdo con los niveles de servicio establecidos con el cliente
>
> **Competencia Aseguramiento de la Calidad del Software:**
> - RA 01: Incorporar actividades de aseguramiento de la calidad de acuerdo con estándares de la industria
> - RA 02: Verificar la calidad del software de acuerdo con las prácticas de los procesos de desarrollo
> - RA 03: Realizar actividades de mejora de la calidad a partir de los resultados de la verificación
>
> **Módulos técnicos activos:** Asesoría de Desarrollo / Codificación final · Implantación, despliegue y elaboración de manuales técnicos y de usuario · Migración y copias de seguridad · Buenas prácticas de calidad de software · Fundamentos IoT (módulo electivo) · Desarrollo Móvil (módulo electivo)
>
> **Propósito del trimestre:** Este es el trimestre de cierre lectivo de la Cadena de Formación. No se trata solo de terminar el código: se trata de entregar un sistema que pueda vivir en producción real o en el entorno del cliente simulado. El equipo debe demostrar que el software está desplegado (no solo corriendo localmente), que tiene manuales que permiten a un usuario final operarlo sin asistencia del equipo de desarrollo, que hay una estrategia de respaldo y migración de datos, y que el proceso de construcción siguió estándares de calidad verificables. Es la primera vez en el programa donde el jurado evalúa el software como producto terminado, no como trabajo en progreso. La pregunta central del T4 de Cadena es: **¿este sistema está listo para ser usado por alguien que no pertenece al equipo de desarrollo?**

---

## Datos de la sesión

| Campo | Valor |
|-------|-------|
| Número de Ficha | |
| Nombre del grupo de proyecto | |
| Nombre del sistema / software | |
| Stack tecnológico completo | |
| URL del repositorio | |
| URL del sistema desplegado (si aplica) | |
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
| D1 — Gestión del Proyecto | 10 % |
| D2 — Artefactos Técnicos (sistema funcionando) | 35 % |
| D3 — Implantación y Despliegue | 20 % |
| D4 — Documentación y Calidad | 20 % |
| D5 — Trabajo en Equipo y Proceso | 15 % |

> **Nota sobre la ponderación:** En T4 de Cadena la distribución cambia de manera significativa respecto a trimestres anteriores, porque las competencias de Implantación y de Aseguramiento de Calidad son nuevas y tienen el mismo peso que los artefactos técnicos. No se puede tener un sistema excelente en código pero sin desplegar ni documentar: ambas dimensiones son igualmente obligatorias para cerrar la etapa lectiva. La gestión baja a 10 % porque a estas alturas del programa debe ser completamente autónoma y no requiere el mismo nivel de andamiaje evaluativo que en T1.

---

## DIMENSIÓN 1 — Gestión del Proyecto (10 %)

> En el último trimestre lectivo la gestión se evalúa más como cierre que como proceso: ¿el equipo puede hacer un balance honesto de lo que construyó, lo que no alcanzó y por qué? Esa capacidad de análisis retrospectivo es más valiosa pedagógicamente que un tablero perfectamente ordenado el día de la sustentación.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 1.1 | El equipo puede presentar el **estado final del backlog del proyecto**: porcentaje de historias de usuario completadas respecto al total del SRS original, con justificación documentada para las historias que quedaron fuera del alcance de la etapa lectiva. La deuda técnica o el alcance reducido no es un problema per se; el problema es no tenerlos documentados. | | | | | |
| 1.2 | El equipo elaboró y puede presentar una **retrospectiva final de los cuatro trimestres**: qué aprendió el equipo sobre trabajo colaborativo en software, qué haría diferente si empezara de nuevo, y qué prácticas de los cuatro trimestres conservaría en un proyecto profesional real. | | | | | |
| 1.3 | Existe un **plan de implantación documentado** que describe las actividades de despliegue, la secuencia de ejecución, los responsables de cada actividad y los criterios de éxito de la implantación. No se acepta un despliegue improvisado sin planificación previa. | | | | | |

---

## DIMENSIÓN 2 — Artefactos Técnicos: sistema funcionando (35 %)

> En T4 el foco se desplaza del código fuente al producto de software. Se evalúa el sistema como un todo coherente: ¿funciona el flujo completo? ¿el backend maneja correctamente los errores? ¿la base de datos tiene integridad? El jurado puede y debe pedir demos en vivo de los flujos principales.

### Bloque 2A — Codificación final: cierre del software (RA 04 — resultado FINAL)

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2A.1 | El sistema completo **funciona de manera integrada**: frontend, backend(s), base de datos relacional y no relacional (si aplica) operan sin errores críticos en el entorno demostrado. El jurado puede solicitar la ejecución de cualquier caso de uso del sistema durante la sesión. | | | | | |
| 2A.2 | El backend implementa **manejo de errores robusto** en todos los niveles: errores de validación de datos de entrada, errores de base de datos, errores de autenticación y excepciones no esperadas producen respuestas HTTP con códigos correctos y mensajes descriptivos. No hay stack traces expuestos al cliente. | | | | | |
| 2A.3 | La base de datos tiene **integridad referencial completa**: las relaciones entre tablas están declaradas con claves foráneas, los constraints de unicidad e integridad están activos y funcionando. El equipo puede demostrar que la BD rechaza datos inconsistentes. | | | | | |
| 2A.4 | El sistema implementa un **modelo de roles y permisos funcional**: hay al menos dos roles diferenciados (por ejemplo, administrador y usuario regular) con permisos distintos, y el sistema los hace cumplir tanto en el frontend (ocultando opciones no permitidas) como en el backend (rechazando peticiones no autorizadas). | | | | | |
| 2A.5 | El código fuente del proyecto está **limpio y organizado para entrega**: no hay archivos de debug, logs temporales, branches de experimentos sin cerrar, ni código comentado masivamente que revele iteraciones sin limpiar. El repositorio refleja el estado de un producto terminado, no un borrador. | | | | | |

### Bloque 2B — Módulos electivos: IoT y/o Desarrollo Móvil (según orientación del equipo)

> Estos módulos son electivos dentro de la Cadena de Formación. Si el proyecto formativo incorporó alguno de estos elementos, el jurado los evalúa con los criterios siguientes. Si el proyecto no contempla IoT ni componente móvil, todos los ítems de este bloque se marcan como ➖.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 2B.1 | **IoT — si aplica:** El equipo puede demostrar la integración de al menos un dispositivo o sensor con el sistema: el dato del sensor llega al backend, se almacena en la base de datos y se visualiza en el frontend. La integración tiene justificación funcional en el contexto del proyecto. | | | | | |
| 2B.2 | **IoT — si aplica:** El equipo puede explicar el protocolo de comunicación utilizado (MQTT, HTTP, WebSocket), la frecuencia de envío de datos, y cómo el sistema maneja la pérdida de conectividad del dispositivo. | | | | | |
| 2B.3 | **Móvil — si aplica:** El equipo tiene una aplicación móvil funcional (React Native, Flutter, Android nativo u otro) que consume la API del sistema y permite realizar al menos los dos casos de uso más frecuentes del rol de usuario final desde un dispositivo móvil. | | | | | |
| 2B.4 | **Móvil — si aplica:** La aplicación móvil maneja correctamente la autenticación, el estado de conexión (qué pasa cuando no hay internet) y la experiencia de usuario en pantalla pequeña. No es simplemente la versión web envuelta en un WebView sin adaptación. | | | | | |

---

## DIMENSIÓN 3 — Implantación y Despliegue (20 %)

> Esta dimensión es completamente nueva en T4 de Cadena y no tiene equivalente en trimestres anteriores. La implantación de software es una competencia técnica y de gestión: requiere planear, ejecutar, verificar y documentar el proceso de poner el sistema en manos del cliente o usuario final. El jurado debe evaluar no solo si el sistema está desplegado, sino si el proceso de implantación fue planificado y documentado.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 3.1 | El sistema está **desplegado en un entorno accesible** diferente al entorno local de desarrollo: puede ser un servidor en la nube (Railway, Render, AWS, GCP, Azure, VPS), un servidor local del centro de formación, o un ambiente simulado de producción con Docker Compose. El jurado puede acceder al sistema desplegado durante la sesión. | | | | | |
| 3.2 | El despliegue usa **variables de entorno y configuración por ambiente**: la configuración del entorno de producción (cadenas de conexión, claves, puertos) está separada del código fuente y no está en el repositorio. Existe documentación de qué variables se necesitan para cada ambiente. | | | | | |
| 3.3 | El equipo elaboró y puede presentar un **manual de instalación técnica** que describe el proceso de despliegue paso a paso: requisitos de infraestructura (CPU, RAM, sistema operativo, puertos necesarios), instrucciones de instalación de dependencias, configuración de la base de datos, configuración de variables de entorno y verificación del sistema después de la instalación. Un técnico de sistemas externo al equipo debe poder seguir ese manual y desplegar el sistema. | | | | | |
| 3.4 | El equipo elaboró un **manual de usuario** que cubre al menos los tres procesos más importantes del sistema desde la perspectiva del usuario final: está escrito en lenguaje no técnico, incluye capturas de pantalla actualizadas del sistema real (no mockups), y tiene una sección de preguntas frecuentes o resolución de errores comunes. | | | | | |
| 3.5 | Existe una **estrategia de copias de seguridad documentada**: el equipo puede describir qué datos son críticos para el sistema, con qué frecuencia se deben respaldar, dónde se almacenan los respaldos (no en el mismo servidor que la aplicación) y cómo se ejecuta una restauración desde una copia de seguridad. Aunque la estrategia sea teórica para el proyecto formativo, debe ser técnicamente viable. | | | | | |
| 3.6 | Si el sistema tiene datos preexistentes que debían migrarse al nuevo esquema (desde un sistema anterior o desde archivos planos), existe un **script o proceso de migración documentado**: describe el origen de los datos, la transformación aplicada y la carga en el nuevo sistema. Si no hubo migración real, el equipo puede describir cómo la abordaría con un conjunto de datos hipotético del dominio del proyecto. | | | | | |

---

## DIMENSIÓN 4 — Documentación y Calidad (20 %)

> El aseguramiento de la calidad en T4 de Cadena no es solo "hacer pruebas". Es incorporar prácticas de calidad durante todo el proceso de construcción, verificar que el software cumple los estándares definidos y actuar sobre los resultados de esa verificación para mejorar el producto antes de la entrega. Los tres RA de la competencia de Aseguramiento de Calidad operan en secuencia: incorporar → verificar → mejorar.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 4.1 | El equipo tiene un **plan de aseguramiento de calidad** del proyecto que define: estándares de codificación aplicados, métricas de calidad monitoreadas (cobertura de pruebas, densidad de defectos, tiempo de respuesta de endpoints), herramientas de análisis estático configuradas, y proceso de revisión de código implementado. | | | | | |
| 4.2 | Existe un **informe final de verificación de calidad** que documenta: resultados de las pruebas automatizadas (unitarias e integración), resultados de las pruebas manuales de aceptación, defectos encontrados durante T4, defectos resueltos y defectos pendientes con su prioridad y justificación de por qué quedaron abiertos. | | | | | |
| 4.3 | El equipo puede demostrar **mejoras concretas realizadas como resultado de la verificación de calidad**: al menos dos ejemplos de código, arquitectura o proceso que fueron modificados después de una revisión o de una prueba fallida. No se trata de que el software sea perfecto; se trata de que el equipo respondió a los hallazgos de calidad con acciones reales. | | | | | |
| 4.4 | El código del proyecto tiene **cobertura de pruebas automatizadas** en el módulo de lógica de negocio más crítico: al menos 60 % de cobertura en ese módulo, demostrable con el reporte del framework de pruebas (`pytest --cov`, `jest --coverage` u equivalente). | | | | | |
| 4.5 | El repositorio del proyecto tiene configurado al menos un **pipeline de CI básico** (GitHub Actions, GitLab CI u otro): el pipeline ejecuta las pruebas automatizadas en cada push o pull request a la rama principal. El equipo puede mostrar el historial de ejecuciones del pipeline. Si no es posible CI completo, existe al menos un script que ejecuta todas las pruebas con un solo comando. | | | | | |
| 4.6 | La **documentación técnica del sistema está consolidada** para entrega: el repositorio tiene un `README.md` completo, la API tiene documentación accesible (Swagger, Postman collection o API.md), los manuales de instalación y de usuario están en el repositorio o en un enlace accesible, y los scripts de base de datos son ejecutables desde cero. | | | | | |

---

## DIMENSIÓN 5 — Trabajo en Equipo y Proceso (15 %)

> En el cierre de la etapa lectiva esta dimensión evalúa la madurez del equipo como unidad de trabajo: no solo si colaboraron, sino si construyeron un proceso de desarrollo que podría sostenerse en un entorno profesional real. Un equipo maduro no solo entrega el producto: puede explicar cómo lo construyó, qué aprendió y cómo mejoraría el proceso.

| # | Criterio de evaluación | ✅ | 🟡 | 🔴 | ➖ | Observaciones del jurado |
|---|------------------------|----|----|----|----|--------------------------|
| 5.1 | El **historial del repositorio** del trimestre muestra actividad distribuida entre todos los integrantes hasta la semana de sustentación. No hay picos de actividad artificial justo antes de la presentación ni integrantes con cero contribuciones. El log de commits es el registro de trabajo más honesto del equipo. | | | | | |
| 5.2 | El equipo realizó **revisiones de código** (code reviews) durante el trimestre: hay evidencia en los pull requests de comentarios de revisión, sugerencias implementadas o discusiones técnicas entre integrantes. La revisión de código no tiene que ser formal: puede verse en los comentarios de los PR del repositorio. | | | | | |
| 5.3 | Cada integrante puede **explicar el sistema completo** con suficiente profundidad para responder preguntas del jurado sobre cualquier capa: un integrante especializado en frontend puede explicar cómo funciona la autenticación en el backend; uno de backend puede describir la estructura de componentes del frontend. La especialización es válida; el desconocimiento total de otras capas no. | | | | | |
| 5.4 | El equipo puede presentar una **reflexión final sobre el proceso de desarrollo** de los cuatro trimestres: qué metodología usaron realmente (no qué metodología declararon usar), qué tan bien funcionó, cuáles fueron los momentos más difíciles técnicamente y de coordinación, y qué llevan como aprendizaje para su vida profesional. El jurado evalúa la calidad del análisis, no si el proceso fue perfecto. | | | | | |
| 5.5 | El equipo tiene clara la **hoja de ruta hacia la etapa productiva**: puede describir qué funcionalidades quedan pendientes, qué deuda técnica existe documentada, y qué necesitaría hacer en la etapa productiva para llevar el sistema a un estado de producción real ante un cliente externo. | | | | | |

---

## Resumen de evaluación

| Dimensión | Peso | Calificación del jurado | Notas |
|-----------|------|-------------------------|-------|
| D1 — Gestión del Proyecto | 10 % | | |
| D2 — Artefactos Técnicos | 35 % | | |
| D3 — Implantación y Despliegue | 20 % | | |
| D4 — Documentación y Calidad | 20 % | | |
| D5 — Trabajo en Equipo y Proceso | 15 % | | |

---

## Decisión del jurado

| Decisión | Seleccionar |
|----------|-------------|
| ☐ **Aprobado para etapa productiva** | El sistema y la documentación están en condiciones de ser presentados ante un cliente en la etapa productiva. |
| ☐ **Aprobado con condicionamientos** | Puede iniciar etapa productiva pero debe subsanar los ítems indicados en las primeras semanas. |
| ☐ **Aplazado — plan de mejora** | El grupo tiene hasta [fecha] para resolver los ítems críticos señalados antes de aprobar la etapa lectiva. |

### Condicionamientos o ajustes requeridos para ingreso a etapa productiva

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
|-------------------------------|-----------------|--------------|
| | | |
| | | |

---

## Retroalimentación cualitativa del jurado

| Jurado | Fortaleza principal del equipo al cierre de la etapa lectiva | Recomendación clave para la etapa productiva |
|--------|--------------------------------------------------------------|----------------------------------------------|
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

*Instrumento de evaluación formativa — Programa ADSO 228118 · Cadena de Formación · Trimestre IV (equivale a Trim VII del plan interno) — Cierre de etapa lectiva*
*Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital*