# Psicología para la Vida · Agenda profesional

PWA de uso personal para gestionar pacientes, citas, sesiones, tareas, pagos y paquetes.

## Publicación en GitHub + Netlify

1. Subir todos los archivos de esta carpeta a la raíz del repositorio.
2. Netlify debe estar conectado al repositorio de GitHub.
3. Build command: dejar vacío.
4. Publish directory: `.`
5. Después de publicar, abrir la dirección de Netlify en Safari del iPhone y elegir **Compartir → Añadir a pantalla de inicio**.

## Respaldo de datos

La agenda guarda los datos localmente en el navegador/PWA. Para protegerlos frente a borrado del navegador o cambio de dispositivo:

1. Abrir **Más → Respaldo de datos → Crear respaldo**.
2. Guardar el archivo `.json` en **Archivos/iCloud Drive** o en otro lugar privado y seguro.
3. En un dispositivo nuevo, abrir la agenda y usar **Más → Respaldo de datos → Restaurar respaldo**.
4. Seleccionar el archivo `.json` y confirmar la restauración.

El respaldo incluye pacientes, citas, sesiones, tareas, pagos, paquetes y horarios.

> El archivo de respaldo puede contener información sensible de pacientes. Debe almacenarse de forma privada y segura.

## Archivos principales

- `index.html`: aplicación y funciones de respaldo/restauración.
- `manifest.json`: configuración PWA.
- `sw.js`: caché/offline básico.
- `logo.png`: logo oficial.
- `icon-*.png` y `favicon-32.png`: iconos.
