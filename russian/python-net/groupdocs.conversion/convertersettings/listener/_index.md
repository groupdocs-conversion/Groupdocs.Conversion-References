---
title: "свойство listener"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Реализация слушателя конвертера, используемая для мониторинга статуса и прогресса конвертации, с его обратными вызовами Started, Progress и Completed, перенаправляемыми в ConversionEvents.onconversionstarted…"
type: docs
url: /ru/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

Реализация слушателя конвертера, используемая для мониторинга статуса и прогресса конвертации, с его обратными вызовами Started, Progress и Completed, перенаправляемыми к [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), и [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) во время создания [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### См. также
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
