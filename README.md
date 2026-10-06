# Calendario Laboral 2026

Organizador de vacaciones, home office, geolocalización y feriados. Funciona como app web instalable (PWA): se abre desde el navegador del celular y se puede agregar a la pantalla de inicio.

- App (GitHub Pages): https://repo-hernan-tranquillo.github.io/calendar-vacaciones/
- Versión en claude.ai: https://claude.ai/artifact/Jn6mSdEvxmiMfuRFxvJmVW

## Instalar en el celular

- **Android (Chrome):** abrir el link de la app → menú ⋮ → "Instalar app" o "Agregar a pantalla de inicio".
- **iPhone (Safari):** abrir el link → botón Compartir → "Agregar a inicio".

Una vez instalada funciona sin conexión.

## Datos

Lo que se marca queda guardado solo en el navegador de cada dispositivo. Para pasarlo de uno a otro: "Copiar datos" en el origen, "Importar datos" en el destino y pegar.

## Archivos

- [index.html](index.html): la app completa.
- [manifest.webmanifest](manifest.webmanifest): nombre, colores e íconos para instalarla.
- [sw.js](sw.js): service worker, permite usarla sin conexión.
- [icons/](icons/): íconos de la app.

Los cambios que se suben a `main` se publican solos en GitHub Pages. La versión de claude.ai hay que volver a publicarla a mano.
