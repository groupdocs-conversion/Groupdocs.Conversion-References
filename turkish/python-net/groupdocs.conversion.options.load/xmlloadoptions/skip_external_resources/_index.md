---
title: "skip_external_resources özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bu özellik dış kaynakların yüklenip yüklenmediğini gösterir."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/
is_root: false
weight: 2080
---


## skip_external_resources property

Bu özellik dış kaynakların yüklenip yüklenmediğini gösterir.

True ise, [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) listesinde bulunanlar dışındaki tüm dış kaynaklar yüklenmez. Varsayılan değer True'tir.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Ayrıca Bakınız
* class [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/)
