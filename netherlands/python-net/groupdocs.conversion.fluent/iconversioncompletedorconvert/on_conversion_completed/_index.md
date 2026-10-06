---
title: "on_conversion_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Ontvangt de geconverteerde documentstroom."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Ontvangt de geconverteerde documentstream. Wordt alleen geactiveerd als `ConvertTo(string fileName)` of `ConvertTo(convertedStreamProvider)` is ingesteld.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Provider van de geconverteerde documentstroom (`ConvertedContext`). |

**Returns:** Interface to continue conversion building.

### Zie ook
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
