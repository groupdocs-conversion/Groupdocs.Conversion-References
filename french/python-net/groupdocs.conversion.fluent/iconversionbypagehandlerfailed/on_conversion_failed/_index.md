---
title: "méthode on_conversion_failed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre un rappel à invoquer lorsqu’une conversion de page échoue."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Enregistre un rappel à invoquer lorsqu’une conversion de page échoue.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Une action pour gérer l'échec, recevant le contexte de page convertie et l'exception qui a causé l'échec. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Voir aussi
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
