# Firme · Prototipo de apoyo a la captura en flagrancia

Prototipo navegable con datos ficticios. Policía Nacional de Colombia.

- `index.html` — Demo guiada del caso 0421 (vista del patrullero, con guía del recorrido).
- `admin.html` — Centro de mando para el alto mando.

Los dos archivos son autónomos: no requieren instalación ni compilación. El Centro de mando lee el avance de la demo desde el almacenamiento local del navegador, así que se sincronizan cuando se abren en el mismo navegador y dominio.

## Despliegue en Vercel

1. Suba el contenido de esta carpeta a un repositorio de GitHub.
2. En Vercel: **Add New → Project**, importe el repositorio.
3. Framework Preset: **Other**. Sin comando de build. Output directory: la raíz (`.`).
4. Deploy.

Rutas: `/` (demo) y `/admin` (centro de mando).
