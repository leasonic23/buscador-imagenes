# Buscar por imagen

App web para buscar una foto del móvil en Google Lens, Bing, TinEye y Yandex (coincidencias exactas o parecidas).

- Ábrela en Safari en el iPhone y usa **Compartir → Añadir a pantalla de inicio**.
- Bing recibe la foto directamente (subida por formulario).
- Google Lens: botón que abre el menú Compartir del iPhone para pasar la foto a la app de Google.
- Google Lens, TinEye y Yandex rechazan subidas desde otras webs (comprobado: 403, 405 y página de inicio). Para ellos la app sube una copia reducida a un alojamiento temporal que se borra sola y busca por URL.
- La app no guarda fotos ni usa servidor propio: es un único `index.html`.
