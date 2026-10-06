---
title: "метод on_conversion_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен при ошибке конвертации документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Регистрирует обратный вызов, который будет выполнен при ошибке конвертации документа. Повторный вызов заменяет любой ранее установленный обработчик.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – действие для обработки ошибки, получающее контекст конвертации и исключение, вызвавшее ошибку. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### См. также
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
