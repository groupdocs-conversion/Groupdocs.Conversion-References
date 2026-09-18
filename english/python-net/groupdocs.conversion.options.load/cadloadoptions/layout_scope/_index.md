---
title: layout_scope property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The layout scope that determines which drawing spaces are converted."
type: docs
url: /python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

The layout scope that determines which drawing spaces are converted. Defaults to [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), which does not restrict the conversion. Ignored when [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) is supplied, because explicit layout names always win. A `None` value is treated as [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

If the scope selects none of the sheets offered by a drawing, the conversion fails with `InvalidLoadOptionsException`, which names the scope and the available sheets instead of rendering the excluded spaces. A drawing that offers no sheet at all is unaffected and still converts as a single unit. Not honoured when converting to PDF/UA-1, for the reason given on [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### See Also
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
