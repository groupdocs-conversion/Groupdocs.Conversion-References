---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен при успешном завершении конвертации страницы."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Регистрирует обратный вызов, который будет выполнен при успешном завершении конвертации страницы.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Действие для обработки завершения, получающее контекст преобразованной страницы. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### См. также
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
