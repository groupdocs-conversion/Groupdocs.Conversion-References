---
title: "on_conversion_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Ontvangt de geconverteerde documentstroom."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Ontvangt de geconverteerde documentstroom. Wordt alleen aangeroepen wanneer `ConvertTo(string fileName)` of `ConvertTo(convertedStreamProvider)` is geconfigureerd.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Provider voor de geconverteerde documentstroom. De provider ontvangt een `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### Zie ook
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
