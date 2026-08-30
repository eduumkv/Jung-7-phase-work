# Ciclo de 7 — PWA

## Qué incluye
- 7 fases guiadas con instrucciones contextuales.
- Autosave del borrador.
- Historial permanente en IndexedDB.
- Un JSON independiente por registro.
- "Guardar en Archivos" usa el menú Compartir de iOS cuando está disponible.
- Exportación de respaldo completo.
- Soporte offline mediante Service Worker después de la primera carga.

## Instalación en iPhone
1. Publica esta carpeta en una URL HTTPS (por ejemplo GitHub Pages, Netlify o Cloudflare Pages).
2. Ábrela en Safari.
3. En iOS 26, en Compartir > Añadir a pantalla de inicio, deja activado "Abrir como app web".
4. Abre el icono "Ciclo de 7".

## Archivos en iOS
Al terminar un registro pulsa "Guardar en Archivos". En el menú de compartir selecciona "Guardar en Archivos" y elige/crea la carpeta `Ciclo de 7`.
El almacenamiento interno de la app funciona con IndexedDB; los JSON son la copia portátil.

## Nota
Un archivo HTML abierto directamente desde la app Archivos no puede comportarse igual que una PWA servida por HTTPS. Para instalación y almacenamiento fiable en iPhone necesita una URL web.
