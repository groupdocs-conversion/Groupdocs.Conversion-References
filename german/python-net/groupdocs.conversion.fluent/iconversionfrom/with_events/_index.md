---
title: "with_events Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriere Ereignis-Handler für den Lebenszyklus der Konvertierung in einem ConversionEvents‑Behälter, der für die Lebensdauer des Konverters existiert und bei jedem Konvertierungsvorgang ausgelöst wird."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Registrieren Sie Ereignishandler für den Konvertierungslebenszyklus in einem [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) Behälter, der für die Lebensdauer des Konverters existiert und bei jedem Konvertierungsvorgang ausgelöst wird.

Kann vor oder nach [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) aufgerufen werden.
Mehrere Aufrufe werden akkumuliert: Der gleiche interne Behälter wird an jede `configure`‑Aktion übergeben, sodass Handler, die in früheren Aufrufen gesetzt wurden, erhalten bleiben, es sei denn, sie werden durch einen späteren Aufruf überschrieben.

```python
def with_events(self, configure):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Aktion, die den Ereignis‑Behälter verändert. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### Siehe auch
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
