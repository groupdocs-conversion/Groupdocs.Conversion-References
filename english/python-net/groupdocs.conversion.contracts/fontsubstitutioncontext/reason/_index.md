---
title: reason property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The substitution message exactly as reported by the conversion pipeline, verbatim and unparsed."
type: docs
url: /python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
is_root: false
weight: 2020
---


## reason property

The substitution message exactly as reported by the conversion pipeline, verbatim and unparsed.

For documents that expose font names structurally this may be None (use [`FontSubstitutionContext.original_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) / [`FontSubstitutionContext.substitute_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/)); for others it carries the full human-readable description, which names both the missing and the substitute font.

### Definition:
```python
@property
def reason(self):
    ...
```

### See Also
* class [`FontSubstitutionContext`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/)
