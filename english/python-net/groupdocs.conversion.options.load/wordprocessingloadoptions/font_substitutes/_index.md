---
title: font_substitutes property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2130
---


## font_substitutes property

The font substitutes used when converting a WordProcessing document.

Note: The order of substitution is as follows:

1) Automatically substitute missing fonts based on font name (if enabled).

2) Automatically substitute missing fonts based on FontConfig (if enabled).

3) Substitute missing fonts based on FontSubstitutes (if set).

4) Automatically substitute missing fonts based on FontInfo (if enabled).

5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_substitutes(self):
    ...
@font_substitutes.setter
def font_substitutes(self, value):
    ...
```

### See Also
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
