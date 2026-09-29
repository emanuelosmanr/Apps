# Closet Studio v2

## Publicar sin borrar datos existentes
1. Descomprime el ZIP.
2. Copia **el contenido** de esta carpeta sobre los archivos del mismo repositorio y la misma rama que ya usa GitHub Pages.
3. Reemplaza `index.html`, `styles.css`, `app.js`, `sw.js`, `manifest.webmanifest`, `README.md` y la carpeta `icons`.
4. No borres el repositorio, no cambies su nombre, no cambies la URL de GitHub Pages y no uses otro dominio.
5. No cambies en `app.js` estos identificadores: `closetStudioDB`, `garments`, `cs_looks`, `cs_profile`.
6. Antes de actualizar, abre **Perfil > Exportar** para tener un respaldo JSON.

Los archivos de la app, el caché offline y los datos personales son almacenamientos diferentes. Esta actualización cambia el caché a `closet-studio-v2`, pero conserva IndexedDB y localStorage. El botón **Borrar todo** sí elimina los datos deliberadamente.

Si el navegador muestra la versión anterior después de publicar, cierra todas las pestañas de la app y vuelve a abrirla. También puedes recargar la página. No selecciones opciones del navegador que borren “datos del sitio”.
