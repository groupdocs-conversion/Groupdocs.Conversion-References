---
title: font_name_substitution_enabled property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2120
---


## font_name_substitution_enabled property

The property that enables automatic substitution of missing fonts based on the font name. Default: False.

Note: The order of substitution is as follows:

1) Automatically substitute missing fonts based on font name (if enabled).
2) Automatically substitute missing fonts based on FontConfig (if enabled).
3) Substitute missing fonts based on FontSubstitutes (if set).
4) Automatically substitute missing fonts based on FontInfo (if enabled).
5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_name_substitution_enabled(self):
    ...
@font_name_substitution_enabled.setter
def font_name_substitution_enabled(self, value):
    ...
```

### See Also
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
