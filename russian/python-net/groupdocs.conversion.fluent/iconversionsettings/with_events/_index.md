---
title: "метод with_events"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Регистрирует обработчики событий жизненного цикла конвертации в объекте ConversionEvents, который существует в течение срока жизни конвертера и срабатывает при каждом запуске конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Регистрирует обработчики событий жизненного цикла конвертации в контейнере [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/), который существует в течение срока жизни конвертера и срабатывает при каждом запуске конвертации.

Находится на том же этапе входа, что и [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Несколько вызовов накапливаются: один и тот же внутренний контейнер передаётся каждому действию `configure`, поэтому обработчики, установленные в ранних вызовах, сохраняются, если их не перезаписать более поздним.

```python
def with_events(self, configure):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Действие, которое изменяет пакет событий. |

**Returns:** The source-selection stage so that `Load` may be chained.

### См. также
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
