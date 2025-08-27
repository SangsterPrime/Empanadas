negocio 18
# Empanadas Caseras 

Descripción
- Landing simple para ordenar empanadas (Pino / Queso) + docenas y delivery.
- Archivo principal: `negocio.html`.

Cómo abrir
- Abrir `negocio.html` en el navegador (doble clic) o desde VS Code con la extensión Live Server ("Go Live").
- Si el favicon no cambia, recarga sin caché (Ctrl+F5) o prueba modo incógnito.

Favicon / logo
- Coloca tu imagen descargada en la misma carpeta y nómbrala `empanadas_caseras.jpg`.
- Ya está referenciada en el `<head>`:
  ```html
  <link rel="icon" type="image/jpeg" href="empanadas_caseras.jpg">
  ```
- Recomendado: imagen cuadrada 64x64 o 32x32. Para mejorar compatibilidad convierte a `.ico` si es necesario.

Dependencias
- Bootstrap 5 se carga vía CDN en `negocio.html`. No requiere instalación local.

Editar precios y teléfono
- Abrir `negocio.html` y modificar el bloque JS:
  ```js
  const phone = "56942075446";
  const prices = { pino: 3000, queso: 3000, docena_pino: 29000, docena_queso: 29000, delivery: 2000 };
  ```
- Guarda y recarga la página.

Sugerencias rápidas
- Usa imágenes optimizadas (webp/png/jpg) y cuadradas para favicon.
- Para desplegar en web, sube todos los archivos al hosting y asegúrate que la ruta del favicon sea accesible públicamente.

Contacto
- Archivo mantenido en: `c:\Users\sangs\OneDrive\Escritorio\HTML\negocio.html`
