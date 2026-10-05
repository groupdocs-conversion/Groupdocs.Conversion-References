---
title: "FontTransformation classe"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Décrit la configuration de transformation de police incluant les attributs de police, appliquée après le chargement du document et la substitution de police."
type: docs
url: /fr/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Décrit la configuration de transformation de police incluant les attributs de police, appliquée après le chargement du document et la substitution de police.

Le type FontTransformation expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Crée une transformation de police avec une correspondance exacte de la police (la taille et le style doivent correspondre). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Crée une transformation de police uniquement par nom, en faisant correspondre n'importe quelle taille et tout style, la police de remplacement conservant la taille et le style de la police d'origine. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Crée une transformation de police avec des options de correspondance flexibles. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Détermine si deux instances d'objet sont égales. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Servit comme fonction de hachage par défaut. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | La propriété indique si n'importe quelle taille de police pour le nom de police d'origine est correspondante (true) ou si seule la taille exacte spécifiée dans `OriginalFont` est correspondante (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | La propriété détermine si n'importe quel style de police (gras, italique, souligné) de la police d'origine est correspondante (True) ou si le style exact spécifié dans `OriginalFont` est requis (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | La spécification de la police d'origine à correspondre et à remplacer. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | La spécification de la police de remplacement. |

### Voir aussi
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
