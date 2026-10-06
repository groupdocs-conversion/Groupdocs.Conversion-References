---
title: "on_conversion_failed metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en sidkonvertering misslyckas."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registrerar en callback som ska anropas när en sidkonvertering misslyckas. Att anropa igen ersätter tidigare inställd hanterare.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Anropbar funktion som hanterar felet, tar emot den konverterade sidkontexten och undantaget som orsakade felet. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Se även
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
