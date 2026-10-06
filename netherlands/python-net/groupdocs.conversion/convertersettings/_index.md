---
title: "ConverterSettings klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Definieert instellingen voor het aanpassen van het gedrag van de Converter."
type: docs
url: /nl/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Definieert instellingen voor het aanpassen van het gedrag van de Converter.

Het ConverterSettings-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Initialiseert een nieuw exemplaar van ConverterSettings met standaardwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | De cache-implementatie die wordt gebruikt voor het opslaan van conversieresultaten. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | De paden van aangepaste lettertype-mappen. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | De implementatie van de converter‑listener die wordt gebruikt voor het bewaken van de conversiestatus en voortgang, waarbij de callbacks Started, Progress en Completed worden doorgestuurd naar [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), en [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) tijdens de constructie van [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | De logger-implementatie die wordt gebruikt voor het loggen van het conversieproces. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | De gebeurtenisafhandelaar voor voltooide compressie. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | De gebeurtenisafhandelaar die wordt aangeroepen wanneer conversie per pagina mislukt. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | De gebeurtenisafhandelaar die wordt aangeroepen wanneer een conversie mislukt. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | De converter scant lettertype‑mappen recursief wanneer ingesteld op True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | De tijdelijke map die wordt gebruikt voor conversie. |

### Voorbeeld

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Zie ook
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
