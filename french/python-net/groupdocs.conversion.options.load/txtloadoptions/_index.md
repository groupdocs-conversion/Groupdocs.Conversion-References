---
title: "classe TxtLoadOptions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Options pour charger des documents Txt."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Options pour charger des documents Txt.

Configuration de police pour le texte brut :

Comme les fichiers TXT ne contiennent pas d'informations de police, utilisez DefaultTextFont pour spécifier la police lors du rendu du contenu texte brut pendant la conversion.

Le type TxtLoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Initialise une nouvelle instance de [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

### Méthodes
| Méthode | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Détermine si deux instances d'objet sont égales. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Servit comme fonction de hachage par défaut. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | La police à utiliser lors du rendu du contenu texte brut pendant la conversion. Par défaut : Arial 10 pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | La propriété indique comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut. La valeur par défaut est True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | L'encodage utilisé lors du chargement d'un document Txt. Peut être None. La valeur par défaut est None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Le type de fichier du document d'entrée. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | L'option préférée pour la gestion des espaces en début de ligne. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | Les paramètres de marge, tels que définis par [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Les options de taille de page pour le chargement d'un document TXT. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | L'option préférée pour gérer les espaces de fin. La valeur par défaut est [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Voir aussi
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
