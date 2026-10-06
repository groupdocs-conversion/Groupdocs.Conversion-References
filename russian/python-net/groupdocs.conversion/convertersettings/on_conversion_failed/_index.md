---
title: "свойство on_conversion_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Обработчик события, вызываемый при ошибке конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

Обработчик события, вызываемый при ошибке конвертации.

Сохранено для обратной совместимости: значение объединяется во внутренний набор событий при создании [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (соответствует [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) и переопределяется, если тот же обработчик также установлен в параметре конструктора `events`.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### См. также
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
