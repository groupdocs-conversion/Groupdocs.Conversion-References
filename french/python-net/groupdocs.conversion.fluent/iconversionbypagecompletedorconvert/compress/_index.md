---
title: "méthode compress"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Compresse les résultats de la conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/compress/
is_root: false
weight: 1010
---


## compress {#options}

Compresse les résultats de la conversion.

Enregistrez un gestionnaire de flux compressé à l'étape d'entrée via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (en définissant `OnCompressionCompleted`) plutôt que via la méthode de chaîne fluide obsolète sur l'interface retournée.

```python
def compress(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Options de conversion de compression. |

**Returns:** Continuation that proceeds to `Convert`.

### Voir aussi
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
