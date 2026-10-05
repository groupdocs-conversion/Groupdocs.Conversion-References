---
title: "metode get_all_possible_conversions"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mendapatkan semua konversi yang didukung."
type: docs
url: /id/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Mendapatkan semua konversi yang didukung.

Pelajari lebih lanjut tentang konversi yang didukung:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Contoh

```python
from groupdocs.conversion import Converter

# Dapatkan semua konversi yang mungkin
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Lihat Juga
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
