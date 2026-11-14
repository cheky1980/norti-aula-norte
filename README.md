# Norti · Aula Norte

Simulador web de conversación de Norti, asistente virtual de Aula Norte.

## Contenido
- `index.html`: simulador listo para publicar.
- `mapa-recorrido.svg`: mapa visual de los recorridos conversacionales.

## Publicar con GitHub Pages
1. Crear un repositorio en GitHub, por ejemplo `norti-aula-norte`.
2. Subir estos archivos a la raíz del repositorio.
3. Abrir **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Seleccionar la rama `main` y la carpeta `/ (root)`, y guardar.
6. Esperar la publicación. La dirección tendrá el formato:
   `https://USUARIO.github.io/norti-aula-norte/`

## Alcance de esta versión
- Registra fecha y hora local de Argentina en el navegador para la sesión, los mensajes y los pasos del recorrido.
- Genera un identificador de sesión en el navegador.
- Mantiene los caminos de inscripción, campus virtual, organización académica y pregunta límite.
- Es una simulación: no envía derivaciones reales ni guarda conversaciones en una base de datos central.

## Próxima etapa opcional
Para conservar conversaciones y consultarlas desde un panel privado, conectar el frontend con una API y una base de datos (por ejemplo Supabase). No colocar claves privadas en `index.html`.
