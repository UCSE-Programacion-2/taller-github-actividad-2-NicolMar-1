---
name: "Fase 2 — Git y Pull Request"
about: "Ramas, commits convencionales, Push y Pull Request vinculado al issue."
title: "[Fase 2] Control de versiones y Pull Request"
labels: "fase-2, auto-seeded, tipo-tarea"
---

## Objetivo

Aplicar un flujo de trabajo **profesional**: trabajar en una **rama** dedicada (no directamente en `main`), realizar **commits** con [Conventional Commits](https://www.conventionalcommits.org/), subir los cambios y abrir un **Pull Request** que cierre el issue correspondiente.

## Recordatorio

**No integres el trabajo de esta fase con commits directos a `main`.** Integra vía PR revisado.

## Checklist

- [ ] Actualizar `main` localmente (`git pull`) antes de crear la rama.
- [ ] Crear una rama descriptiva, por ejemplo: `feature/cv-personalizado` o `feature/setup-estructura`.
- [ ] Realizar **commits atómicos** con mensajes del tipo `feat:`, `fix:`, `docs:`, `style:`, etc.
- [ ] `git push -u origin <tu-rama>`.
- [ ] Abrir **Pull Request** hacia `main`.
- [ ] En el cuerpo del PR incluir: **`Closes #N`** (siendo `N` el número del issue de la **Fase 1** o el que indique tu docente).
- [ ] Revisar el diff; resolver conflictos si los hay; pedir revisión si el curso lo exige.
- [ ] **Merge** a `main` tras la aprobación (o según criterio docente).

## Criterios de aceptación

1. Historial de commits **legible** y alineado con Conventional Commits.
2. Al menos un PR **fusionado** que cierre el issue con `Closes #…`.
3. La rama `main` refleja el estado estable post-merge.

## Notas

- Si trabajas solo, realiza una **autorrevisión** antes del merge: enlaces, ortografía y vista móvil.
- Si el repositorio usa protección de rama, sigue el flujo del aula (fork, revisores, etc.).

## Referencias

- [Conventional Commits](https://www.conventionalcommits.org/)
- [GitHub — Cerrar issues con palabras clave](https://docs.github.com/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
