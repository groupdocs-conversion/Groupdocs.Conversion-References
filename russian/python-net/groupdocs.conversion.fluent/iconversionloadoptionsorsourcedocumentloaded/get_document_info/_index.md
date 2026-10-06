---
title: "метод get_document_info"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает информацию о исходном документе, включая количество страниц и другие свойства, специфичные для типа файла."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Получает информацию о исходном документе, включая количество страниц и другие свойства, специфичные для типа файла.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details about the source document, such as format, page count, creation date, size, and type‑specific properties.

### Пример

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### См. также
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
