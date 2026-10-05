---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre un rappel à invoquer lorsqu’une conversion de page se termine avec succès, en remplaçant tout gestionnaire précédemment défini lors de la ré‑invocation."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Enregistre un rappel à invoquer lorsqu’une conversion de page se termine avec succès, en remplaçant tout gestionnaire précédemment défini lors de la ré‑invocation.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Une action pour gérer l'achèvement, recevant le contexte de page convertie. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Voir aussi
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
