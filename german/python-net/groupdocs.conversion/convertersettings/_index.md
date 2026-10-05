---
title: "ConverterSettings Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Definiert Einstellungen zur Anpassung des Verhaltens des Converters."
type: docs
url: /de/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Definiert Einstellungen zur Anpassung des Verhaltens des Converters.

Der ConverterSettings-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Initialisiert eine neue Instanz von ConverterSettings mit Standardwerten. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | Die Cache-Implementierung, die zum Speichern von Konvertierungsergebnissen verwendet wird. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Die Pfade zu benutzerdefinierten Schriftverzeichnissen. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | Die Implementierung des Converter-Listeners, die zur Überwachung des Konvertierungsstatus und -fortschritts verwendet wird, wobei ihre Started-, Progress- und Completed-Callbacks an [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), und [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) während der Konstruktion von [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) weitergeleitet werden. |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | Die Logger-Implementierung, die zum Protokollieren des Konvertierungsprozesses verwendet wird. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Der Ereignishandler für abgeschlossene Kompression. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Der Ereignishandler, der aufgerufen wird, wenn die Konvertierung pro Seite fehlschlägt. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Der Ereignishandler, der aufgerufen wird, wenn eine Konvertierung fehlschlägt. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Der Converter durchsucht Schriftverzeichnisse rekursiv, wenn er auf True gesetzt ist. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | Der temporäre Ordner, der für die Konvertierung verwendet wird. |

### Beispiel

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Siehe auch
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
