---
title: "Metode get_possible_conversions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengambil konversi yang mungkin untuk dokumen sumber."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/get_possible_conversions/
is_root: false
weight: 1010
---


## get_possible_conversions

Mengambil konversi yang mungkin untuk dokumen sumber.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** A `GroupDocs.Conversion.Fluent.PossibleConversions` object containing the source description and a collection of conversion options.

### Contoh

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Lihat Juga
* class [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/)
