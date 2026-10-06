---
title: "метод convert_by_page_to"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Сохранить преобразованную страницу как поток."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionto/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Сохранить преобразованную страницу как поток.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Поставщик потока страниц конвертированного документа. converted_stream_provider arg1arg1: Контекст сохранения. |

**Returns:** Page options or handler setup interface to continue conversion building.

### См. также
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
