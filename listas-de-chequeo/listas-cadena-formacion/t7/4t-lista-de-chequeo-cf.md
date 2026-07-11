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
>
> - RA 01: Planear actividades de construcción del software — **resultado FINAL**
> - RA 04: Codificar el software de acuerdo con el diseño — **resultado FINAL**
>
> **Competencia Implantación del Software:**
>
> - RA 01: Planear actividades de implantación del software de acuerdo con las condiciones del sistema
> - RA 02: Desplegar el software de acuerdo con la arquitectura y las políticas establecidas
> - RA 03: Documentar el proceso de implantación siguiendo estándares de calidad
> - RA 04: Implantar el software de acuerdo con los niveles de servicio establecidos con el cliente
>
> **Competencia Aseguramiento de la Calidad del Software:**
>
> - RA 01: Incorporar actividades de aseguramiento de la calidad de acuerdo con estándares de la industria
> - RA 02: Verificar la calidad del software de acuerdo con las prácticas de los procesos de desarrollo
> - RA 03: Realizar actividades de mejora de la calidad a partir de los resultados de la verificación
>
> **Módulos técnicos activos:** Asesoría de Desarrollo / Codificación final · Implantación, despliegue y elaboración de manuales técnicos y de usuario · Migración y copias de seguridad · Buenas prácticas de calidad de software · Fundamentos IoT (módulo electivo) · Desarrollo Móvil (módulo electivo)
>
> **Propósito del trimestre:** Este es el trimestre de cierre lectivo de la Cadena de Formación. No se trata solo de terminar el código: se trata de entregar un sistema que pueda vivir en producción real o en el entorno del cliente simulado. El equipo debe demostrar que el software está desplegado (no solo corriendo localmente), que tiene manuales que permiten a un usuario final operarlo sin asistencia del equipo de desarrollo, que hay una estrategia de respaldo y migración de datos, y que el proceso de construcción siguió estándares de calidad verificables. Es la primera vez en el programa donde el jurado evalúa el software como producto terminado, no como trabajo en progreso. La pregunta central del T4 de Cadena es: **¿este sistema está listo para ser usado por alguien que no pertenece al equipo de desarrollo?**

---

## Datos de la sesión

| Campo                                  | Valor |
| --------------------------------------- | ----- |
| Número de Ficha                        |       |
| Nombre del grupo de proyecto           |       |
| Nombre del sistema / software          |       |
| Stack tecnológico completo             |       |
| URL del repositorio                    |       |
| URL del sistema desplegado (si aplica) |       |
| Integrantes presentes                  |       |
| Integrantes ausentes                   |       |
| Fecha de sustentación                  |       |
| Jurado 1                               |       |
| Jurado 2                               |       |

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

| Dimensión                                      | Peso |
| ------------------------------------------------ | ---- |
| D1 — Gestión del Proyecto                      | 10 % |
| D2 — Artefactos Técnicos (sistema funcionando) | 35 % |
| D3 — Implantación y Despliegue                 | 20 % |
| D4 — Documentación y Calidad                   | 20 % |
| D5 — Trabajo en Equipo y Proceso               | 15 % |

> **Nota sobre la ponderación:** En T4 de Cadena la distribución cambia de manera significativa respecto a trimestres anteriores, porque las competencias de Implantación y de Aseguramiento de Calidad son nuevas y tienen el mismo peso que los artefactos técnicos. No se puede tener un sistema excelente en código pero sin desplegar ni documentar: ambas dimensiones son igualmente obligatorias para cerrar la etapa lectiva. La gestión baja a 10 % porque a estas alturas del programa debe ser completamente autónoma y no requiere el mismo nivel de andamiaje evaluativo que en T1.

---

## Distribución del tiempo de sesión (20 min)

| Bloque | Minutos |
| --- | --- |
| Contexto y datos de sesión | 1 |
| 🎤 Demo en vivo + preguntas (11 ítems 🎤 base, bloque serial) | 14 |
| 👁 Inspección rápida (manuales, plan de calidad, evidencia de repo) — en paralelo, Jurado 2 | — |
| Retroalimentación, decisión y firmas | 4 |
| **Total** | **19-20** |

