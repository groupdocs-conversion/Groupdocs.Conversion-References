---
title: "خاصية font_name_substitution_enabled"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تشير الخاصية إلى ما إذا كانت الخطوط المفقودة تُستبدل تلقائياً بناءً على اسم الخط."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

الخاصية تشير إلى ما إذا كانت الخطوط المفقودة تُستبدل تلقائيًا بناءً على اسم الخط. القيمة الافتراضية: False.

ملاحظة: ترتيب الاستبدال كما يلي:

- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_name_substitution_enabled(self):
    ...
@font_name_substitution_enabled.setter
def font_name_substitution_enabled(self, value):
    ...
```

### انظر أيضًا
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
