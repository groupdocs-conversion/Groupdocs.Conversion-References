---
title: "with_events Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Startet eine fluente Kette in der Einstiegsebene mit Ereignis-Handlern des Konvertierungslebenszyklus."
type: docs
url: /de/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Startet eine fluente Kette in der Einstiegsebene mit Ereignis-Handlern des Konvertierungslebenszyklus.

```python
def with_events(cls, configure):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Aufrufbare (Callable), die den `ConversionEvents`‑Behälter verändert. |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### Siehe auch
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
