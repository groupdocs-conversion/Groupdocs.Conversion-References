---
title: "Класс Converter"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Представляет основной класс, который управляет процессом конвертации документа."
type: docs
url: /ru/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Представляет основной класс, который управляет процессом конвертации документа.

Тип Converter раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Инициализирует новый экземпляр Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Инициализирует новый экземпляр [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Инициализирует новый экземпляр [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Инициализирует новый Converter с явными событиями конвертации. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Инициализирует новый экземпляр Converter с явными событиями конвертации. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Инициализирует новый экземпляр Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Инициализирует новый экземпляр [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Инициализирует новый экземпляр класса [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Инициализирует новый Converter с явными событиями конвертации. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Инициализирует новый Converter с явными событиями конвертации. |

### Методы
| Метод | Описание |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Преобразует исходный документ и сохраняет весь преобразованный документ. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Преобразует исходный документ и сохраняет полностью преобразованный документ. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Преобразует исходный документ и сохраняет полностью преобразованный документ. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Преобразует исходный документ и сохраняет полностью преобразованный документ. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Преобразует исходный документ и сохраняет полностью преобразованный документ. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Преобразует исходный документ и сохраняет преобразованный документ постранично. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Преобразует исходный документ и сохраняет преобразованный документ постранично. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Преобразует исходный документ и сохраняет преобразованный документ постранично. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Преобразует исходный документ и сохраняет преобразованный документ постранично. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Освобождает ресурсы. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Получает все поддерживаемые преобразования. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Получает информацию об исходном документе, включая количество страниц и другие свойства, специфичные для типа файла. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Получает возможные преобразования исходного документа. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Получает поддерживаемые преобразования для указанного расширения документа. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Проверяет, защищён ли исходный документ паролем. |

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Руководства задач, использующие `Converter`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### См. также
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
