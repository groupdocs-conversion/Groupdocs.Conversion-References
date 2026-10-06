---
title: "listener özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürücü dinleyici uygulaması, dönüşüm durumu ve ilerlemesini izlemek için kullanılır; Started, Progress ve Completed geri çağrıları ConversionEvents.onconversionstarted'e yönlendirilir…"
type: docs
url: /tr/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

Dönüştürücü dinleyici uygulaması, dönüşüm durumu ve ilerlemesini izlemek için kullanılır; Started, Progress ve Completed geri çağırmaları, [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), ve [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) adreslerine, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) oluşturulması sırasında yönlendirilir.

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Ayrıca Bakınız
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
