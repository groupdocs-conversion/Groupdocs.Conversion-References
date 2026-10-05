---
title: "méthode with_events"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre les gestionnaires d'événements du cycle de vie de la conversion sur un sac ConversionEvents qui vit pendant toute la durée de vie du convertisseur et se déclenche à chaque exécution de conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Enregistre les gestionnaires d'événements du cycle de vie de la conversion sur un sac [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) qui vit pendant toute la durée de vie du convertisseur et se déclenche à chaque exécution de conversion.

Se situe au même stade d'entrée que [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Les appels multiples s'accumulent : le même sac interne est passé à chaque action `configure`, de sorte que les gestionnaires définis lors des appels précédents persistent sauf s'ils sont écrasés par un appel ultérieur.

```python
def with_events(self, configure):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Action qui modifie le sac d'événements. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Voir aussi
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
