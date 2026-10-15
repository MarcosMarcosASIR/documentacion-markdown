# Detalles técnicos

## Organización del proyecto

Este documento amplía la información del archivo principal `markdown.md`.

### Estructura de carpetas

- `markdown.md`: documentación principal.
- `docs/detalles.md`: información complementaria.
- `assets/mi-imagen.png`: imagen almacenada localmente.

### Rutas relativas

Una ruta relativa indica dónde se encuentra un archivo respecto al documento actual.

Desde `markdown.md` utilizamos:

```markdown
[Consultar detalles](docs/detalles.md)
```

Desde este documento, la ruta hacia la imagen sería:

```text
../assets/mi-imagen.png
```

### Recomendaciones

1. Mantener nombres de archivos claros.
2. Comprobar los enlaces antes de publicar.
3. Subir todos los recursos al repositorio.
4. Verificar la visualización en GitHub.
