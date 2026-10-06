---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает поток преобразованной страницы."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Получает поток преобразованной страницы. Вызывается только если установлен `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Поставщик потока преобразованной страницы. Поставщик получает `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### См. также
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
