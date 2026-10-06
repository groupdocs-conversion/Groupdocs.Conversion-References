---
title: "ImageConvertOptions-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Representerar alternativ för att konvertera ett dokument till en bildfilstyp."
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Representerar alternativ för att konvertera ett dokument till en bildfilstyp.

Typen ImageConvertOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Initierar en ny ImageConvertOptions-instans. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | Bakgrundsfärgen som ska användas där den stöds av källformatet. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | Bildens ljusstyrkejustering. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | Egenskapen begränsar PDF-renderingsupplösningen per sida till sidans inbyggda rasterupplösning, vilket förhindrar rendering med högre DPI än den inbäddade bilden och genererar sidan med dess inbyggda (småare) pixelmått och DPI i slutresultatet. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | Kontrastjusteringen som tillämpas på bilden. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | Beskärningsområdet för rasterbilden efter konvertering. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | Bildens vändningsläge. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | Bildens gammajustering. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | Alternativet som anger om bilden ska konverteras till gråskala. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | Önskad bildhöjd efter konvertering. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | Önskad horisontell bildupplösning efter konvertering; standard är indatafilens upplösning eller 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | De JPEG-specifika konverteringsalternativen. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | Den per-axel nedre gränsen som tillämpas på den begränsade renderings-DPI:n när [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) är aktiverad. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Sidnumret att börja konverteringen från. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | Listan med sidindex som ska konverteras. Ska specificeras för att konvertera specifika sidor. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | Antalet sidor att konvertera med start från `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | De PSD-specifika konverteringsalternativen. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | Bildrotationsvinkeln. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | De Tiff-specifika konverteringsalternativen. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | UsePdf‑egenskapen. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | Den önskade vertikala upplösningen för bilden efter konvertering. Standardupplösningen är upplösningen i indatafilen eller 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Specifika alternativ för vattenstämpeln. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | De WebP-specifika konverteringsalternativen. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | Den önskade bildbredden efter konvertering. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
Uppgiftsguider som använder `ImageConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Se även
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
