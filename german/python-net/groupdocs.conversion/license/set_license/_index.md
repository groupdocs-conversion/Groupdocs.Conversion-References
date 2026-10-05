---
title: "set_license Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Wenden Sie eine Lizenz auf den aktuellen Prozess an."
type: docs
url: /de/python-net/groupdocs.conversion/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Wenden Sie eine Lizenz auf den aktuellen Prozess an.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| license_source |  | Entweder ein Zeichenketten‑Pfad zu einer ``.lic``‑Datei oder ein lesbares dateiähnliches Objekt, das die Lizenz‑Bytes liefert. Dateiähnliche Eingaben werden in eine temporäre Datei geschrieben, bevor sie an die Brücke übergeben werden. |

| Wirft | Beschreibung |
| :- | :- |
| `TypeError` | Falls ``license_source`` weder ein Zeichenketten‑Pfad noch ein lesbares dateiähnliches Objekt ist. |

### Siehe auch
* class [`License`](/conversion/python-net/groupdocs.conversion/license/)
