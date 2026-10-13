# .github

Configuración compartida de la organización `elingenierodedatos`.

- `profile/README.md`: perfil público de la organización.
- `PULL_REQUEST_TEMPLATE.md`: plantilla de PR por defecto para todos los repos.
- `.github/workflows/`: workflows reutilizables (pendiente).

## Convenciones de la organización

- Nombres de repo en minúsculas con guiones; los cursos llevan el prefijo `curso-`.
- Todo cambio entra a `main` por pull request con checks en verde.
- Commits con [Conventional Commits](https://www.conventionalcommits.org/es/).
- Ningún secreto en el código: se usan secretos de GitHub Actions y `wrangler secret`.
