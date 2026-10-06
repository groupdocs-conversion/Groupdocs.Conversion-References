---
title: "cap_resolution_to_page_content propiedad"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad limita la resolución de renderizado PDF por página a la resolución raster nativa de la página, evitando renderizar a un DPI más alto que la imagen incrustada y emitiendo la página en su nativa (más pequeña)…"
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

La propiedad limita la resolución de renderizado PDF por página a la resolución raster nativa de la página, evitando renderizar a un DPI más alto que la imagen incrustada y emitiendo la página con sus dimensiones de píxel y DPI nativos (más pequeños) en la salida final.

Solo las páginas dominadas por imágenes (escaneo) se ven afectadas; las páginas con texto o contenido vectorial nunca se suavizan y se emiten al DPI solicitado. El límite se ignora cuando se establece una salida explícita de [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) o [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/). El valor predeterminado es False (sin limitación; cada página se renderiza y emite al DPI solicitado).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Ver también
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
