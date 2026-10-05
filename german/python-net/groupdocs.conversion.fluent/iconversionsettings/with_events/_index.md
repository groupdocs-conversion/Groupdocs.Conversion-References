---
title: "with_events Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert Ereignishandler für den Konvertierungslebenszyklus in einem ConversionEvents‑Behälter, der für die Lebensdauer des Konverters existiert und bei jedem Konvertierungslauf ausgelöst wird."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Registriert Ereignishandler für den Konvertierungs-Lebenszyklus in einem [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) Behälter, der für die Lebensdauer des Konverters existiert und bei jedem Konvertierungslauf ausgelöst wird.

Befindet sich in derselben Einstiegsebene wie [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Mehrere Aufrufe akkumulieren: derselbe interne Behälter wird an jede `configure`‑Aktion übergeben, sodass Handler, die in früheren Aufrufen gesetzt wurden, erhalten bleiben, sofern sie nicht von einem späteren Aufruf überschrieben werden.

```python
def with_events(self, configure):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Aktion, die den Ereignis‑Behälter verändert. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Siehe auch
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
