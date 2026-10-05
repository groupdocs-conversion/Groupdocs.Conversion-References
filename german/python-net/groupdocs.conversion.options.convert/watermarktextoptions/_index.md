---
title: "WatermarkTextOptions Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Optionen zum Festlegen eines Textwasserzeichens im konvertierten Dokument."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

Optionen zum Festlegen eines Textwasserzeichens im konvertierten Dokument.

Stellt die Konfiguration des Aussehens des Wasserzeichens dar. Die folgenden Eigenschaften können konfiguriert werden:

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

Der WatermarkTextOptions Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | Initialisiert eine WatermarkTextOptions-Instanz mit dem angegebenen Wasserzeichentext. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | Klone aktuelle Instanz. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestimmt, ob zwei Objektinstanzen gleich sind. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als Standard‑Hash‑Funktion. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | Die Schriftfarbe des Wasserzeichens, wenn ein Textwasserzeichen angewendet wird. |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | Der Wasserzeichentext. |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | Die Wasserzeichen-Schriftart, die verwendet wird, wenn ein Textwasserzeichen angewendet wird. |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | Das Wasserzeichen wird automatisch skaliert, um die Seitengröße anzupassen, wenn es auf True gesetzt ist. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | Das Wasserzeichen wird als Hintergrund gestempelt; wenn True, wird es unten platziert, andernfalls oben (Standard ist False). (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | Die Höhe des Wasserzeichens. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | Die linke Position des Wasserzeichens. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | Der Rotationswinkel des Wasserzeichens. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | Die obere Position des Wasserzeichens. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | Die Transparenz des Wasserzeichens. Wert zwischen 0 und 1. Wert 0 ist vollständig sichtbar, Wert 1 ist unsichtbar. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | Die Breite des Wasserzeichens. (geerbt von [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |

### Beispiel

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
Aufgabenleitfäden, die `WatermarkTextOptions` verwenden:

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### Siehe auch
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
