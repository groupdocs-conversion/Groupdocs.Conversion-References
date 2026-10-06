---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получить поток преобразованной страницы."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Получить поток конвертированной страницы. Будет вызвано только если установлен `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Поставщик потока преобразованной страницы converted_page_stream arg1arg1: `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### См. также
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
