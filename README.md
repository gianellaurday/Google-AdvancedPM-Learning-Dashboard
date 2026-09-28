# 📊 Advanced Project Management — Project Case Study

¡Bienvenida/o a mi caso de estudio aplicado de Project Management!

Este repositorio documenta la gestión del certificado **Advanced Project Management: Asana, Jira, Confluence, and AI** (Coursera) como si fuera un proyecto real, aplicando el ciclo de vida completo de Project Management: Iniciación, Planificación, Ejecución, Monitoreo y Cierre. El certificado funcionó como el "proyecto"; sus 9 cursos, como unidades de trabajo, y cada módulo, como una tarea.

A diferencia de mis casos de estudio anteriores, aquí trabajé con **dos herramientas de gestión en paralelo**: Jira para conservar el plan estimado y Asana para registrar el cronograma real. Además incorporé métricas ágiles (burndown y velocity) para comparar lo planeado contra lo ejecutado.

## 🎯 Objetivo del Proyecto

Gestionar el certificado como un proyecto completo, generando documentación formal, métricas reales de desempeño y evidencia práctica del uso de herramientas de Project Management, para responder preguntas como:

- ¿Cuál fue el progreso general del proyecto y cuándo cerró frente a lo planeado?
- ¿Cuántos cursos y módulos se completaron, y en cuánto tiempo real vs. estimado?
- ¿Qué patrón de cronograma mostré: en qué cursos me atrasé y en cuáles me adelanté?
- ¿Cuál fue mi velocity semanal?
- ¿Qué riesgos se identificaron y cómo se gestionaron?

## 🔄 Ciclo de Vida del Proyecto

El proyecto se gestionó bajo 5 fases formales:

| Fase | Estado |
|---|---|
| 01 · Iniciación | ✅ Completada |
| 02 · Planificación | ✅ Completada |
| 03 · Ejecución | ✅ Completada |
| 04 · Monitoreo | ✅ Completada |
| 05 · Cierre | ✅ Completada |

Cada fase generó documentación formal (Business Case, Project Charter, Matriz Poder-Interés, Matriz RACI, Objetivos SMART y OKRs, WBS, Cronograma, Risk Register), manteniendo trazabilidad entre la documentación y el trabajo operativo en Jira y Asana.

## 📑 Índice del Caso de Estudio

### 📚 Resumen Ejecutivo

Indicadores generales del proyecto:

- 9 de 9 cursos completados (100%)
- 41 módulos completados
- 82 horas estimadas vs. 47.62 horas reales (−34.38 h, −41.9%)
- Promedio de calificaciones: 98.18%
- Cierre el 27 de septiembre de 2026, 3 días antes de lo planeado (30 de septiembre)
- 6 riesgos identificados, todos cerrados o resueltos

### 🧩 Estructura de Trabajo (WBS)

El proyecto siguió una Work Breakdown Structure de 2 niveles: cada curso como unidad principal (9) y cada módulo como actividad (41). La misma estructura se replicó en Jira y en Asana para mantener trazabilidad entre la documentación formal y el trabajo operativo.

### 🗂️ Gestión con Jira y Asana

Cada herramienta cumplió un rol distinto:

**Jira — el plan estimado**
- Jerarquía Epic → Task (9 Epics y 41 Tasks) sobre un espacio Kanban.
- 48 dependencias "Blocks" (40 entre módulos y 8 entre cursos) que reflejan las predecesoras del cronograma.
- Fechas de fin según el cronograma estimado.

**Asana — el cronograma real**
- Proyecto con 9 secciones (una por curso) y 41 tareas con las fechas reales de inicio y fin.
- 40 dependencias Finish-to-Start entre módulos.
- Vista Timeline coloreada por curso mediante un campo personalizado.
- Decisión de diseño: usé secciones y tareas planas en lugar de subtareas, porque las subtareas de Asana no se muestran en la vista Timeline.

### 📈 Seguimiento del Proyecto (Dashboard Power BI)

El dashboard tiene dos páginas:

