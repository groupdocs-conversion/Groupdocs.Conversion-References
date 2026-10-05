---
title: "Klasse TxtLoadOptions"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Optionen zum Laden von Txt-Dokumenten."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Optionen zum Laden von Txt-Dokumenten.

Schriftkonfiguration für Klartext:

Da TXT-Dateien keine Schriftinformationen enthalten, verwenden Sie DefaultTextFont, um die Schrift für die Darstellung des Klartextinhalts während der Konvertierung festzulegen.

Der Typ TxtLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Initialisiert eine neue Instanz von [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

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
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | Die Schrift, die bei der Darstellung von Klartextinhalt während der Konvertierung verwendet wird. Standard: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | Die Eigenschaft legt fest, wie nummerierte Listenelemente erkannt werden, wenn ein Klartextdokument konvertiert wird. Der Standardwert ist `True`. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Die beim Laden eines Txt-Dokuments verwendete Kodierung. Kann `None` sein. Standard ist `None`. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Der Dateityp des Eingabedokuments. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | Die bevorzugte Option zur Behandlung von führenden Leerzeichen. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | Die Rand‑Einstellungen, wie von [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) definiert. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Die Optionen für die Seitengröße beim Laden eines TXT-Dokuments. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | Die bevorzugte Option zur Behandlung von nachgestellten Leerzeichen. Der Standardwert ist [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Siehe auch
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
