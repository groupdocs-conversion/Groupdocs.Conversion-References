---
title: ConverterSettings class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Defines settings for customizing Converter behaviour."
type: docs
url: /python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Defines settings for customizing Converter behaviour.

The ConverterSettings type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Initializes a new instance of ConverterSettings with default values. |

### Properties
| Property | Description |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | The cache implementation used for storing conversion results. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | The custom font directories paths. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | The converter listener implementation used for monitoring conversion status and progress, with its Started, Progress, and Completed callbacks forwarded to [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), and [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) during [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) construction. |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | The logger implementation used for logging conversion process. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | The event handler for compression completed. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | The event handler invoked when conversion by page fails. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | The event handler invoked when a conversion fails. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | The converter scans font directories recursively when set to True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | The temp folder used for conversion. |

### Example

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### See Also
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
