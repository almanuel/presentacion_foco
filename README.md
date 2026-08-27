# Presentación · Agenda Informática Nacional

Presentación web estática, sin dependencias ni proceso de compilación. El contenido responde a [`reqs.md`](reqs.md).

## Uso local

Abrí `index.html` en un navegador o iniciá un servidor local:

```bash
python3 -m http.server 8000
```

Luego visitá `http://localhost:8000`. Navegá con las flechas, `Espacio`, `Inicio` y `Fin`; cada diapositiva tiene una URL compartible como `#slide-7`.

## Publicación y distribución

Subí estos archivos a cualquier hosting estático (GitHub Pages, Netlify, Vercel o un bucket web). No hace falta instalar dependencias ni ejecutar una compilación. Para distribuirla sin publicar, comprimí `index.html` junto con esta guía y abrí el archivo en cualquier navegador moderno.

## Fotos de Cero + Infinito

Las imágenes están organizadas en `assets/cero-mas-infinito/` por tipo de vista. La diapositiva **El lugar** usa automáticamente `exteriores/patio-central.jpg` e `interiores/galeria-principal.jpg`.

Consultá [`assets/README.md`](assets/README.md) antes de agregar nuevas imágenes. Usá fotos horizontales de al menos 1600 px de ancho y optimizalas para web.

Las imágenes actualmente incluidas provienen de [Argentina.gob.ar](https://www.argentina.gob.ar/) y [CAF](https://www.caf.com/).
