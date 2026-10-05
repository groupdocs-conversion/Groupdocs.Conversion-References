---
title: "CadLoadOptions‑Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Bietet Optionen zum Laden von CAD-Dokumenten."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/cadloadoptions/
is_root: false
weight: 60
---


## CadLoadOptions class

Bietet Optionen zum Laden von CAD-Dokumenten.

Der Typ CadLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/__init__/) | Initialisiert eine neue Instanz der [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)‑Klasse. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestimmt, ob zwei Objektinstanzen gleich sind. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als Standard‑Hash‑Funktion. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/background_color/) | Die Hintergrundfarbe. |
| [ctb_sources](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/ctb_sources/) | Die CTB-Quellen. |
| [draw_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_color/) | Die Vordergrundfarbe. |
| [draw_type](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_type/) | Der Zeichnungstyp. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/format/) | Der Dateityp des Eingabedokuments. |
| [layout_names](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) | Die zu konvertierenden Layoutnamen. |
| [layout_scope](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) | Der Layout‑Bereich, der bestimmt, welche Zeichenbereiche konvertiert werden. Standardmäßig ist [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), was die Konvertierung nicht einschränkt. Ignoriert, wenn [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) angegeben ist, weil explizite Layoutnamen immer Vorrang haben. Ein `None`‑Wert wird als [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) behandelt. |

### Siehe auch
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
