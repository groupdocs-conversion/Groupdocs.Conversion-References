---
title: "FontTransformation‑klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Beschrijft configuratie voor lettertype-transformatie, inclusief lettertype-attributen, toegepast na het laden van het document en de lettertypevervanging."
type: docs
url: /nl/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Beschrijft configuratie voor lettertype-transformatie, inclusief lettertype-attributen, toegepast na het laden van het document en de lettertypevervanging.

Het type FontTransformation bevat de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Maakt een lettertype‑transformatie met exacte overeenkomst van lettertype (grootte en stijl moeten overeenkomen). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Maakt een lettertype‑transformatie alleen op basis van naam, waarbij elke grootte en stijl overeenkomt, en waarbij het vervangende lettertype de grootte en stijl van het oorspronkelijke lettertype behoudt. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Maakt een lettertype‑transformatie met flexibele overeenstemmingsopties. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bepaalt of twee objectinstellingen gelijk zijn. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als de standaard hash-functie. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | De eigenschap geeft aan of elke lettertypegrootte voor de oorspronkelijke lettertype‑naam wordt gematcht (true) of alleen de exacte lettertypegrootte die is opgegeven in `OriginalFont` wordt gematcht (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | De eigenschap bepaalt of elke lettertype‑stijl (vet, cursief, onderstrepen) van het oorspronkelijke lettertype wordt gematcht (True) of de exacte lettertype‑stijl die is opgegeven in `OriginalFont` vereist is (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | De specificatie van het oorspronkelijke lettertype om te matchen en te vervangen. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | De specificatie van het vervangende lettertype. |

### Zie ook
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
