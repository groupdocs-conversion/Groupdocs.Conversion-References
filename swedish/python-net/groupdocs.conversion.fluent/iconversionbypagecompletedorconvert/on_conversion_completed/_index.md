---
title: "on_conversion_completed‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tar emot den konverterade sidströmmen."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Tar emot den konverterade sidströmmen. Utlöses endast om `ConvertTo(convertedStreamProvider)` är angivet.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Leverantör av konverterad sidström. Leverantören tar emot ett `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
