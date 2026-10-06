---
title: "метод on_conversion_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы успешно завершится, заменяя любой ранее установленный обработчик при повторном вызове."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы успешно завершится, заменяя любой ранее установленный обработчик при повторном вызове.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Действие для обработки завершения, получающее контекст преобразованной страницы. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### См. также
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
