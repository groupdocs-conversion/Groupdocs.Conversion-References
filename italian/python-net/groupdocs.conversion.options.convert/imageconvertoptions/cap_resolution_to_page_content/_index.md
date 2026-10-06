---
title: "cap_resolution_to_page_content proprietà"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "La proprietà limita la risoluzione di rendering PDF per pagina alla risoluzione raster nativa della pagina, impedendo il rendering a un DPI più alto dell'immagine incorporata e generando la pagina nella sua risoluzione nativa (più piccola)…"
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

La proprietà limita la risoluzione di rendering PDF per pagina alla risoluzione raster nativa della pagina, impedendo il rendering a un DPI più alto rispetto all'immagine incorporata e generando la pagina alle sue dimensioni pixel native (più piccole) e DPI nell'output finale.

Solo le pagine dominate da immagini (scansione) sono interessate; le pagine con testo o contenuti vettoriali non vengono mai ammorbidite e vengono generate al DPI richiesto. Il limite è ignorato quando è impostata un'uscita esplicita [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) o [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/). Il valore predefinito è False (nessun limite; ogni pagina è renderizzata e generata al DPI richiesto).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Vedi anche
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
