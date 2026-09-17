# CORPOVIDASA — Sitio web corporativo

Sitio de una sola página para CORPOVIDASA (Corporación de Servicios de Vida, S.A.), bilingüe (ES/EN).

## Estructura
- `index.html` — contenido y estructura (ya incluye `<script src="js/script.js">` al final)
- `css/style.css` — estilos
- `js/script.js` — traducciones ES/EN e interactividad (modales, hero animado)
- `images/CORPOVIDASA_logo_final.png` — logo oficial

## Importante sobre pruebas locales
Si abres `index.html` haciendo doble clic (protocolo file://), Windows/Edge puede aplicar restricciones de seguridad a archivos descargados de internet ("Mark of the Web") que interfieren con JavaScript. Para probar sin problemas:
- Usa la extensión "Live Server" en VS Code, o
- Publícalo en GitHub Pages (recomendado para producción)

## Uso en GitHub Pages
1. Sube estos archivos (manteniendo la estructura de carpetas) a un repositorio de GitHub.
2. Activa GitHub Pages: Settings → Pages → Source: rama main, carpeta / (root).
3. Accede en https://tu-usuario.github.io/nombre-repositorio/

## Notas
- Los íconos son SVG originales dibujados a mano (no se usan imágenes de bancos con derechos de autor).
- El sitio usa localStorage para recordar el idioma elegido.
