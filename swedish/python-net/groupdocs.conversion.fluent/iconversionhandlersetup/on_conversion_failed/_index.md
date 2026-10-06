---
title: "on_conversion_failed metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Anropbar som hanterar felet, tar emot konverteringskontexten och undantaget som orsakade felet. |

**Returns:** IConversionHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Se även
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
