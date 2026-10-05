---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Recevoir le flux de page converti."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Reçoit le flux de page converti. Ne sera déclenché que si `ConvertTo(convertedStreamProvider)` est défini.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Fournisseur de flux de page converti converted_page_stream arg1arg1 : Le `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### Voir aussi
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
