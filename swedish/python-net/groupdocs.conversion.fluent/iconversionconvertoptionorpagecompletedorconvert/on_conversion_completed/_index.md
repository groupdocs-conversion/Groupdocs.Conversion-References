---
title: "on_conversion_completed‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Ta emot konverterad sidström."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Ta emot konverterad sidström. Kommer endast att avfyras om `ConvertTo(convertedStreamProvider)` är inställd.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Leverantör av konverterad sidström converted_page_stream arg1arg1: `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### Se även
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
