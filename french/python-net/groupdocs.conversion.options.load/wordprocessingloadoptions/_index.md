---
title: "Classe WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Fournit des options pour charger des documents WordProcessing."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Fournit des options pour charger des documents WordProcessing.

Pipeline de traitement des polices :

Phase 1 - Substitution de police (pendant le chargement du document):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Phase 2 - Remplacement de police (après le chargement du document):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

Le type WordProcessingLoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Initialise une nouvelle instance de [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

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
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | La propriété auto_detect_rtl_direction détermine si les paragraphes et les runs contenant principalement du texte de droite à gauche ont leurs indicateurs bidi réparés avant la conversion. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Les options de signets. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Le drapeau indiquant si les propriétés de document intégrées sont effacées lors du chargement d'un document WordProcessing. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | La propriété ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | Le mode d'affichage des commentaires spécifie comment les commentaires doivent être affichés dans le document de sortie. La valeur par défaut est `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | La propriété implémente [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). La valeur par défaut est False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | Le drapeau convert_owner indique s'il faut convertir le propriétaire du document. La valeur par défaut est True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | La police par défaut pour un document WordProcessing. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | La profondeur des options de chargement du conteneur de document. La valeur par défaut est 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | La propriété embed_true_type_fonts détermine si les polices TrueType sont incorporées dans le document de sortie. La valeur par défaut est True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | La propriété active la substitution automatique des polices manquantes basée sur le FontConfig du système. La valeur par défaut est False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | Le drapeau qui active la substitution automatique des polices manquantes basée sur FontInfo dans le document. Valeur par défaut : False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | La propriété indique si les polices manquantes sont automatiquement substituées en fonction du nom de la police. Valeur par défaut : False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | Les substituts de police utilisés lors de la conversion d'un document WordProcessing. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Les transformations de police appliquées après le chargement du document et la substitution de police sont terminées, permettant la modification de toutes les polices du document, y compris celles chargées avec succès. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Le type de fichier du document d'entrée. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | La propriété hide_word_tracked_changes masque le balisage et le suivi des modifications pour les documents Word. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | Les options de césure pour les documents WordProcessing. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | La propriété keep_date_field_original_value détermine si la valeur originale d'un champ de date est conservée. La valeur par défaut est False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Les paramètres de marge. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | Le drapeau de génération de numérotation de page pour le document converti (valeur par défaut : False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | Le mot de passe pour déprotéger un document protégé. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | Le drapeau indiquant si la structure du document doit être conservée lors de la conversion en PDF (la valeur par défaut est False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | La propriété indique si les champs de formulaire Microsoft Word sont conservés en tant que champs de formulaire dans le PDF résultant ou convertis en texte. La valeur par défaut est False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | Le nom complet du commentateur est affiché dans les commentaires lorsqu'il est réglé sur True. La valeur par défaut est False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | Les paramètres de taille pour le document WordProcessing ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | Le drapeau qui détermine si les ressources externes sont ignorées lors du chargement d'un document. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | L'option de mettre à jour les champs après le chargement. Valeur par défaut : False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | La mise en page est mise à jour après le chargement. Valeur par défaut : False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | La propriété indique s'il faut utiliser un formateur de texte pour un affichage de crénage amélioré. La valeur par défaut est False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | Les ressources sur liste blanche pour le chargement de contenu externe, implémentant [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Exemple

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Guides de tâches qui utilisent `WordProcessingLoadOptions` :

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Voir aussi
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
