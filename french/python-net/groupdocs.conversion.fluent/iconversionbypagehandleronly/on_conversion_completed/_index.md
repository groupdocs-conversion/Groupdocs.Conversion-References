---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre un rappel à invoquer lorsqu’une conversion de page se termine avec succès."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/
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
| on_completed | `Action[ConvertedPageContext]` | Objet appelable qui gère l'achèvement, en recevant le contexte de page convertie. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Voir aussi
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
