---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает поток преобразованного документа и срабатывает только если установлен ConvertTo(string fileName) или ConvertTo(convertedStreamProvider)."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Получает поток преобразованного документа и вызывается только если установлен `ConvertTo(string fileName)` или `ConvertTo(convertedStreamProvider)`

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Поставщик потока преобразованного документа. |

**Returns:** Interface to continue conversion building.

### См. также
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
