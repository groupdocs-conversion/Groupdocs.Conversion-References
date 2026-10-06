---
title: "метод get_document_info"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает информацию об исходном документе, включая количество страниц и другие свойства, специфичные для типа файла."
type: docs
url: /ru/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Получает информацию об исходном документе, включая количество страниц и другие свойства, специфичные для типа файла.

Узнайте больше о конвертированном документе – тип файла, количество страниц, дата создания и многие другие свойства, специфичные для формата:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Пример

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### См. также
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
