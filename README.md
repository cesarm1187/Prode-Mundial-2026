# Prode Mundial 2026 - PWA interna

Archivos incluidos:
- `index.html`: la app.
- `manifest.json`: datos para instalarla como app.
- `service-worker.js`: cache básico/offline.
- `icons/`: íconos de instalación.

## Instalación en celular
- Android/Chrome: abrir el link > menú > **Agregar a pantalla principal** o botón instalar.
- iPhone/Safari: compartir > **Agregar a inicio**.

## Importante
Esta versión guarda usuarios, apuestas y resultados en el navegador usando `localStorage`.
Sirve para uso interno/simple o pruebas. Si querés que todos los usuarios compartan la misma base en tiempo real desde distintos celulares, el próximo paso es conectar Firebase/Supabase o un backend propio.
