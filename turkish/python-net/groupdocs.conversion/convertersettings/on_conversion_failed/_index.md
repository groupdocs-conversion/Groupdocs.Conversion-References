---
title: "on_conversion_failed özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir dönüşüm başarısız olduğunda tetiklenen olay işleyicisi."
type: docs
url: /tr/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

Bir dönüşüm başarısız olduğunda tetiklenen olay işleyicisi.

Geri uyumluluk için saygı gösterilir: değer, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) oluşturulması sırasında dahili olay çantasına birleştirilir (mapping to [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) ve aynı işleyici `events` yapıcı parametresinde de ayarlanmışsa geçersiz kılınır.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Ayrıca Bakınız
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
