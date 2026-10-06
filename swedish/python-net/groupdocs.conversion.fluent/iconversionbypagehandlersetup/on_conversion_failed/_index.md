---
title: "on_conversion_failed metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en sidkonvertering misslyckas."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registrerar en återuppringning som ska anropas när en sidkonvertering misslyckas.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – en åtgärd för att hantera felet, som tar emot den konverterade sidkontexten och undantaget som orsakade felet. |

**Returns:** IConversionByPageHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Se även
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
