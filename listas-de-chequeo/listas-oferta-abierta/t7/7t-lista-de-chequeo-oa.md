# Lista de Chequeo T7 — Oferta Abierta
## Implantación y Cierre de Etapa Lectiva · ADSO 228118 · SENA CGMLTI

> **RAP que se cierran:** Construcción RA01 (**FINAL**) · Implantación (RA01–04) · Aseguramiento de la Calidad (RA01–03). **Pregunta central:** ¿este sistema está listo para ser entregado y operado por alguien que no perteneció al equipo de desarrollo? Fundamento pedagógico completo: `1.justificación-metodologica.md` y `2.estructura-de-lista-propuesta.md`.

**Ficha:** _______  **Equipo:** ____________________  **Stack completo:** ____________________
**Repo URL:** ____________________  **URL desplegada:** ____________________
**Presentes/Total:** ___/___  **Fecha:** __________  **Jurado 1:** ____________  **Jurado 2:** ____________

**Escala:** ✅🟡🔴➖ (ver `3.escala-valoración-propuesta.md`) · **Ponderación:** D1 20 % · D2 25 % · D3 25 % · D4 20 % · D5 10 %

## Ítems

| # | Dim | Criterio | ✅ | 🟡 | 🔴 | ➖ | Obs. |
|---|---|---|---|---|---|---|---|
| 1 | D1 | Sistema funciona integrado y estable (todos los componentes); el jurado puede pedir cualquier caso de uso en vivo. | | | | | |
| 2 | D1 | Backlog final con % de historias completadas vs. SRS original y justificación de lo no alcanzado. | | | | | |
| 3 | D1 | Código limpio para entrega (sin debug/`console.log`); seguridad básica (hash de contraseñas, JWT con expiración, sin inyección SQL). | | | | | |
| 4 | D2 | Plan de implantación (infraestructura requerida, estrategia de migración/backup, plan de contingencia). | | | | | |
| 5 | D2 | Sistema desplegado en entorno distinto al local, accesible por URL; configuración separada por ambiente (`.env.example`). | | | | | |
| 6 | D2 | Despliegue reproducible desde cero siguiendo únicamente el manual de instalación (Docker o pasos documentados). | | | | | |
| 7 | D2 | Plan de capacitación de usuarios + sesión simulada; ≥5 pruebas de aceptación con cliente simulado registradas. | | | | | |
| 8 | D3 | Estándar de calidad adoptado (ISO 25010 / CMMI / PSP) con influencia real en decisiones; plan de aseguramiento de calidad. | | | | | |
| 9 | D3 | Pipeline de CI (o script único) ejecuta las pruebas automáticamente en cada push/PR. | | | | | |
| 10 | D3 | Informe de evaluación de calidad: al menos un RNF medido (rendimiento, usabilidad o seguridad OWASP) vs. su meta. | | | | | |
| 11 | D3 | Plan de mejora con ≥3 acciones; ≥2 mejoras implementadas a partir de la verificación de calidad. | | | | | |
| 12 | D4 | Manual técnico completo (arquitectura, stack, BD, API) suficiente para que un técnico externo mantenga el sistema. | | | | | |
| 13 | D4 | Manual de usuario con capturas reales del sistema desplegado + preguntas frecuentes. | | | | | |
| 14 | D4 | Plan de mantenimiento y soporte; repositorio organizado para entrega definitiva (sin archivos temporales). | | | | | |
| 15 | D4 | Documentación de API accesible (Swagger/Postman) para todos los servicios activos del sistema. | | | | | |
| 16 | D5 | Historial de commits distribuido y coherente hasta el cierre; cada integrante defiende el sistema completo. | | | | | |
| 17 | D5 | Hoja de ruta hacia la etapa productiva y reflexión crítica de los siete trimestres. | | | | | |

## Resumen y decisión del jurado

| Dim | Peso | Calificación | Notas |
|---|---|---|---|
| D1 Cierre de Construcción | 20 % | | |
| D2 Implantación y Despliegue | 25 % | | |
| D3 Aseguramiento de la Calidad | 25 % | | |
| D4 Documentación de Entrega | 20 % | | |
| D5 Proceso, Equipo y Reflexión Final | 10 % | | |

☐ **Aprobado para etapa productiva**  ☐ **Aprobado con condicionamientos**  ☐ **Aplazado — plan de mejora**

**Ajuste requerido para ingreso a etapa productiva:** _____________________________  **Plazo:** __________

**Retroalimentación —** Jurado 1 (logro más significativo): _____________________  Jurado 2 (recomendación clave): _____________________

## Firmas

Jurado 1: _______________  Jurado 2: _______________  Vocero del grupo (constancia de recibido): _______________

---
*Instrumento de evaluación formativa — ADSO 228118 · Oferta Abierta · T7 — Cierre de etapa lectiva · Revisión 2026 · CGMLTI — Regional Distrito Capital.*