**Resumen**
- KPIs generales: cursos, módulos, horas estimadas, variación en horas, nota promedio y progreso.
- Horas estimadas vs. reales por curso.
- Riesgos por nivel.
- Notas por curso.
- Tabla resumen por curso.
- Días vs. plan por curso (positivo = terminé antes de lo planeado).

**Ágil**
- Burndown chart: módulos restantes reales vs. restante ideal, calculado a partir de las fechas de fin estimadas de cada módulo.
- Evolución de horas acumuladas: planificadas vs. reales.
- Velocity por sprint: 7, 13, 10 y 11 módulos, con un promedio de 10.25 módulos por sprint.
- Project Closure Report.

### ⭐ Rendimiento Académico

- Notas por curso y por módulo.
- Promedio general del certificado: 98.18% (rango por curso: 92.92% a 100%).

### ⚠️ Gestión de Riesgos

Se gestionaron 6 riesgos a lo largo del proyecto: 3 de planificación y ejecución (cronograma, disponibilidad personal y conectividad) y 3 identificados durante la ejecución, relacionados con el uso de herramientas y la calidad de los datos. Por nivel, 4 fueron bajos y 2 medios. Los 6 quedaron cerrados o resueltos sin comprometer el cumplimiento del alcance.

### 🧠 Decisiones de Gestión Destacadas

- **Velocity por semana, no por curso:** los cursos duraron entre 1 y 6 días, así que no cumplen la definición de un sprint. Usé semanas calendario (lunes a domingo) para que cada sprint tenga la misma duración y la métrica sea comparable.
- **Burndown ideal escalonado:** el "restante ideal" baja en módulos completos, según cuándo estaba planeado terminar cada uno, y no como una línea recta suavizada.
- **Cifras reconciliadas:** las horas de cada curso se validaron contra la suma de sus módulos, de modo que todo el reporte muestra los mismos totales.

## 🛠️ Tecnologías y Herramientas

- Microsoft Power BI Desktop
- Power Query · DAX
- Jira (Atlassian) — plan estimado con Kanban
- Asana — cronograma real con Timeline
- Microsoft Excel (fuente de datos privada)
- Advanced Project Management: Asana, Jira, Confluence, and AI (Coursera)

## 📸 Capturas del Proyecto

**Dashboard — Resumen (Power BI)**

![Dashboard Resumen](imagenes/dashboard-resumen.png)

*Imagen 1: Dashboard de seguimiento, página Resumen. Septiembre 28, 2026.*

**Dashboard — Ágil (Power BI)**

![Dashboard Ágil](imagenes/dashboard-agil.png)

*Imagen 2: Dashboard de seguimiento ágil, con burndown y velocity. Septiembre 28, 2026.*

**Cronograma y Dependencias (Jira)**

![Cronograma Jira](imagenes/jira-cronograma.png)

*Imagen 3: Vista de Cronograma con dependencias entre cursos y módulos. Septiembre 2026.*

**Tablero Kanban (Jira)**

![Tablero Kanban](imagenes/jira-kanban.png)

*Imagen 4: Tablero Por hacer → En curso → Listo. Septiembre 2026.*

**Cronograma Real (Asana)**

![Timeline Asana](imagenes/asana-timeline.png)

*Imagen 5: Vista Timeline con las fechas reales, coloreada por curso. Septiembre 2026.*

**Gestión de Riesgos**

![Risk Register](imagenes/risk-register.png)

*Imagen 6: Risk Register — 6 riesgos identificados y cerrados o resueltos. Septiembre 2026.*

## ✍️ Sobre este repositorio

Este proyecto representa una aplicación práctica de los conocimientos adquiridos en Project Management y en el uso de Jira y Asana, integrando planificación, ejecución, monitoreo, gestión de riesgos y documentación formal — simulando un escenario real de gestión de proyectos.

Las capturas y documentación compartidas corresponden a un caso de estudio personal. El archivo de datos utilizado para alimentar el dashboard, así como la documentación formal completa del proyecto, no se publican en su totalidad, ya que forman parte de mi registro privado de aprendizaje.

Desarrollado por Gianella Urday Ibarra como parte de su formación profesional.
