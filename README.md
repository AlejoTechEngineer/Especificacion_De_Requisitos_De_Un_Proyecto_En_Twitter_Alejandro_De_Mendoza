<div align="center">

# Especificación de Requisitos — Proyecto Twitter Features

![Scrum](https://img.shields.io/badge/SCRUM-Agile-FF6B35?style=for-the-badge)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Requirements](https://img.shields.io/badge/Requisitos-User%20Stories-6A0DAD?style=for-the-badge)

> Especificación completa de requisitos para un proyecto de nuevas funcionalidades en Twitter/X con historias de usuario, épicas en Jira y burn-down charts.

## Descripción

</div>

---

Especificación de requisitos de software aplicando metodología **SCRUM**: definición de épicas, historias de usuario con criterios de aceptación (formato GIVEN/WHEN/THEN), estimación por puntos de historia, backlog priorizado en **Jira** y gráficas de burn-down de 3 y 19 días para seguimiento del sprint.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `*.xlsx` | Plantilla con historias de usuario, épicas y puntos |
| `burndown_3dias.html` | Gráfica burn-down sprint corto (3 días) |
| `burndown_19dias.html` | Gráfica burn-down sprint completo (19 días) |
| `Enlace al Proyecto de Jira.*` | Enlace al tablero Jira del proyecto |

## Artefactos SCRUM generados

- **Épicas** definidas por dominio funcional (perfil, feed, seguridad, analytics)
- **Historias de usuario** con criterios de aceptación GIVEN/WHEN/THEN
- **Story points** estimados por complejidad relativa
- **Burn-down charts** interactivos para seguimiento de velocidad del equipo

## Contexto académico

**Asignatura:** Ingeniería de Software · **Institución:** Ingeniería Informática
**Autor:** Alejandro De Mendoza — Ingeniero Informático · Especialista Ingeniería de Software

---

## Arquitectura

```mermaid
flowchart TD
    A[Definicion de epicas - Jira Board] --> B[Historias de usuario - GIVEN / WHEN / THEN]
    B --> C[Estimacion por Story Points]
    C --> D[Backlog priorizado - Plantilla XLSX]
    D --> E[Inicio de Sprint]
    E --> F{Seguimiento}
    F --> G[burndown_3dias.html - Sprint corto 3 dias]
    F --> H[burndown_19dias.html - Sprint completo 19 dias]
    G & H --> I{Sprint completado?}
    I -- No --> E
    I -- Si --> J[Revision y Retrospectiva]
    J --> K[Enlace al Proyecto de Jira]
```

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
