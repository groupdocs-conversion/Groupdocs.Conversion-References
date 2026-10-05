---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre un rappel à invoquer lorsqu’une conversion de document se termine avec succès."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Enregistre un rappel à invoquer lorsqu’une conversion de document se termine avec succès.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Une action pour gérer la finalisation, en recevant le contexte de conversion. |

**Returns:** The flat handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Voir aussi
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
