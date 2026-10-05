---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Konvertierten Seitenstrom empfangen."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Empfängt den konvertierten Seitenstrom. Wird nur ausgelöst, wenn `ConvertTo(convertedStreamProvider)` gesetzt ist.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Konvertierter Seitenstrom-Provider converted_page_stream arg1arg1: Der `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### Siehe auch
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
