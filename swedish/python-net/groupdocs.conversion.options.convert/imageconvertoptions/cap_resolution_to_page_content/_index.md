---
title: "cap_resolution_to_page_content egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Egenskapen begränsar per‑sida PDF‑renderingsupplösningen till sidans inbyggda rasterupplösning, vilket förhindrar rendering med högre DPI än den inbäddade bilden och avger sidan i dess inbyggda (mindre) …"
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

Egenskapen begränsar PDF-renderingsupplösningen per sida till sidans inbyggda rasterupplösning, vilket förhindrar rendering med högre DPI än den inbäddade bilden och genererar sidan med dess inbyggda (småare) pixelmått och DPI i slutresultatet.

Endast bild‑dominerade (skannade) sidor påverkas; sidor med text eller vektor­innehåll mjukas aldrig upp och avges i den begärda DPI:n. Begränsningen ignoreras när en explicit utdata [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) eller [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) har satts. Standardvärdet är False (ingen begränsning; varje sida renderas och avges i den begärda DPI:n).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Se även
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
