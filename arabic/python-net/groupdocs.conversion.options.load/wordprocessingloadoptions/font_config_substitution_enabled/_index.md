---
title: "خاصية font_config_substitution_enabled"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "الخاصية تمكّن الاستبدال التلقائي للخطوط المفقودة بناءً على FontConfig النظامي."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

الخاصية تمكّن الاستبدال التلقائي للخطوط المفقودة بناءً على FontConfig النظام. القيمة الافتراضية هي False.

ملاحظة: ترتيب الاستبدال كما يلي:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_config_substitution_enabled(self):
    ...
@font_config_substitution_enabled.setter
def font_config_substitution_enabled(self, value):
    ...
```

### انظر أيضًا
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
