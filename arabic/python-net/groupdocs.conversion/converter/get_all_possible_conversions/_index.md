---
title: "طريقة get_all_possible_conversions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يحصل على جميع التحويلات المدعومة."
type: docs
url: /ar/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

يحصل على جميع التحويلات المدعومة.

تعرف على المزيد حول التحويلات المدعومة:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### مثال

```python
from groupdocs.conversion import Converter

# استرجاع جميع التحويلات الممكنة
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### انظر أيضًا
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
