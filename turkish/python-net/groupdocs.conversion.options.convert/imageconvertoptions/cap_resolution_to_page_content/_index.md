---
title: "cap_resolution_to_page_content özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bu özellik, sayfa başına PDF render çözünürlüğünü sayfanın yerel raster çözünürlüğüyle sınırlar, gömülü görüntüden daha yüksek DPI'de render edilmesini önler ve sayfayı yerel (daha küçük) çözünürlükte oluşturur…"
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

Bu özellik, sayfa başına PDF render çözünürlüğünü sayfanın yerel raster çözünürlüğüyle sınırlar; gömülü görüntüden daha yüksek DPI'da render edilmesini önler ve sayfayı yerel (daha küçük) piksel boyutları ve DPI ile nihai çıktıda üretir.

Yalnızca görüntü ağırlıklı (tarama) sayfalar etkilenir; metin veya vektör içeren sayfalar asla yumuşatılmaz ve istenen DPI'de oluşturulur. Açık bir çıktı [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) veya [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) ayarlandığında sınırlama yok sayılır. Varsayılan değer False'tur (sınırlama yok; her sayfa istenen DPI'de render edilip oluşturulur).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Ayrıca Bakınız
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
