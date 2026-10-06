---
title: "set_license metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Applicera en licens på den aktuella processen."
type: docs
url: /sv/python-net/groupdocs.conversion/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Applicera en licens på den aktuella processen.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| license_source |  | Antingen en strängsökväg till en ``.lic``‑fil eller ett läsbart fil‑likt objekt som levererar licensbytarna. Fil‑lika indata skrivs till en temporär fil innan de skickas till bryggan. |

| Kastar | Beskrivning |
| :- | :- |
| `TypeError` | Om ``license_source`` varken är en strängsökväg eller ett läsbart fil‑liknande objekt. |

### Se även
* class [`License`](/conversion/python-net/groupdocs.conversion/license/)
