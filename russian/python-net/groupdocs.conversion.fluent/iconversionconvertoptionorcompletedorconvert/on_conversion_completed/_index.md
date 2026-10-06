---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает поток преобразованного документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Получает поток преобразованного документа. Вызывается только когда `ConvertTo(string fileName)` или `ConvertTo(convertedStreamProvider)` настроены.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Провайдер для потока преобразованного документа. Провайдер получает `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### См. также
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
