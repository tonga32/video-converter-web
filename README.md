# Video Converter

Conversor web de video y audio que procesa los archivos localmente mediante FFmpeg.wasm.

## Funciones
- Carga por selector o arrastrar y soltar.
- Exportación a MP4, WEBM, MOV, GIF, MP3 y WAV.
- Ajuste de resolución y calidad de video.
- Barra de progreso y descarga del resultado.
- Los archivos se procesan en el navegador y no se suben a un servidor.

## Publicación con GitHub Pages
1. Abrí Settings → Pages.
2. En Build and deployment, seleccioná Deploy from a branch.
3. Elegí la rama main y la carpeta /(root).
4. Guardá y esperá a que finalice el despliegue.

La primera conversión descarga FFmpeg WebAssembly desde CDN. El rendimiento depende del dispositivo; se recomienda comenzar con archivos pequeños. Se requiere conexión a internet para cargar las dependencias.

## Tecnologías
HTML, CSS, JavaScript ES Modules y FFmpeg.wasm.
