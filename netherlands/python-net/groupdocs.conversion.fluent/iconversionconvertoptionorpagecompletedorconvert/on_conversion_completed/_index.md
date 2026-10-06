---
title: "on_conversion_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Ontvang geconverteerde paginastroom."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Ontvang de geconverteerde paginastroom. Wordt alleen geactiveerd als `ConvertTo(convertedStreamProvider)` is ingesteld.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Provider van geconverteerde paginastroom converted_page_stream arg1arg1: De `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### Zie ook
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
