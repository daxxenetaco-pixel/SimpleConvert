# SimpleConvert

Conversor de imágenes gratuito, rápido y 100% privado que corre directamente en el navegador. Sin servidores, sin registro, sin límites.

---

## ¿Qué es?

SimpleConvert es una aplicación web de archivo único (`SimpleConvert.html`) que convierte imágenes usando la Canvas API del navegador. Ningún archivo tuyo sale de tu dispositivo en ningún momento.

## Características

- **Formatos soportados:** PNG, JPEG, WEBP, SVG, HEIC/HEIF, PDF
- **Conversión por lotes** con descarga en ZIP
- **SimpleEdit** — editor rápido integrado: rotar, voltear, recortar, ajustar brillo/contraste/saturación
- **Mantener proporción** — bloqueo de aspecto automático al redimensionar
- **Eliminación de metadatos EXIF** por defecto (ubicación GPS, modelo de cámara, fecha)
- **Estimación de tamaño** antes de convertir
- **Historial de conversiones** en sesión
- **Modo oscuro** con persistencia en localStorage
- **Sin registro, sin cookies de rastreo, sin anuncios, sin suscripciones**

## Uso

No requiere instalación ni servidor. Descarga el archivo y ábrelo en cualquier navegador moderno:

```
SimpleConvert.html → abrir con Chrome / Firefox / Safari / Edge
```

O despliégalo como sitio estático en GitHub Pages, Netlify, Vercel, etc.

## Tecnologías

| Librería | Uso |
|---|---|
| [heic2any](https://github.com/alexcorvi/heic2any) | Conversión de HEIC/HEIF en el cliente |
| [JSZip](https://stuk.github.io/jszip/) | Generación de archivos ZIP |
| [jsPDF](https://github.com/parallax/jsPDF) | Exportación a PDF |
| Canvas API (nativa) | Conversión, edición y renderizado de imágenes |

## Privacidad

- Procesamiento 100% local — ningún byte de tus imágenes toca un servidor externo
- Sin cookies de rastreo ni analíticas de terceros
- Los metadatos EXIF se eliminan durante el re-renderizado en canvas
- El historial se guarda solo en `localStorage` de tu navegador y puedes borrarlo en cualquier momento

## Licencia

[MIT](LICENSE) — libre para usar, modificar y distribuir.
