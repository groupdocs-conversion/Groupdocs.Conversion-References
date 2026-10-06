---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает поток преобразованной страницы."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Получает поток преобразованной страницы. Будет вызвано только если `ConvertTo(convertedStreamProvider)` установлен.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Поставщик потока преобразованной страницы. `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### См. также
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
