---
title: "ImageConvertOptions klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt opties voor het converteren van een document naar een afbeeldingsbestandtype voor."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Stelt opties voor het converteren van een document naar een afbeeldingsbestandtype voor.

Het ImageConvertOptions‑type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Initialiseert een nieuw ImageConvertOptions‑exemplaar. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | De achtergrondkleur die gebruikt wordt waar ondersteund door het bronformaat. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | De helderheidsaanpassing van de afbeelding. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | De eigenschap beperkt de PDF‑renderresolutie per pagina tot de native rasterresolutie van de pagina, waardoor renderen op een hogere DPI dan de ingesloten afbeelding wordt voorkomen en de pagina wordt uitgegeven met zijn native (kleinere) pixelafmetingen en DPI in de uiteindelijke output. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | De contrastaanpassing toegepast op de afbeelding. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | Het bijsnijdgebied van de rasterafbeelding na conversie. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | De spiegelmodus van de afbeelding. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | De gamma-aanpassing van de afbeelding. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | De optie die aangeeft of de afbeelding naar grijstinten moet worden geconverteerd. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | De gewenste afbeeldingshoogte na conversie. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | De gewenste horizontale resolutie van de afbeelding na conversie; standaard de resolutie van het invoerbestand of 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | De JPEG-specifieke conversie-opties. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | De per-as ondergrens die wordt toegepast op de begrensde render-DPI wanneer [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) is ingeschakeld. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Het paginanummer waar de conversie moet beginnen. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | De lijst met paginacijfers die moeten worden geconverteerd. Moet worden gespecificeerd om specifieke pagina's te converteren. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | Het aantal pagina's dat moet worden geconverteerd, beginnend bij `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | De PSD-specifieke conversie-opties. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | De rotatiehoek van de afbeelding. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | De Tiff-specifieke conversie-opties. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | De UsePdf‑eigenschap. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | De gewenste verticale resolutie van de afbeelding na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | De watermerk‑specifieke opties. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | De WebP-specifieke conversie-opties. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | De gewenste afbeeldingsbreedte na conversie. |

### Voorbeeld

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
Taakgidsen die `ImageConvertOptions` gebruiken:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Zie ook
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
