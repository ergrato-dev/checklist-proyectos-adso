# Guía de Contribución

Gracias por querer mejorar este instrumento. Estas listas de chequeo sirven a instructores y aprendices de ADSO en toda la Regional Distrito Capital — cada mejora tiene impacto directo en el aula.

---

## ¿Qué tipo de contribuciones se aceptan?

| Tipo                      | Ejemplos                                                                |
| ------------------------- | ----------------------------------------------------------------------- |
| **Corrección**            | Errores ortográficos, criterios ambiguos, ítem duplicado                |
| **Mejora de criterios**   | Reformular un ítem para que sea más verificable o alcanzable            |
| **Nueva lista**           | Lista para un trimestre o modalidad aún no cubierta                     |
| **Alineación curricular** | Actualizar ítems cuando cambie el programa ADSO o el Proyecto Formativo |
| **Traducción**            | Adaptar las listas para otra lengua o región                            |

## Lo que NO se acepta

- Cambios que bajen el nivel de exigencia sin justificación pedagógica.
- Ítems subjetivos que no puedan verificarse con evidencia concreta.
- Modificaciones que rompan la progresión trimestre a trimestre.

---

## Proceso paso a paso

### 1. Abre un issue primero

Antes de abrir un PR, describe el problema o mejora en un issue usando la plantilla correspondiente. Esto evita trabajo duplicado y permite discutir el enfoque.

### 2. Haz un fork y crea tu rama

```bash
git clone git@github.com:TU_USUARIO/checklist-proyectos-adso.git
cd checklist-proyectos-adso
git checkout -b fix/descripcion-corta   # o feat/, docs/, etc.
```

Convención de ramas:

- `fix/` — correcciones
- `feat/` — listas o secciones nuevas
- `docs/` — mejoras a README, guías, metadocumentación
- `refactor/` — reorganización sin cambio de contenido

### 3. Edita siguiendo los criterios de diseño

Cada ítem debe ser:

- **Verificable** — el jurado puede comprobarlo en el momento.
- **Alcanzable** — el trimestre actual lo permite; no pida lo que aún no se enseñó.
- **Progresivo** — construye sobre el trimestre anterior.
- **Orientado a evidencia** — pide artefactos concretos, no impresiones.
- **Cronometrable** — quien lo escribe puede estimar en segundos/minutos cuánto toma verificarlo en vivo. Esa estimación determina su tier: 🎤 **verificación viva** (demo, explicación oral, pregunta directa — 1 a 1.5 min) o 👁 **inspección rápida** (vistazo binario existe/no existe — 20 a 30 seg). Ver el modelo completo en [6.tiempos-de-sesion.md](6.tiempos-de-sesion.md).

### Límite de ítems por lista

Cada lista de chequeo tiene una sesión de 20 minutos para todo: contexto, demo, preguntas, inspección de evidencia, retroalimentación, decisión y firmas. Objetivo: **máximo 32-34 ítems por lista**, con 8-10 de ellos en tier 🎤. Si una propuesta de ítem nuevo excede ese límite, la alternativa no es alargar la sesión: es fusionar el ítem con otro del mismo bloque que un jurado verificaría con la misma evidencia o la misma pregunta, o reclasificarlo a 👁 si su verificación real es más rápida de lo que parece. T1 y CF-T1 (sesión de aprobación de ideas) no están sujetas a este límite por ser estructuralmente distintas — ver justificación en `6.tiempos-de-sesion.md`.

### 4. Commits con Conventional Commits

```
tipo(alcance): descripción corta en imperativo

- detalle 1
- detalle 2

Impacto: ...
```

Tipos válidos: `fix`, `feat`, `docs`, `refactor`, `chore`.

### 5. Abre el Pull Request

Usa la plantilla de PR. El mantenedor revisará en un plazo de 7 días hábiles.

---

## Estilo de escritura

- Español neutro (sin regionalismos excluyentes).
- Segunda persona plural para dirigirse a los aprendices (_"el equipo presenta"_, _"los integrantes demuestran"_).
- Sin gerundios al inicio de ítem (_"Presenta"_ no _"Presentando"_).
- Máximo 120 caracteres por ítem en la lista de chequeo.

---

## Código de Conducta

Este proyecto aplica el [Contributor Covenant](CODE_OF_CONDUCT.md). Al contribuir, aceptas sus términos.
