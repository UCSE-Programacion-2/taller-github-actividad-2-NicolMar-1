---
name: "Fase 3 — GitHub Pages"
about: "Publicar el CV web en GitHub Pages y verificar la URL pública."
title: "[Fase 3] Publicación en GitHub Pages"
labels: "fase-3, auto-seeded, tipo-tarea"
---

## Objetivo

**Desplegar** el sitio estático del CV en **GitHub Pages** y comprobar que la URL pública muestra el contenido correcto (incluidas hojas de estilo, scripts e imágenes).

## Prerrequisitos

- Código del CV integrado en `main` (o en la rama que indique el docente) tras merge del PR.
- Estructura de carpetas coherente con la opción de Pages que vayas a usar (raíz vs `docs/`).

## Checklist

- [ ] En GitHub: **Settings → Pages**.
- [ ] Elegir fuente: **Deploy from a branch** (u opción equivalente según la UI actual).
- [ ] Seleccionar **rama** (`main` / `gh-pages`) y **carpeta** (`/` o `/docs`).
- [ ] Guardar y esperar el despliegue (puede tardar varios minutos).
- [ ] Abrir la **URL publicada** y validar:
  - [ ] Página principal carga.
  - [ ] Estilos y scripts aplicados (no “HTML sin CSS”).
  - [ ] Navegación y enlaces internos funcionan.
- [ ] Si la URL usa subruta (`/nombre-repo/`), verificar **rutas relativas** en enlaces y recursos.

## Criterios de aceptación

1. El CV es accesible mediante una **URL pública** de GitHub Pages.
2. No hay errores evidentes de carga de recursos en la consola del navegador (salvo avisos menores no bloqueantes).
3. El enlace queda documentado donde lo solicite el docente (README, entrega en el aula, etc.).

## Solución de problemas (rápido)

| Síntoma | Qué revisar |
|---------|-------------|
| Página en blanco o sin estilo | Rutas a CSS/JS (`./` vs `/`), carpeta de Pages |
| 404 en el root | Nombre del repo, rama y carpeta en Settings → Pages |
| Imágenes rotas | Mayúsculas/minúsculas en nombres de archivo, rutas relativas |

## Referencias

- [GitHub Pages — documentación](https://docs.github.com/pages)
