---
title: "метод on_conversion_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен при ошибке конвертации страницы."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/
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
| on_failed | `Action[ConvertedPageContext, Exception]` | Вызываемый объект, который обрабатывает ошибку, получая контекст преобразованной страницы и исключение, вызвавшее ошибку. |

**Returns:** Interface to continue conversion building, allowing only `OnConversionCompleted` or `Convert`/`Compress`.

### См. также
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
