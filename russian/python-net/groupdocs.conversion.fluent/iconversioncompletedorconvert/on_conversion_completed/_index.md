---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает поток преобразованного документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Получает поток конвертированного документа. Срабатывает только если установлен `ConvertTo(string fileName)` или `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Поставщик потока преобразованного документа (`ConvertedContext`). |

**Returns:** Interface to continue conversion building.

### См. также
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
