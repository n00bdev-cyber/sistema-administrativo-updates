# Sistema Administrativo — canal de actualizaciones

Este repositorio público contiene únicamente el manifiesto del canal estable y,
cuando exista un certificado de firma de código, los instaladores firmados de
Sistema Administrativo.

- No contiene código fuente ni datos comerciales.
- No contiene certificados, claves privadas, tokens ni contraseñas.
- `stable.json` mantiene las descargas deshabilitadas hasta que haya un
  instalador Authenticode válido.
- Las releases publicadas son inmutables.
- El cliente verifica versión, ruta exacta, tamaño, SHA-256 y Authenticode; no
  ejecuta automáticamente los archivos descargados.

Repositorio de distribución: `n00bdev-cyber/sistema-administrativo-updates`.
