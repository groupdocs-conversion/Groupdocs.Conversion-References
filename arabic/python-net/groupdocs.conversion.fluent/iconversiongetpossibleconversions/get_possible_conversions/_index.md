---
title: "طريقة get_possible_conversions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسترجع التحويلات الممكنة للمستند المصدر."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/get_possible_conversions/
is_root: false
weight: 1010
---


## get_possible_conversions

يسترجع التحويلات الممكنة للمستند المصدر.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** A `GroupDocs.Conversion.Fluent.PossibleConversions` object containing the source description and a collection of conversion options.

### مثال

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### انظر أيضًا
* class [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/)
