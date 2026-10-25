# Cómo contribuir a mi-primer-repo

## Ramas

- `main` siempre tiene código que funciona. Nunca se sube directamente.
- Cada tarea va en su propia rama: `feature/nombre-de-la-tarea`.
- Los arreglos urgentes van en `hotfix/descripcion`.

## Mensajes de commit

- Un commit, un cambio. Usa el formato Conventional Commits:
  - `feat: añade la página de servicios`
  - `fix: corrige el enlace del menú`
  - `docs: actualiza el README`
- En imperativo y en una línea. Sin punto final.

## Pull requests

- Enlaza la incidencia que resuelve: `closes #5` en la descripción.
- Otro miembro del equipo revisa y aprueba antes de fusionar.
- Tras fusionar, borra la rama.

## Lo que nunca se sube

- Contraseñas, tokens ni claves privadas.
- Archivos de configuración personal (`.env`, `.vscode/`, `.idea/`).