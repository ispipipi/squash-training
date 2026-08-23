# Squash Training PWA

Paquete listo para publicar en GitHub Pages.

## Que incluye

- `index.html`: app responsive para movil con una sesion por pantalla.
- `manifest.json`: configuracion instalable como PWA.
- `service-worker.js`: cache basico para abrir la app sin conexion despues de la primera carga.
- `icons/`: iconos PWA y Apple Touch Icon.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `squash-training`.
2. Sube todos los archivos de este paquete a la raiz del repositorio.
3. En GitHub, entra a `Settings` y luego a `Pages`.
4. En `Build and deployment`, elige `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/root`.
6. Abre la URL publicada en Safari desde el iPhone.
7. Toca `Compartir` y luego `Añadir a pantalla de inicio`.

El progreso se guarda en el navegador del dispositivo. Si usas otro telefono o borras datos del sitio, los checks no se trasladan automaticamente.
