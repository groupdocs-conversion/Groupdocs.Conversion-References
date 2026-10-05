---
title: "Classe ProjectManagementFileType"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définit les formats de fichiers Project qui sont créés par des logiciels de gestion de projet tels que Microsoft Project, Primavera P6, etc."
type: docs
url: /fr/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Définit les formats de fichiers Project qui sont créés par des logiciels de gestion de projet tels que Microsoft Project, Primavera P6, etc.

Un fichier de projet est une collection de tâches, de ressources et de leur planification pour obtenir un résultat mesurable sous forme d'un produit ou d'un service. Documents de gestion de projet. Inclut les types de fichiers suivants : [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). En savoir plus sur les formats de gestion de projet ici : https://wiki.fileformat.com/project-management.

Le type ProjectManagementFileType expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | Initialise un ProjectManagementFileType pour la sérialisation. |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | Les fichiers modèle Microsoft Project contiennent des informations de base et une structure ainsi que des paramètres de document pour créer des fichiers .MPP. En savoir plus sur ce format de fichier ici. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP est un fichier de données Microsoft Project qui stocke les informations liées à la gestion de projet de manière intégrée. En savoir plus sur ce format de fichier ici. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange File Format est un format de fichier ASCII destiné au transfert d'informations de projet entre Microsoft Project (MSP) et d'autres applications qui prennent en charge le format de fichier MPX telles que Primavera Project Planner, Sciforma et Timerline Precision Estimating. En savoir plus sur ce format de fichier ici. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | Le format de fichier XER est un format de fichier projet propriétaire utilisé par l'application de planification et de gestion de projet Primavera P6. En savoir plus sur ce format de fichier ici. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Type de fichier inconnu (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Voir aussi
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
