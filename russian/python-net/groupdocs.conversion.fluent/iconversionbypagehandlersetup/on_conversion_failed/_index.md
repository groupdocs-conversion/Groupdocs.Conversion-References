---
title: "метод on_conversion_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обратный вызов, который будет выполнен при ошибке конвертации страницы."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_failed/
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
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – действие для обработки ошибки, получающее контекст преобразованной страницы и исключение, вызвавшее ошибку. |

**Returns:** IConversionByPageHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### См. также
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
