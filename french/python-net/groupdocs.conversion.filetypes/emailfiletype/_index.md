---
title: "Classe EmailFileType"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définit les formats de fichiers e-mail utilisés par les applications de messagerie pour stocker les messages, pièces jointes, dossiers, carnets d'adresses et autres données."
type: docs
url: /fr/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

Définit les formats de fichiers e-mail utilisés par les applications de messagerie pour stocker les messages, pièces jointes, dossiers, carnets d'adresses et autres données.

Inclut les types de fichiers suivants :
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

En savoir plus sur les formats de courriel sur https://wiki.fileformat.com/email.

Le type EmailFileType expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | Initialise un nouveau EmailFileType pour la sérialisation. |

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
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches. En savoir plus sur ce format de fichier ici. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. La quasi-totalité des clients de messagerie prennent en charge ce format de fichier en raison de sa conformité à la norme RFC‑822 Internet Message Format. En savoir plus sur ce format de fichier ici. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les courriels. En savoir plus sur ce format de fichier ici. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker des informations de contact. Le format est largement utilisé pour l'échange de données entre les applications d'échange d'informations populaires. En savoir plus sur ce format de fichier ici. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | Le format de fichier MBox est un terme générique qui représente un conteneur pour une collection de messages électroniques. Les messages sont stockés à l'intérieur du conteneur avec leurs pièces jointes. En savoir plus sur ce format de fichier ici. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | Les fichiers avec l'extension .PST représentent les fichiers de stockage personnel Outlook (également appelés Personal Storage Table) qui stockent une variété d'informations utilisateur. En savoir plus sur ce format de fichier ici. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST ou fichiers de stockage hors ligne représentent les données de la boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale après enregistrement auprès du serveur Exchange via Microsoft Outlook. En savoir plus sur ce format de fichier ici. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | Un fichier avec l'extension .olm est un fichier Microsoft Outlook pour le système d'exploitation Mac. Un fichier OLM stocke des messages électroniques, des journaux, des données de calendrier et d'autres types de données d'application. Ceux-ci sont similaires aux fichiers PST utilisés par Outlook sur le système d'exploitation Windows. Cependant, les fichiers OLM créés par Outlook pour Mac ne peuvent pas être ouverts dans Outlook pour Windows. En savoir plus sur ce format de fichier ici. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | Le format de fichier ICS (iCalendar) est utilisé pour représenter et échanger des informations de calendrier et de planification telles que des événements, des tâches et des données de disponibilité. En savoir plus sur ce format de fichier ici. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Type de fichier inconnu (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Voir aussi
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
