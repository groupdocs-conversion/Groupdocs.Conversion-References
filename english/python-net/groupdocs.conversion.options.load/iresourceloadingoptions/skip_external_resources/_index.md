---
title: skip_external_resources property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The property indicates whether external resources are loaded."
type: docs
url: /python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/
is_root: false
weight: 2010
---


## skip_external_resources property

The property indicates whether external resources are loaded.

If True, all external resources will not be loaded except those in [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) list. Default: True.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### See Also
* class [`IResourceLoadingOptions`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/)
