---
title: "detect_numbering_with_whitespaces özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bu özellik, düz metin belgesi dönüştürüldüğünde numaralı liste öğelerinin nasıl tanındığını belirtir."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

Bu özellik, bir düz metin belgesi dönüştürüldüğünde numaralı liste öğelerinin nasıl tanındığını belirtir. Varsayılan değer True'tir.

Bu seçenek False olarak ayarlanırsa, liste tanıma algoritması, liste numaraları bir nokta, sağ köşeli parantez veya madde işareti (örneğin "•", "*", "-" veya "o") ile bittiğinde liste paragraflarını algılar.

Bu seçenek True olarak ayarlanırsa, boşluk karakterleri de liste numarası ayırıcıları olarak kullanılır: Arap‑stili numaralandırma (ör. 1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (".") işaretlerini kullanır.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Ayrıca Bakınız
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
