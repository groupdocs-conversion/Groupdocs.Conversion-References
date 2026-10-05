---
title: "méthode compress"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Compresse les résultats de conversion et renvoie une continuation qui poursuit la conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Compresse les résultats de conversion et renvoie une continuation qui poursuit vers `Convert`.

Enregistrez un gestionnaire de flux compressé à l'étape d'entrée via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (définissant `OnCompressionCompleted`) plutôt que d'utiliser la méthode de chaîne fluide obsolète sur l'interface renvoyée.

```python
def compress(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Options de conversion de compression. |

**Returns:** Continuation that proceeds to `Convert`.

### Voir aussi
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
