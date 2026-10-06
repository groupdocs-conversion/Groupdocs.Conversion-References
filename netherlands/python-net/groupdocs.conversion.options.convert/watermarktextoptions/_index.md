---
title: "WatermarkTextOptions klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Opties voor het instellen van een tekstwatermerk op het geconverteerde document."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

Opties voor het instellen van een tekstwatermerk op het geconverteerde document.

Stelt de configuratie van het uiterlijk van het watermerk voor. De volgende eigenschappen kunnen worden geconfigureerd:

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

Het type WatermarkTextOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | Initialiseert een WatermarkTextOptions exemplaar met de opgegeven watermerktekst. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | Kloon de huidige instantie. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bepaalt of twee objectinstellingen gelijk zijn. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als de standaard hash-functie. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | De watermerkletterkleur als een tekstwatermerk wordt toegepast. |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | De watermerktekst. |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | Het watermerklettertype dat wordt gebruikt wanneer een tekstwatermerk wordt toegepast. |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | Het watermerk wordt automatisch geschaald om op de paginagrootte te passen wanneer ingesteld op True. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | Het watermerk wordt gestempeld als achtergrond; als True wordt het onderaan geplaatst, anders wordt het bovenop geplaatst (standaard is False). (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | De hoogte van het watermerk. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | De linkse positie van het watermerk. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | De rotatiehoek van het watermerk. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | De bovenste positie van het watermerk. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | De transparantie van het watermerk. Waarde tussen 0 en 1. Waarde 0 is volledig zichtbaar, waarde 1 is onzichtbaar. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | De breedte van het watermerk. (geërfd van [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

with Converter("./professional-services.docx") as converter:
    watermark = WatermarkTextOptions("DRAFT")
    watermark.color = Color.from_argb(128, 211, 211, 211)  # lite gray
    watermark.top = 10
    watermark.left = 10
    watermark.width = 300
    watermark.height = 300
    watermark.background = True

    options = PdfConvertOptions()
    options.pages_count = 1
    options.watermark = watermark

    converter.convert("./professional-services.pdf", options)
```

### Guides
Taakgidsen die `WatermarkTextOptions` gebruiken:

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### Zie ook
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
