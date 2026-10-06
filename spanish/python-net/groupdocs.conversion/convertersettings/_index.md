---
title: "Clase ConverterSettings"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Define la configuración para personalizar el comportamiento de Converter."
type: docs
url: /es/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Define la configuración para personalizar el comportamiento de Converter.

El tipo ConverterSettings expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Inicializa una nueva instancia de ConverterSettings con valores predeterminados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | La implementación de caché utilizada para almacenar los resultados de la conversión. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Las rutas de los directorios de fuentes personalizados. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | La implementación del listener del convertidor utilizada para monitorear el estado y progreso de la conversión, con sus callbacks Started, Progress y Completed reenviados a [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), y [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) durante la construcción de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | La implementación del registrador utilizada para registrar el proceso de conversión. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | El controlador de eventos para compresión completada. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | El controlador de eventos invocado cuando la conversión por página falla. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | El controlador de eventos invocado cuando una conversión falla. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | El convertidor escanea los directorios de fuentes de forma recursiva cuando está configurado en True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | La carpeta temporal utilizada para la conversión. |

### Ejemplo

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Ver también
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
