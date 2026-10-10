TasaFácil — versión web instalable (PWA)

CONTENIDO
- index.html: aplicación y calculadora.
- manifest.json: datos para instalar como app.
- sw.js: caché básica para abrir la interfaz sin conexión.
- icon-192.png e icon-512.png: iconos.

IMPORTANTE
La aplicación consulta https://bcv.today/api/v1/rate.json. BCV Today es un servicio independiente que recopila datos publicados por el BCV; no es una fuente oficial propia del BCV. Comprueba siempre la fecha de vigencia.
La consulta automática necesita internet. El conversor admite tasas manuales.

PARA INSTALAR EN IPHONE
Safari exige que la aplicación esté alojada en una dirección HTTPS para que la experiencia PWA funcione correctamente. Abrir el index.html como archivo local permite probar la interfaz, pero no activa de forma fiable la instalación ni el service worker.

Siguiente paso recomendado:
1. Crear un repositorio en GitHub y subir todos los archivos de esta carpeta a la raíz.
2. En Settings > Pages, activar el despliegue desde la rama principal (root).
3. Abrir en Safari la URL HTTPS que GitHub Pages indique.
4. Tocar Compartir > Añadir a pantalla de inicio > Añadir.

Este paquete no está publicado todavía; no existe aún un enlace web público de instalación.
