---
title: "метод on_conversion_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен при ошибке конвертации страницы."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Регистрирует обратный вызов, который будет выполнен при ошибке конвертации страницы.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Действие для обработки ошибки, получающее контекст преобразованной страницы и исключение, вызвавшее ошибку. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### См. также
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
