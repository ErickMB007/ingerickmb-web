# ErickMB · Infraestructura de marketing

Landing independiente: https://erickmb-marketing.ebello1701.workers.dev

`worker.mjs` contiene la página y la ficha descargable servida en `/ficha-negocio.txt`. No requiere dependencias. Contacto: WhatsApp público de ErickMB.

Publicación inicial realizada por API de Cloudflare. GitHub guarda el código; no hay despliegue automático configurado.

La página emite eventos locales `contact_click` y `brief_download` a dataLayer, sin datos personales. No contiene un contenedor GTM ni GA4 activo. Search Console y Looker Studio aún no están conectados. El clic en WhatsApp no acredita contacto ni venta.

Comprobación: `node --check marketing/worker.mjs`.
