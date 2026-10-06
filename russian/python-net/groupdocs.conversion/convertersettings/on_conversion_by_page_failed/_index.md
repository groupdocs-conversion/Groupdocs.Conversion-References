---
title: "свойство on_conversion_by_page_failed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Обработчик события, вызываемый при ошибке конвертации по странице."
type: docs
url: /ru/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

Обработчик события, вызываемый при ошибке конвертации по странице.

Учитывается для обратной совместимости: значение объединяется во внутренний контейнер событий при создании [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (соответствует [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) и переопределяется, если тот же обработчик также установлен в параметре конструктора `events`.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### См. также
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
