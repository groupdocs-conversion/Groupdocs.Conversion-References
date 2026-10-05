---
title: "FontTransformation Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Beschreibt die Konfiguration der Schriftart-Transformation einschließlich Schriftart-Attribute, die nach dem Laden des Dokuments und der Schriftart-Substitution angewendet werden."
type: docs
url: /de/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Beschreibt die Konfiguration der Schriftart-Transformation einschließlich Schriftart-Attribute, die nach dem Laden des Dokuments und der Schriftart-Substitution angewendet werden.

Der FontTransformation Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Erstellt eine Schriftarttransformation mit exakter Schriftartübereinstimmung (Größe und Stil müssen übereinstimmen). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Erstellt eine Schriftarttransformation nur nach Namen, die jede Größe und jeden Stil abgleicht, wobei die Ersatzschriftart die Größe und den Stil der Originalschriftart beibehält. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Erstellt eine Schriftarttransformation mit flexiblen Übereinstimmungsoptionen. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestimmt, ob zwei Objektinstanzen gleich sind. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als Standard‑Hash‑Funktion. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | Die Eigenschaft gibt an, ob jede Schriftgröße für den Originalschriftartnamen abgeglichen wird (true) oder nur die exakt in `OriginalFont` angegebene Schriftgröße abgeglichen wird (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | Die Eigenschaft bestimmt, ob jeder Schriftstil (fett, kursiv, unterstrichen) der Originalschriftart abgeglichen wird (True) oder der exakt in `OriginalFont` angegebene Schriftstil erforderlich ist (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | Die Originalschriftart‑Spezifikation zum Abgleichen und Ersetzen. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | Die Ersatzschriftart‑Spezifikation. |

### Siehe auch
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
