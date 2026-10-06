---
title: "Класс DocumentInfo"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Базовая реализация для получения полиморфной информации о документе."
type: docs
url: /ru/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

Базовая реализация для получения полиморфной информации о документе.

Экземпляры возвращаются методом `Converter.get_document_info()` и раскрывают метаданные, такие как формат, количество страниц, дата создания, размер и специфические для формата атрибуты.

Тип DocumentInfo раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | Дата создания документа. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Формат документа. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Общее количество страниц в документе. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | Свойство реализует [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | Размер документа в байтах. |

### Пример

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Пример использования
show_document_info("./lorem-ipsum.txt")
```

### См. также
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
