---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Reçoit le flux du document converti."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Reçoit le flux du document converti. Il est invoqué uniquement lorsque `ConvertTo(string fileName)` ou `ConvertTo(convertedStreamProvider)` a été configuré.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Fournisseur du flux de document converti. Le fournisseur reçoit un `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### Voir aussi
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
