---
title: "метод compress"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Сжимает результаты конвертации; зарегистрируйте обработчик сжатого‑потока на этапе входа через IConversionSettings.withevents (устанавливая OnCompressionCompleted) вместо использования устаревшего fluent…"
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Сжимает результаты конвертации; зарегистрируйте обработчик сжатого потока на начальном этапе через [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (устанавливая `OnCompressionCompleted`) вместо использования устаревшего метода цепочки fluent.

```python
def compress(self, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Параметры преобразования сжатия. |

**Returns:** Continuation that proceeds to `Convert`.

### См. также
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
