---
title: detect_numbering_with_whitespaces property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

The property allows specifying how numbered list items are recognized when a plain text document is converted. The default value is True.

If this option is set to False, the list recognition algorithm detects list paragraphs when list numbers end with either a dot, right bracket, or bullet symbols (such as "•", "*", "-" or "o").

If this option is set to True, whitespaces are also used as list number delimiters: the list recognition algorithm for Arabic‑style numbering (e.g., 1., 1.1.2.) uses both whitespaces and dot (".") symbols.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### See Also
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
