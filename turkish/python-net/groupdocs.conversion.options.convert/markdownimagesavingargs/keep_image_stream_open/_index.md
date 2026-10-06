---
title: "keep_image_stream_open özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bu özellik, dönüştürmeden sonra dönüştürücünün görüntü akışını açık tutup tutmayacağını belirler."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

Bu özellik, dönüştürmeden sonra dönüştürücünün görüntü akışını açık tutup tutmayacağını belirler.

False (varsayılan) olduğunda, dönüştürücü yazdıktan sonra [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) öğesini kapatır — diske yazdırılması gereken `io.RawIOBase` değişiklikleri için deyimsel bir davranıştır. True olarak ayarlandığında, dönüşüm tamamlandıktan sonra akış açık kalır (kendi kendinize okumak istediğiniz bir `io.BytesIO` için tipiktir); ardından çağıran, kapatmayı kendisi üstlenir.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Ayrıca Bakınız
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
