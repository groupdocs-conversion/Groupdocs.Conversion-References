---
title: "طريقة get_possible_conversions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسترجع التحويلات الممكنة للمستند المصدر."
type: docs
url: /ar/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

يسترجع التحويلات الممكنة للمستند المصدر.

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### مثال

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### انظر أيضًا
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
