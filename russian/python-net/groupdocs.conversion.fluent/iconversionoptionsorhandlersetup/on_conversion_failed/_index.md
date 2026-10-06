---
title: "метод on_conversion_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен при ошибке конвертации документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Регистрирует обратный вызов, который будет выполнен при ошибке конвертации документа.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Вызываемый объект, который обрабатывает сбой, получая контекст конверсии и исключение, вызвавшее сбой. |

**Returns:** `IConversionOptionsOrHandlerSetup`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### См. также
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
