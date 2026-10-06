---
title: "ConverterSettings-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Definierar inställningar för att anpassa Converter‑beteende."
type: docs
url: /sv/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Definierar inställningar för att anpassa Converter‑beteende.

ConverterSettings-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Initierar en ny instans av ConverterSettings med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | Cacheimplementeringen som används för att lagra konverteringsresultat. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Sökvägarna för anpassade teckensnittskataloger. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | Konverterlyssnare-implementeringen som används för att övervaka konverteringsstatus och framsteg, med dess Started-, Progress- och Completed‑återuppringningar vidarebefordrade till [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), och [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) under konstruktionen av [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | Logger-implementeringen som används för att logga konverteringsprocessen. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Händelsehanteraren för komprimering slutförd. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Händelsehanteraren som anropas när konvertering per sida misslyckas. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Händelsehanteraren som anropas när en konvertering misslyckas. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Konvertern skannar teckensnittskataloger rekursivt när den är satt till True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | Den temporära mappen som används för konvertering. |

### Exempel

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Se även
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
