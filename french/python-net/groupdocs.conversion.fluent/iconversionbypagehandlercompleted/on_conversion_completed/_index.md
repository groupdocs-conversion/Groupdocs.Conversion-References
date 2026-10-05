---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre un rappel à invoquer lorsqu’une conversion de page se termine avec succès."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Enregistre un rappel à invoquer lorsqu’une conversion de page se termine avec succès.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Une action pour gérer l'achèvement, recevant le contexte de page convertie. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Voir aussi
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
