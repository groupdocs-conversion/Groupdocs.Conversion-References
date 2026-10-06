---
title: "on_conversion_completed‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en sidkonvertering slutförs framgångsrikt."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registrerar en återuppringning som ska anropas när en sidkonvertering slutförs framgångsrikt.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | En åtgärd för att hantera slutförandet, som tar emot den konverterade sidkontexten. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Se även
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
