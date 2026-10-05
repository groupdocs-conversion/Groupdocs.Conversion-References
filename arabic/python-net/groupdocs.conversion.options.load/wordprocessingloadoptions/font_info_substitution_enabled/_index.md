---
title: "خاصية font_info_substitution_enabled"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "العلم الذي يمكّن الاستبدال التلقائي للخطوط المفقودة بناءً على FontInfo في المستند."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

العلم الذي يتيح الاستبدال التلقائي للخطوط المفقودة بناءً على FontInfo في المستند. القيمة الافتراضية: False.

ملاحظة: ترتيب الاستبدال كما يلي:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_info_substitution_enabled(self):
    ...
@font_info_substitution_enabled.setter
def font_info_substitution_enabled(self, value):
    ...
```

### انظر أيضًا
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
