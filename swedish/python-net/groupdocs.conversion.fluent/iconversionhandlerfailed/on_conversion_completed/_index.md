---
title: "on_conversion_completed‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt. Återanrop ersätter tidigare inställd hanterare.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Anropbar som hanterar slutförandet och tar emot konverteringskontexten. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Se även
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
