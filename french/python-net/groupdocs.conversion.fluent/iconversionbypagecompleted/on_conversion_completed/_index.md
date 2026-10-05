---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Reçoit le flux de page converti."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Reçoit le flux de page converti. Ne sera déclenché que si `ConvertTo(convertedStreamProvider)` est défini.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Fournisseur de flux de page convertie. Le `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Voir aussi
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
