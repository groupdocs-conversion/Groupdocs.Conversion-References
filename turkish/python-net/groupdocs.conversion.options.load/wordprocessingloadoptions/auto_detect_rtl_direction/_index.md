---
title: "auto_detect_rtl_direction özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "autodetectrtldirection özelliği, çoğunlukla sağdan sola metin içeren paragrafların ve koşulların dönüştürmeden önce bidi bayraklarının onarılıp onarılmayacağını belirler."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

auto_detect_rtl_direction özelliği, çoğunlukla sağdan sola metin içeren paragrafların ve koşulların (runs) dönüştürmeden önce bidi bayraklarının onarılıp onarılmayacağını belirler.

True (varsayılan) olarak ayarlandığında, özellik Microsoft Word ve LibreOffice tarafından kullanılan bir sezgisel kuralı uygular; yalnızca RTL betiği içeren koşullarda `<w:bidi/>` olmadan ve `<w:rtl w:val="0"/>` ile OOXML üreten Google Docs gibi araçların oluşturduğu Arapça/İbranice belgelerin render edilmesini düzeltir. False olarak ayarlandığında, kaynak işaretlemenin katı OOXML yorumlamasını korur.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Ayrıca Bakınız
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
