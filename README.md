# Seguimiento de dieta

Página web de una sola pieza (`seguimiento.html`) para el seguimiento diario de peso, medidas y fases de dieta (definición / mantenimiento / ganancia).

## Datos en la nube

Los datos se guardan en dos sitios:

- **localStorage** del navegador (copia local instantánea, funciona sin conexión).
- **jsonbin.io**: al abrir la página se cargan los datos del bin y cada cambio se guarda automáticamente en la nube, de forma que se puede usar desde varios dispositivos.

El estado de la sincronización se muestra bajo el título (☁️ sincronizado / ⚠️ sin conexión). Si no hay conexión, la página sigue funcionando con los datos locales.

## Uso

Abrir `seguimiento.html` en el navegador, o servirlo con GitHub Pages.
