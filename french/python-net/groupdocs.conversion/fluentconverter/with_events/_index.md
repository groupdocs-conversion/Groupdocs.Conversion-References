---
title: "méthode with_events"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Démarre une chaîne fluide à l'étape d'entrée avec des gestionnaires d'événements du cycle de vie de la conversion."
type: docs
url: /fr/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Démarre une chaîne fluide à l'étape d'entrée avec des gestionnaires d'événements du cycle de vie de la conversion.

```python
def with_events(cls, configure):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Callable qui modifie le sac `ConversionEvents`. |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### Voir aussi
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
