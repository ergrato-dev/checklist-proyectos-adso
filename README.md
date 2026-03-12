<img src="_assets/banner.svg" alt="Listas de Chequeo · ADSO 228118 · SENA" width="100%"/>

# Listas de Chequeo — Seguimiento de Proyectos ADSO

Instrumento de evaluación estandarizado para las sesiones de seguimiento de proyectos formativos del programa **Análisis y Desarrollo de Software (ADSO, cód. 228118)** — SENA Regional Distrito Capital, Centro de Gestión de Mercados, Logística y Tecnologías de la Información.

---

## Problema que resuelve

Sin un instrumento común, cada instructor del jurado evalúa con criterios distintos, lo que genera inequidad entre grupos, confusión en los aprendices y dificultad para identificar rezagos a tiempo. Este repositorio estandariza y objetiva ese proceso.

---

## Referentes

Las listas están ancladas a tres referentes simultáneos:

1. **Programa de Formación ADSO (228118):** competencias y Resultados de Aprendizaje (RAP) por trimestre.
2. **Proyecto Formativo:** fases del ciclo de vida del software y entregables esperados en cada fase.
3. **Estándares de la industria:** IEEE, ISO/IEC 25010, CMMI, Scrum/Kanban.

---

## Estructura de cada lista

Cinco dimensiones con distinto peso según el momento formativo:

| Dimensión                           | Foco                                                   |
| ----------------------------------- | ------------------------------------------------------ |
| **1 - Gestión del Proyecto**        | Backlog, actas, roles, herramientas de seguimiento     |
| **2 - Artefactos Técnicos**         | Entregables específicos del RAP del trimestre          |
| **3 - Documentación**               | Relevancia, estándares y control de versiones          |
| **4 - Trabajo en Equipo y Proceso** | Commits distribuidos, tareas equitativas, sustentación |
| **5 - Calidad y Mejores Prácticas** | Convenciones, revisión entre pares, pruebas            |

### Escala de valoración

| Nivel         | Símbolo | Descripción                                    |
| ------------- | ------- | ---------------------------------------------- |
| Excelente     | ✅      | Cumple completamente y con evidencia sólida    |
| Satisfactorio | 🟡      | Cumple parcialmente o con evidencia incompleta |
| Insuficiente  | 🔴      | No cumple o la evidencia es muy débil          |
| No Aplica     | ➖      | El ítem no corresponde a este equipo/proyecto  |

### Ponderación por etapa

| Dimensión                   | T1–T3 | T4–T6 | T7  |
| --------------------------- | ----- | ----- | --- |
| Gestión del Proyecto        | 20%   | 20%   | 15% |
| Artefactos Técnicos         | 40%   | 40%   | 35% |
| Documentación               | 20%   | 15%   | 25% |
| Trabajo en Equipo           | 10%   | 10%   | 10% |
| Calidad y Mejores Prácticas | 10%   | 15%   | 15% |

---

## Organización del repositorio

```
README.md
.gitignore
0.problema.md                        ← contexto y justificación del instrumento
1.justificación-metodologica.md
2.estructura-de-lista-propuesta.md
3.escala-valoración-propuesta.md
4.pros-cons.md
5.lineas-rojas-ideas-de-proyecto.md

_docs/
├── listas-oferta-abierta/           ← grupos con modalidad de oferta abierta
│   ├── t1/
│   ├── t2/
│   ├── t3/
│   ├── t4/
│   ├── t5/
│   ├── t6/
│   └── t7/
└── listas-cadena-formacion/         ← grupos en cadena de formación
    ├── t4 - 2t3t/
    ├── t5 - 4t5t/
    ├── t6/
    └── t7/
```

Cada carpeta de trimestre contiene uno o más archivos `*-lista-de-chequeo.md` listos para diligenciar por sesión.

---

## Uso

1. Identificar el trimestre del grupo y su modalidad (Oferta Abierta / Cadena de Formación).
2. Abrir la lista correspondiente en `_docs/`.
3. Completar los **Datos de la sesión** (ficha, integrantes, jurado, fecha).
4. Valorar cada ítem con la escala ✅ 🟡 🔴 ➖.
5. Registrar observaciones y la decisión final del jurado.