> Si el equipo presenta módulo electivo (IoT y/o Móvil, Bloque 2B), sus ítems 🎤 se suman al bloque de demo con cargo al minuto de holgura; si no presenta ninguno, esos ítems se marcan ➖ y no consumen tiempo.

---

## DIMENSIÓN 1 — Gestión del Proyecto (10 %)

> En el último trimestre lectivo la gestión se evalúa más como cierre que como proceso: ¿el equipo puede hacer un balance honesto de lo que construyó, lo que no alcanzó y por qué? Esa capacidad de análisis retrospectivo es más valiosa pedagógicamente que un tablero perfectamente ordenado el día de la sustentación.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                    | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 1.1 | 🎤 El equipo presenta el **estado final del backlog del proyecto**: porcentaje de historias completadas respecto al SRS original, con justificación documentada para las historias fuera de alcance. La deuda técnica o el alcance reducido no es un problema per se; el problema es no tenerlos documentados. |     |     |     |     |                          |
| 1.2 | 🎤 El equipo elaboró y presenta una **retrospectiva final de los cuatro trimestres**: qué aprendió sobre trabajo colaborativo en software, qué haría diferente, y qué prácticas conservaría en un proyecto profesional real.                                                                                  |     |     |     |     |                          |
| 1.3 | 👁 Existe un **plan de implantación documentado**: actividades de despliegue, secuencia, responsables y criterios de éxito. No se acepta un despliegue improvisado sin planificación previa.                                                                                                                    |     |     |     |     |                          |

---

## DIMENSIÓN 2 — Artefactos Técnicos: sistema funcionando (35 %)

> En T4 el foco se desplaza del código fuente al producto de software. Se evalúa el sistema como un todo coherente: ¿funciona el flujo completo? ¿el backend maneja correctamente los errores? ¿la base de datos tiene integridad? El jurado puede y debe pedir demos en vivo de los flujos principales.

### Bloque 2A — Codificación final: cierre del software (RA 04 — resultado FINAL)

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                          | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 2A.1 | 🎤 El sistema completo **funciona de manera integrada**: frontend, backend(s), base de datos relacional y no relacional (si aplica) operan sin errores críticos. El jurado puede solicitar la ejecución de cualquier caso de uso durante la sesión.                                           |     |     |     |     |                          |
| 2A.2 | 🎤 El backend implementa **manejo de errores robusto** en todos los niveles (validación, BD, autenticación, excepciones no esperadas), y la base de datos tiene **integridad referencial completa** (FK, constraints activos); el equipo demuestra que la BD rechaza datos inconsistentes.            |     |     |     |     |                          |
| 2A.3 | 🎤 El sistema implementa un **modelo de roles y permisos funcional**: al menos dos roles diferenciados con permisos distintos, aplicados tanto en frontend (ocultando opciones) como en backend (rechazando peticiones no autorizadas). Demo en vivo. |     |     |     |     |                          |
| 2A.4 | 👁 El código fuente está **limpio y organizado para entrega**: sin archivos de debug, logs temporales, branches de experimentos sin cerrar, ni código comentado masivamente.                         |     |     |     |     |                          |

### Bloque 2B — Módulos electivos: IoT y/o Desarrollo Móvil (según orientación del equipo)

> Estos módulos son electivos dentro de la Cadena de Formación. Si el proyecto formativo incorporó alguno de estos elementos, el jurado los evalúa con los criterios siguientes. Si el proyecto no contempla IoT ni componente móvil, todos los ítems de este bloque se marcan como ➖.

| #    | Criterio de evaluación                                                                                                                                                                                                                                                                                                                               | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 2B.1 | 🎤 **IoT — si aplica:** el equipo demuestra la integración de al menos un dispositivo o sensor con el sistema: el dato llega al backend, se almacena y se visualiza en el frontend, con justificación funcional en el contexto del proyecto.                                                      |     |     |     |     |                          |
| 2B.2 | 🎤 **IoT — si aplica:** el equipo explica el protocolo de comunicación (MQTT, HTTP, WebSocket), la frecuencia de envío y cómo el sistema maneja la pérdida de conectividad del dispositivo.                                                                                                                                  |     |     |     |     |                          |
| 2B.3 | 🎤 **Móvil — si aplica:** la app funcional con React Native (desarrollo híbrido) consume la API del sistema y permite realizar los dos casos de uso más frecuentes del usuario final desde un dispositivo móvil. No se aceptan implementaciones nativas (Android-Kotlin, iOS-Swift). |     |     |     |     |                          |
| 2B.4 | 🎤 **Móvil — si aplica:** la app maneja correctamente la autenticación, el estado de conexión (sin internet) y la experiencia en pantalla pequeña. No es la versión web envuelta en un WebView sin adaptación.                                                                                   |     |     |     |     |                          |

