---
title: "метод with_events"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Зарегистрируйте обработчики событий жизненного цикла конвертации в объекте ConversionEvents, который существует в течение срока жизни конвертера и срабатывает при каждом запуске конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Регистрируйте обработчики событий жизненного цикла конвертации в контейнере [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/), который живёт в течение срока жизни конвертера и вызывается при каждом запуске конвертации.

Может быть вызвано до или после [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).
Несколько вызовов накапливаются: один и тот же внутренний объект передаётся каждому действию `configure`, поэтому обработчики, установленные в ранних вызовах, сохраняются, если только не будут перезаписаны более поздним вызовом.

```python
def with_events(self, configure):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Действие, которое изменяет пакет событий. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### См. также
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
