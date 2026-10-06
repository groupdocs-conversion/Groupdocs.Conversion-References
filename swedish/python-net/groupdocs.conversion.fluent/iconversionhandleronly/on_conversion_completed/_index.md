---
title: "on_conversion_completed‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | En åtgärd för att hantera slutförandet, tar emot konverteringskontexten. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Se även
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
