---
title: "méthode on_conversion_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Reçoit le flux du document converti et n'est déclenché que si ConvertTo(string fileName) ou ConvertTo(convertedStreamProvider) est défini."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Reçoit le flux du document converti et n'est déclenché que si `ConvertTo(string fileName)` ou `ConvertTo(convertedStreamProvider)` est défini.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Fournisseur de flux du document converti. |

**Returns:** Interface to continue conversion building.

### Voir aussi
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
