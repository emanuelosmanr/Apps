# Closet Studio

PWA estática, adaptable a iPhone, iPad y Mac, para administrar prendas y crear combinaciones. No requiere servidor de aplicaciones para sus funciones locales.

## Publicar en GitHub Pages
1. Descomprime el proyecto y sube todos los archivos a la raíz de un repositorio.
2. En GitHub abre **Settings > Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
4. Abre la dirección pública generada por GitHub.

## Instalar
- iPhone/iPad: abre el sitio en Safari, toca **Compartir** y luego **Añadir a pantalla de inicio**.
- Mac: usa la opción del navegador para añadir o instalar la app web.

## Privacidad
Las fotos, prendas, preferencias y combinaciones se guardan en IndexedDB/localStorage del propio navegador. Borrar los datos del sitio también borra el clóset.

## Alcance de la sugerencia “inteligente”
Esta versión incluye un motor local basado en categoría, estilo, audiencia, armonía de color y tono de piel aproximado. No envía fotos a servicios externos. El archivo `app.js` deja el producto listo para reemplazar o complementar esa lógica con un endpoint de visión generativa propio.

## Desarrollo local
Los service workers requieren HTTP/HTTPS. Ejecuta, por ejemplo:

```bash
python3 -m http.server 8080
```

Luego abre `http://localhost:8080`.
