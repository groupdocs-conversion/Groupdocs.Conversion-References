---
title: "Класс ConverterSettings"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Определяет настройки для настройки поведения конвертера."
type: docs
url: /ru/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Определяет настройки для настройки поведения конвертера.

Тип ConverterSettings раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Инициализирует новый экземпляр ConverterSettings со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | Реализация кэша, используемая для хранения результатов конвертации. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Пути к пользовательским каталогам шрифтов. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | Реализация слушателя конвертера, используемая для мониторинга статуса и прогресса конвертации, с его обратными вызовами Started, Progress и Completed, перенаправляемыми к [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), и [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) во время создания [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | Реализация логгера, используемая для ведения журнала процесса конвертации. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Обработчик события завершения сжатия. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Обработчик события, вызываемый при ошибке конвертации по странице. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Обработчик события, вызываемый при ошибке конвертации. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Конвертер рекурсивно сканирует каталоги шрифтов, когда установлен в True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | Временная папка, используемая для конвертации. |

### Пример

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### См. также
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
