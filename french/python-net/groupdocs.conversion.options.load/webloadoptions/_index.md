---
title: "Classe WebLoadOptions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Fournit des options pour charger des documents web."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/webloadoptions/
is_root: false
weight: 550
---


## WebLoadOptions class

Fournit des options pour charger des documents web.

Le type WebLoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/__init__/) | Initialise une nouvelle instance de [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/). |

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
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | Le chemin/base URL pour le HTML. |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | L'action utilisée pour configurer les en-têtes de requête, où le premier paramètre est l'Uri. |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Le fournisseur d'identifiants pour l'Uri. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/custom_css_style/) | La propriété implémente [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | L'encodage à utiliser lors du chargement du document web. Si défini sur None, l'encodage sera déterminé à partir de l'attribut jeu de caractères du document. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/format/) | Le type de fichier du document d'entrée. |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | Le mode de rendu HTML contrôle la façon dont le contenu HTML est rendu. Valeur par défaut : AbsolutePositioning. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/margin_settings/) | Les paramètres de marge. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/orientation_settings/) | Les paramètres d'orientation. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_layout_options/) | Les options de mise en page utilisées lors du chargement des documents web. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_numbering/) | Le drapeau qui active ou désactive la génération de la numérotation des pages dans le document converti. Valeur par défaut : False. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | Le délai d'attente pour le chargement des ressources externes. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/size_settings/) | Les paramètres de taille. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/skip_external_resources/) | La propriété implémente [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | La propriété indique s'il faut utiliser le PDF pour la conversion (valeur par défaut : False). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/whitelisted_resources/) | La propriété des ressources autorisées implémente [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | Le niveau de zoom en pourcentage appliqué à la balise `<body>` du document avant la conversion, mettant à l'échelle l'apparence visuelle du document. |

### Voir aussi
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
