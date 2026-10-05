---
title: "classe EmailLoadOptions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Fournit des options pour charger des documents Email."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/emailloadoptions/
is_root: false
weight: 130
---


## EmailLoadOptions class

Fournit des options pour charger des documents Email.

Le type EmailLoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/__init__/) | Initialise une nouvelle instance de la classe [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/). |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/clone/) | Clone l'instance actuelle. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Détermine si deux instances d'objet sont égales. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Servit comme fonction de hachage par défaut. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/attachment_icons/) | La liste des icônes de pièces jointes, qui peut être personnalisée pour fournir des icônes spécifiques à différents types de fichiers. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owned/) | La propriété implémente [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). La valeur par défaut est True. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owner/) | La propriété convert_owner implémente [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). La valeur par défaut est True. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/custom_css_style/) | Le style CSS personnalisé, implémentant [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/default_font/) | La police par défaut pour un document e‑mail. Cette police sera utilisée si une police requise est manquante. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/depth/) | La profondeur des options de chargement du conteneur de documents. |
| [display_attachments](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_attachments/) | L'option d'afficher ou de masquer les pièces jointes dans l'en-tête. Par défaut : True. |
| [display_bcc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_bcc_email_address/) | L'option d'afficher ou de masquer l'adresse e-mail Bcc. Par défaut : False. |
| [display_cc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_cc_email_address/) | L'option d'afficher ou de masquer l'adresse e-mail "Cc", par défaut à False. |
| [display_email_addresses](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_email_addresses/) | L'option de contrôler si les adresses e-mail sont affichées à côté des noms. Par défaut : True. |
| [display_from_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_from_email_address/) | L'option d'afficher ou de masquer l'adresse e-mail "from". Par défaut : True. |
| [display_header](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_header/) | L'option d'afficher ou de masquer l'en-tête du courriel. Par défaut : True. |
| [display_sent](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_sent/) | L'option d'afficher ou de masquer la date/heure d'envoi dans l'en-tête. Par défaut : True. |
| [display_subject](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_subject/) | L'option d'afficher ou de masquer le sujet dans l'en-tête. Par défaut : True. |
| [display_to_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_to_email_address/) | L'option d'afficher ou de masquer l'adresse e-mail "to". Par défaut : True. |
| [field_text_map](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/field_text_map/) | Le mappage entre le message e-mail [`EmailField`](/conversion/python-net/groupdocs.conversion.options.load/emailfield/) et la représentation textuelle du champ. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/font_substitutes/) | La liste des substituts de police. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/format/) | Le type de fichier du document d'entrée. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/margin_settings/) | Les paramètres de marge. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/orientation_settings/) | Les paramètres d'orientation. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/page_layout_options/) | La propriété implémente [`IPageLayoutOptions.page_layout_options`](/conversion/python-net/groupdocs.conversion.options.load/ipagelayoutoptions/page_layout_options/). |
| [preserve_original_date](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/preserve_original_date/) | La propriété détermine s'il faut conserver la chaîne d'en-tête de date originale dans le message mail lors de l'enregistrement. La valeur par défaut est True. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/resource_loading_timeout/) | Le délai d'attente pour le chargement des ressources externes. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/size_settings/) | Les paramètres de taille de page pour l'opération de chargement d'e-mail. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/skip_external_resources/) | La propriété qui implémente [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [time_zone_offset](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/time_zone_offset/) | Le décalage UTC (Temps Universel Coordonné) pour les dates des messages. |
| [use_default_attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/use_default_attachment_icons/) | Le drapeau indiquant si les icônes de pièces jointes par défaut sont utilisées (par défaut True). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/whitelisted_resources/) | La propriété implémente [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Voir aussi
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
