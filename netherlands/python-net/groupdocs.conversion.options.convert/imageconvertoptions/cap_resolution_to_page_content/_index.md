---
title: "cap_resolution_to_page_content eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De eigenschap beperkt de per-pagina PDF-renderresolutie tot de native rasterresolutie van de pagina, waardoor renderen op een hogere DPI dan de ingebedde afbeelding wordt voorkomen en de pagina wordt uitgegeven in zijn native (kleinere) resolutie…"
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

De eigenschap beperkt de PDF‑renderresolutie per pagina tot de native rasterresolutie van de pagina, waardoor renderen op een hogere DPI dan de ingesloten afbeelding wordt voorkomen en de pagina wordt uitgegeven met zijn native (kleinere) pixelafmetingen en DPI in de uiteindelijke output.

Alleen beeld‑gedomineerde (scan) pagina's worden beïnvloed; pagina's met tekst of vectorinhoud worden nooit verzacht en worden uitgegeven met de gevraagde DPI. De limiet wordt genegeerd wanneer een expliciete output [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) of [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) is ingesteld. Standaard is False (geen beperking; elke pagina wordt gerenderd en uitgegeven met de gevraagde DPI).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Zie ook
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