---

## DIMENSIÓN 3 — Implantación y Despliegue (20 %)

> Esta dimensión es completamente nueva en T4 de Cadena y no tiene equivalente en trimestres anteriores. La implantación de software es una competencia técnica y de gestión: requiere planear, ejecutar, verificar y documentar el proceso de poner el sistema en manos del cliente o usuario final. El jurado debe evaluar no solo si el sistema está desplegado, sino si el proceso de implantación fue planificado y documentado.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 3.1 | 🎤 El sistema está **desplegado en un entorno accesible** diferente al local (nube, servidor del centro, o Docker Compose), con **configuración separada por ambiente** (variables sensibles fuera del repositorio). El jurado accede al sistema desplegado durante la sesión.                                                                                                                                         |     |     |     |     |                          |
| 3.2 | 👁 El equipo elaboró un **manual de instalación técnica** paso a paso: requisitos de infraestructura, instalación de dependencias, configuración de BD y de variables de entorno, y verificación posterior. Un técnico externo debe poder seguirlo y desplegar el sistema. |     |     |     |     |                          |
| 3.3 | 👁 El equipo elaboró un **manual de usuario** que cubre al menos los tres procesos más importantes desde la perspectiva del usuario final, en lenguaje no técnico, con capturas del sistema real y una sección de preguntas frecuentes.                                                                                                                                          |     |     |     |     |                          |
| 3.4 | 👁 Existe una **estrategia de copias de seguridad documentada** (datos críticos, frecuencia, almacenamiento separado, restauración) y, si el sistema tenía datos preexistentes que migrar, un **proceso de migración documentado** (o el equipo describe cómo lo abordaría con un conjunto de datos hipotético).                                                             |     |     |     |     |                          |

---

## DIMENSIÓN 4 — Documentación y Calidad (20 %)

> El aseguramiento de la calidad en T4 de Cadena no es solo "hacer pruebas". Es incorporar prácticas de calidad durante todo el proceso de construcción, verificar que el software cumple los estándares definidos y actuar sobre los resultados de esa verificación para mejorar el producto antes de la entrega. Los tres RA de la competencia de Aseguramiento de Calidad operan en secuencia: incorporar → verificar → mejorar.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                              | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- | --- | --- | --- | ------------------------ |
| 4.1 | 👁 El equipo tiene un **plan de aseguramiento de calidad** (estándares de codificación, métricas monitoreadas, herramientas de análisis estático, revisión de código) y un **pipeline de CI** (o script único) que ejecuta las pruebas automatizadas, con historial de ejecuciones demostrable.                                                               |     |     |     |     |                          |
| 4.2 | 👁 Existe un **informe final de verificación de calidad**: resultados de pruebas automatizadas y manuales, defectos encontrados en T4, resueltos y pendientes con prioridad y justificación.                                                                 |     |     |     |     |                          |
| 4.3 | 🎤 El equipo demuestra **mejoras concretas realizadas como resultado de la verificación de calidad**: al menos dos ejemplos (código, arquitectura o proceso) modificados tras una revisión o prueba fallida.                           |     |     |     |     |                          |
| 4.4 | 🎤 El código tiene **cobertura de pruebas automatizadas** de al menos 60 % en el módulo de lógica de negocio más crítico, demostrable con el reporte del framework de pruebas (`pytest --cov`, `jest --coverage` u equivalente).                                                                                                                                 |     |     |     |     |                          |
| 4.5 | 👁 La **documentación técnica del sistema está consolidada** para entrega: README completo, API documentada, manuales de instalación y usuario en el repositorio, scripts de BD ejecutables desde cero.                                            |     |     |     |     |                          |

