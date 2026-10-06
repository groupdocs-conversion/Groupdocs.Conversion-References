---
title: "метод on_conversion_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы завершится с ошибкой, заменяя любой ранее установленный обработчик при повторном вызове."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы завершится с ошибкой, заменяя любой ранее установленный обработчик при повторном вызове.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Вызываемый объект, который обрабатывает ошибку, получая контекст преобразованной страницы и исключение, вызвавшее ошибку. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### См. также
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
