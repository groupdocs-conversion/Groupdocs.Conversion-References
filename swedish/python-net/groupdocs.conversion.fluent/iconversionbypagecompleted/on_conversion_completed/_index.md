---
title: "on_conversion_completed‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tar emot den konverterade sidströmmen."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Tar emot den konverterade sidströmmen. Kommer endast att utlösas om `ConvertTo(convertedStreamProvider)` är inställd.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Leverantör av konverterad sidström. `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
