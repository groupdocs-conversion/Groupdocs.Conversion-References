---
title: "Klassen FontTransformation"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Beskriver konfiguration för teckensnittstransformation inklusive teckensnittsattribut, tillämpad efter dokumentinläsning och teckensnittsersättning."
type: docs
url: /sv/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Beskriver konfiguration för teckensnittstransformation inklusive teckensnittsattribut, tillämpad efter dokumentinläsning och teckensnittsersättning.

Typen FontTransformation exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Skapar en teckensnittstransformation med exakt teckensnittsmatchning (storlek och stil måste matcha). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Skapar en teckensnittstransformation enbart efter namn, som matchar vilken storlek och stil som helst, där ersättningsteckensnittet behåller originalteckensnittets storlek och stil. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Skapar en teckensnittstransformation med flexibla matchningsalternativ. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestämmer om två objektinstanser är lika. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Fungerar som standard‑hashfunktion. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | Egenskapen indikerar om någon teckensnittsstorlek för det ursprungliga teckensnittsnamnet matchas (true) eller endast den exakta teckensnittsstorleken som anges i `OriginalFont` matchas (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | Egenskapen bestämmer om någon teckensnittsstil (fet, kursiv, understruken) för det ursprungliga teckensnittet matchas (True) eller den exakta teckensnittsstilen som anges i `OriginalFont` krävs (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | Den ursprungliga teckensnittsspecifikationen att matcha och ersätta. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | Ersättningsteckensnittsspecifikationen. |

### Se även
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
