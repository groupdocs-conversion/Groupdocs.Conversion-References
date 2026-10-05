---
title: "skip_external_resources Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Eigenschaft gibt an, ob externe Ressourcen geladen werden."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/
is_root: false
weight: 2080
---


## skip_external_resources property

Die Eigenschaft gibt an, ob externe Ressourcen geladen werden.

Wenn True, werden alle externen Ressourcen nicht geladen, außer denen in der Liste [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). Standardwert ist True.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Siehe auch
* class [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/)
