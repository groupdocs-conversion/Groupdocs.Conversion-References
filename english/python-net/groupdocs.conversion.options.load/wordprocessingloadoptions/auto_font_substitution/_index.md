---
title: auto_font_substitution property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_font_substitution/
is_root: false
weight: 40
---

## auto_font_substitution property


If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. If AutoFontSubstitution is enabled,
GroupDocs.Conversion evaluates all the related fields in FontInfo (Panose, Sig etc) for the missing font and finds the closest match among the available font sources.
Note that font substitution mechanism will override the DefaultFont in cases when FontInfo for the missing font is available in the document. The default value is True.
### Definition:
```python
@property
def auto_font_substitution(self):
    ...
@auto_font_substitution.setter
def auto_font_substitution(self, value):
    ...
```

### See Also
* module [`groupdocs.conversion.options.load`](../../)
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions)
