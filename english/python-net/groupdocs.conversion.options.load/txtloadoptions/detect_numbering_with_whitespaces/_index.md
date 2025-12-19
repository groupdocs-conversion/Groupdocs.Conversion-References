---
title: detect_numbering_with_whitespaces property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 40
---

## detect_numbering_with_whitespaces property


Allows to specify how numbered list items are recognized when plain text document is converted.
The default value is true.

### Remarks 


If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with
either dot, right bracket or bullet symbols (such as "•", "*", "-" or "o").


 If this option is set to true, whitespaces are also used as list number delimiters:
list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols.
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
* module [`groupdocs.conversion.options.load`](../../)
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions)
