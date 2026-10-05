---
title: "Classe FinanceFileType"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définit les types de documents financiers."
type: docs
url: /fr/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Définit les types de documents financiers.

Inclut les types suivants : [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). En savoir plus sur les formats financiers ici : https://docs.fileformat.com/finance/.

Le type FinanceFileType expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Initialise un FinanceFileType pour la sérialisation. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Compare l'objet actuel à un autre. (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implémente la comparaison d'égalité définie par [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Obtient le FileType pour l'extension de fichier fournie. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Renvoie le FileType pour le file_name spécifié. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Renvoie le FileType pour le flux de document fourni. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Fournit la fonction de hachage par défaut. (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Représentation sous forme de chaîne du type de fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | La description du type de fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | L'extension du fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | La famille du fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Le format du fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Champs
| Champ | Description |
| :- | :- |
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL est une norme internationale ouverte pour le reporting d’entreprise numérique largement utilisée dans le monde. C’est un langage basé sur XML qui utilise des éléments XBRL, appelés balises, pour décrire chaque élément de données commerciales afin de formuler des données pour le tri et l’analyse des rapports. En savoir plus sur ce format de fichier ici. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | Dans le iXBRL, le contenu de XBRL est encapsulé dans un format de fichier xHTML qui utilise des balises XML. Comme XBRL, il constitue l’élément racine des fichiers iXBRL. Le format XHTML représente son contenu comme une collection de différents types de documents et modules. Tous les fichiers en XHTML sont basés sur le format de fichier XML et respectent les normes de documents XML. En savoir plus sur ce format de fichier ici. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) est un format de flux de données pour l’échange d’informations financières qui a évolué à partir du Open Financial Connectivity (OFC) de Microsoft et des formats de fichiers Open Exchange d’Intuit. En savoir plus sur ce format de fichier ici. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Type de fichier inconnu (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Voir aussi
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
