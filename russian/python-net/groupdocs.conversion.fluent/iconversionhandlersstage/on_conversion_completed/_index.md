---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен при успешном завершении конвертации документа, заменяя любой ранее установленный обработчик при повторном вызове."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Регистрирует обратный вызов, который будет выполнен при успешном завершении конвертации документа, заменяя любой ранее установленный обработчик при повторном вызове.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Действие для обработки завершения, получающее контекст конверсии. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### См. также
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
