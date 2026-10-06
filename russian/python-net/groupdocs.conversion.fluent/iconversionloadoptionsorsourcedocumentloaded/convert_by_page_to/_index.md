---
title: "метод convert_by_page_to"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Сохраняет конвертированную страницу как поток."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Сохраняет конвертированную страницу как поток.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Поставщик потока страниц преобразованного документа. |

**Returns:** Page options or handler setup interface to continue conversion building.

### См. также
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
