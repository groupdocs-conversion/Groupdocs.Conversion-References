---
title: "on_font_substituted özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belge tarafından başvurulan bir yazı tipi mevcut olmadığında ve bir müşteri‑tarafından sağlanan FontSubstitute kuralı, yapılandırılmış varsayılan yazı tipi veya … ile değiştirildiğinde tetiklenen olay."
type: docs
url: /tr/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

Kaynak belge tarafından başvurulan bir yazı tipi mevcut olmadığında ve ikame edildiğinde (ya müşteri tarafından sağlanan [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) kuralı, ya yapılandırılmış varsayılan yazı tipi, ya da dönüşüm hattının dahili geri dönüşü) tetiklenen olay.

Olay, tek bir `Converter.Convert(...)` çağrısı içinde `(SourceFileName, OriginalFontName)` başına tekilleştirilir — aboneler, kaynak belge başına eksik her yazı tipi için en fazla bir bildirim alır. Dönüşüm iş parçacığında senkron olarak tetiklenir. Görüntü dönüşümleri için tetiklenmez.

Sunum belgeleri için, yazı tipi ikamesi yalnızca Windows'ta algılanır, çünkü motor bunu diğer işletim sistemlerinde bulunmayan platform‑spesifik yazı tipi eşleştirmesi aracılığıyla çözer.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Ayrıca Bakınız
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
