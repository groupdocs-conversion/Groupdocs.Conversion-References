---
title: "on_conversion_completed‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tar emot den konverterade dokumentströmmen och utlöses endast om ConvertTo(string fileName) eller ConvertTo(convertedStreamProvider) är angivet."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Tar emot den konverterade dokumentströmmen och utlöses endast om `ConvertTo(string fileName)` eller `ConvertTo(convertedStreamProvider)` är angivet.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Leverantör av konverterad dokumentström. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
