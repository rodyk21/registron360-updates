# registron360-updates

Repositorio de actualizaciones de RGTN360.

Uso recomendado:

1. Crear una Release en este repo.
2. Subir la APK como asset de la release.
3. Actualizar `version.json` con:
   - `version`
   - `mensaje`
   - `url`
   - `obligatoria`

Ejemplo:

```json
{
  "version": "1.0.6",
  "mensaje": "Mejoras en auto-registro, backups y modo oscuro.",
  "url": "https://github.com/rodyk21/registron360-updates/releases/download/v1.0.6/RGTN360.apk",
  "obligatoria": false
}
```

Mientras no haya una release nueva, `version.json` debe quedarse alineado con la versión actual publicada para no disparar avisos falsos.
