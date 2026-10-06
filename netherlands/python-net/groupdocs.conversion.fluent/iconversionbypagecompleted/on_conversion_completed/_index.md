---
title: "on_conversion_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Ontvangt de geconverteerde paginastroom."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Ontvangt de geconverteerde paginastroom. Wordt alleen geactiveerd als `ConvertTo(convertedStreamProvider)` is ingesteld.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Provider van de geconverteerde paginastroom. De `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Zie ook
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
