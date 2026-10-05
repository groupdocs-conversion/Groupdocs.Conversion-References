---
title: "ImageConvertOptions Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Stellt Optionen für die Konvertierung eines Dokuments in einen Bilddateityp dar."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Stellt Optionen für die Konvertierung eines Dokuments in einen Bilddateityp dar.

Der Typ ImageConvertOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Initialisiert eine neue ImageConvertOptions-Instanz. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | Die Hintergrundfarbe, die verwendet wird, sofern vom Quellformat unterstützt. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | Die Helligkeitsanpassung des Bildes. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | Die Eigenschaft begrenzt die PDF‑Renderauflösung pro Seite auf die native Rasterauflösung der Seite, verhindert das Rendern mit einer höheren DPI als das eingebettete Bild und gibt die Seite in ihrer nativen (kleineren) Pixelgröße und DPI in der endgültigen Ausgabe aus. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | Die Kontrastanpassung, die auf das Bild angewendet wird. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | Der Beschnittbereich des Rasterbildes nach der Konvertierung. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | Der Bildspiegelungsmodus. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | Die Bild-Gamma-Anpassung. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | Die Option, die angibt, ob das Bild in Graustufen konvertiert werden soll. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | Die gewünschte Bildhöhe nach der Konvertierung. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | Die gewünschte horizontale Bildauflösung nach der Konvertierung; standardmäßig die Auflösung der Eingabedatei oder 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | Die JPEG-spezifischen Konvertierungsoptionen. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | Die achsenweise untere Grenze, die auf die begrenzte Render-DPI angewendet wird, wenn [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) aktiviert ist. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Die Seitenzahl, ab der die Konvertierung beginnen soll. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | Die Liste der Seitenindizes, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | Die Anzahl der Seiten, die ab `PageNumber` konvertiert werden sollen. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | Die PSD-spezifischen Konvertierungsoptionen. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | Der Bilddrehwinkel. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Die TIFF-spezifischen Konvertierungsoptionen. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | Die UsePdf‑Eigenschaft. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | Die gewünschte vertikale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Die spezifischen Optionen für das Wasserzeichen. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | Die WebP-spezifischen Konvertierungsoptionen. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | Die gewünschte Bildbreite nach der Konvertierung. |

### Beispiel

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
Aufgabenleitfäden, die `ImageConvertOptions` verwenden:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Siehe auch
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
