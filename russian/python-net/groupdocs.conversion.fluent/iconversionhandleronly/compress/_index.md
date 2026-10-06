---
title: "метод compress"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Сжимает результаты конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionhandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Сжимает результаты конвертации.

Зарегистрируйте обработчик сжатого потока на этапе входа через [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (установка `OnCompressionCompleted`) вместо использования устаревшего метода цепочки fluent на возвращённом интерфейсе.

```python
def compress(self, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Параметры конвертации сжатия |

**Returns:** Continuation that proceeds to `Convert`.

### См. также
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
