---
title: "get_possible_conversions metodu"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belge için olası dönüşümleri alır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Kaynak belge için olası dönüşümleri alır.

Dönen nesne, birincil ve ikincil formatlar dahil olmak üzere tüm dönüşüm seçeneklerine erişim sağlar ve kaynak dosya hakkında üst verileri içerir.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Örnek

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Ayrıca Bakınız
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
