---
title: "skip_external_resources свойство"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Свойство указывает, загружаются ли внешние ресурсы."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/
is_root: false
weight: 2080
---


## skip_external_resources property

Свойство указывает, загружаются ли внешние ресурсы.

Если True, все внешние ресурсы не будут загружаться, за исключением тех, что находятся в списке [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). По умолчанию True.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### См. также
* class [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/)