---

## DIMENSIÓN 5 — Trabajo en Equipo y Proceso (15 %)

> En el cierre de la etapa lectiva esta dimensión evalúa la madurez del equipo como unidad de trabajo: no solo si colaboraron, sino si construyeron un proceso de desarrollo que podría sostenerse en un entorno profesional real. Un equipo maduro no solo entrega el producto: puede explicar cómo lo construyó, qué aprendió y cómo mejoraría el proceso.

| #   | Criterio de evaluación                                                                                                                                                                                                                                                                                                                                                                                             | ✅  | 🟡  | 🔴  | ➖  | Observaciones del jurado |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | --- | --- | --- | ------------------------ |
| 5.1 | 👁 El **historial del repositorio** muestra actividad distribuida entre todos los integrantes hasta la semana de sustentación, y hay evidencia de **revisiones de código** (comentarios o sugerencias en pull requests) durante el trimestre.                                                                                                                                                          |     |     |     |     |                          |
| 5.2 | 🎤 Cada integrante puede **explicar el sistema completo** con suficiente profundidad para responder preguntas del jurado sobre cualquier capa. La especialización es válida; el desconocimiento total de otras capas no.               |     |     |     |     |                          |
| 5.3 | 🎤 El equipo presenta una **reflexión final sobre el proceso de desarrollo** de los cuatro trimestres: qué metodología usaron realmente, qué tan bien funcionó, los momentos más difíciles, y qué llevan como aprendizaje para su vida profesional. |     |     |     |     |                          |
| 5.4 | 🎤 El equipo tiene clara la **hoja de ruta hacia la etapa productiva**: funcionalidades pendientes, deuda técnica documentada, y qué necesitaría hacer para llevar el sistema a producción real ante un cliente externo.                                                                                                                                    |     |     |     |     |                          |

---

## Resumen de evaluación

| Dimensión                        | Peso | Calificación del jurado | Notas |
| --------------------------------- | ---- | ----------------------- | ----- |
| D1 — Gestión del Proyecto        | 10 % |                         |       |
| D2 — Artefactos Técnicos         | 35 % |                         |       |
| D3 — Implantación y Despliegue   | 20 % |                         |       |
| D4 — Documentación y Calidad     | 20 % |                         |       |
| D5 — Trabajo en Equipo y Proceso | 15 % |                         |       |

---

## Decisión del jurado

| Decisión                             | Seleccionar                                                                                                   |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| ☐ **Aprobado para etapa productiva** | El sistema y la documentación están en condiciones de ser presentados ante un cliente en la etapa productiva. |
| ☐ **Aprobado con condicionamientos** | Puede iniciar etapa productiva pero debe subsanar los ítems indicados en las primeras semanas.                |
| ☐ **Aplazado — plan de mejora**      | El grupo tiene hasta [fecha] para resolver los ítems críticos señalados antes de aprobar la etapa lectiva.    |

### Condicionamientos o ajustes requeridos para ingreso a etapa productiva

| Artefacto / Dimensión afectada | Ajuste requerido | Fecha límite |
| ------------------------------ | ---------------- | ------------ |
|                                |                  |              |
|                                |                  |              |

---

## Retroalimentación cualitativa del jurado

| Jurado   | Fortaleza principal del equipo al cierre de la etapa lectiva | Recomendación clave para la etapa productiva |
| -------- | ------------------------------------------------------------ | --------------------------------------------- |
| Jurado 1 |                                                              |                                              |
| Jurado 2 |                                                              |                                              |

---

## Firmas

| Rol                                                    | Nombre completo | Firma |
| ------------------------------------------------------ | --------------- | ----- |
| Jurado 1                                               |                 |       |
| Jurado 2                                               |                 |       |
| Vocero del grupo (constancia de recibido del feedback) |                 |       |

---

_Instrumento de evaluación formativa — Programa ADSO 228118 · Cadena de Formación · Trimestre IV (equivale a Trim VII del plan interno) — Cierre de etapa lectiva_
_Revisión: 2025 · Centro de Gestión de Mercados, Logística y Tecnologías de la Información — Regional Distrito Capital_
