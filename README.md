# CORPOVIDASA — Sitio web corporativo

Sitio de una sola página para CORPOVIDASA (Corporación de Servicios de Vida, S.A.), bilingüe (ES/EN).

## Estructura
- `index.html` — contenido y estructura
- `css/style.css` — estilos
- `js/script.js` — traducciones ES/EN e interactividad
- `images/CORPOVIDASA_logo_final.png` — logo oficial

## Contenido
- Header con menú, selector de idioma y botón de contacto
- Hero con el mensaje "Múltiples soluciones Integradas / Coordinadas para mejorar la vida de nuestros clientes en forma sencilla y práctica", seguido de una red de 8 círculos animados (servicios del grupo) que orbitan alrededor del globo
- Interactividad: al pasar el cursor o presionar cada círculo, aparece a la par el nombre del servicio (con tooltip nativo del navegador como respaldo)
- Tres círculos abren un modal detallado al presionarlos:
  - **Hospedaje**: información completa de Apartamentos Confortables Guatemala (características, descuentos, aspectos favorables)
  - **Servicios médicos y funerarios**: modal con dos pestañas (Servicios Médicos / Servicios Funerarios), cada una con íconos por sección
  - Todo el contenido de estos 3 modales se traduce automáticamente al cambiar el idioma a inglés (ES/EN)
- Visión corporativa
- Servicios al migrante
- Grid de las 8 empresas del grupo (Nuestras Empresas)
- Estadísticas, contacto con mapa y footer

## Uso
Abrir `index.html` directamente en el navegador, o abrir la carpeta en Visual Studio Code / GitHub Pages para publicarlo.

## Notas
- Los íconos son SVG originales dibujados a mano (no se usan imágenes de bancos con derechos de autor).
- El sitio usa localStorage para recordar el idioma elegido.
