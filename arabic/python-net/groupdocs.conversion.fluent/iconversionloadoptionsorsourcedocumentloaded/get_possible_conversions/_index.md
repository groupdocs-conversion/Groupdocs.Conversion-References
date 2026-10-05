---
title: "طريقة get_possible_conversions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسترجع التحويلات الممكنة للمستند المصدر."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

يسترجع التحويلات الممكنة للمستند المصدر.

الكائن المرجع يوفر الوصول إلى جميع خيارات التحويل، بما في ذلك الصيغ الأولية والثانوية، ويتضمن بيانات التعريف حول ملف المصدر.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### مثال

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### انظر أيضًا
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
