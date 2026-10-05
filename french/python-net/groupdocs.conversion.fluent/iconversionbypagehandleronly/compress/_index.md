---
title: "méthode compress"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Compresse les résultats de conversion ; enregistrez un gestionnaire de flux compressé à l'étape d'entrée via IConversionSettings.withevents (paramètre OnCompressionCompleted) au lieu d'utiliser le fluide obsolète…"
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Compresse les résultats de la conversion ; enregistrez un gestionnaire de flux compressé à l’étape d’entrée via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (en définissant `OnCompressionCompleted`) au lieu d’utiliser la méthode de chaîne fluide obsolète.

```python
def compress(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Options de conversion de compression. |

**Returns:** Continuation that proceeds to `Convert`.

### Voir aussi
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
