---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre un rappel à invoquer lorsqu’une conversion de document se termine avec succès."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Enregistre un rappel à invoquer lorsqu’une conversion de document se termine avec succès. Ré‑invoquer remplace tout gestionnaire précédemment défini.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Objet appelable qui gère l'achèvement, en recevant le contexte de conversion. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Voir aussi
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
