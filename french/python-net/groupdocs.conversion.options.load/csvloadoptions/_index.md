---
title: "Classe CsvLoadOptions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Fournit des options pour charger des documents CSV."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/csvloadoptions/
is_root: false
weight: 80
---


## CsvLoadOptions class

Fournit des options pour charger des documents CSV.

Le type CsvLoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/__init__/) | Initialise une nouvelle instance de [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/). |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Clone l'instance actuelle. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Détermine si deux instances d'objet sont égales. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Servit comme fonction de hachage par défaut. (hérité de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_built_in_document_properties/) | La propriété supprime les propriétés de métadonnées intégrées du document. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_custom_document_properties/) | La propriété qui supprime les propriétés de métadonnées personnalisées du document. |
| [convert_date_time_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_date_time_data/) | La propriété indique si la chaîne du fichier est convertie en date. La valeur par défaut est True. |
| [convert_numeric_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_numeric_data/) | Le drapeau indiquant si les chaînes du fichier sont converties en valeurs numériques. La valeur par défaut est True. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owned/) | L'option permet de contrôler si les documents détenus dans le conteneur de documents doivent être convertis. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owner/) | L'option de contrôle de la conversion du conteneur de documents lui‑même ; si true, le conteneur sera le premier document converti. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/default_font/) | La police à utiliser si une police est manquante. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/depth/) | L'option de profondeur contrôle le nombre de niveaux de profondeur à convertir. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/encoding/) | L'encodage utilisé pour les fichiers CSV. La valeur par défaut est `Encoding.Default`. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/font_substitutes/) | Les substituts de police. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/format/) | Le type de fichier du document d'entrée. |
| [has_formula](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/has_formula/) | La propriété indique si le texte est une formule lorsqu'il commence par "=". |
| [is_multi_encoded](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/is_multi_encoded/) | La propriété indique si le fichier contient plusieurs encodages. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/margin_settings/) | Les paramètres de marge de page. |
| [separator](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/separator/) | Le délimiteur d'un fichier CSV. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/size_settings/) | Les paramètres de taille de page. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/) | La propriété indique si les ressources externes sont chargées. Si True, toutes les ressources externes ne seront pas chargées sauf celles de la liste [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). Valeur par défaut : True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/whitelisted_resources/) | Les ressources externes qui seront toujours chargées. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | La propriété détermine si tout le contenu des colonnes d’une feuille est rendu sur une seule page dans le résultat. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Les lignes sont ajustées automatiquement lors de la conversion. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | La propriété détermine si les restrictions des fichiers Excel sont vérifiées lors de la modification d’objets liés aux cellules. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Le nombre de colonnes par page utilisé pour diviser une feuille de calcul en pages ; la valeur par défaut est 0, ce qui désactive la pagination. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | La plage à convertir lors de la conversion vers un format non‑feuille de calcul, par ex. "D1:F8". (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Les informations de culture du système utilisées lors du chargement du fichier. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | La propriété indique s'il faut ignorer les erreurs de calcul de formule. L'erreur peut être une fonction non prise en charge, des liens externes, etc. La valeur par défaut est False. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | La propriété indique si le contenu de chaque feuille est converti en une seule page dans le document PDF. La valeur par défaut est True. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | La conversion est optimisée pour une taille de fichier plus petite plutôt que pour la qualité d'impression lorsqu'elle est définie sur True lors de la conversion en PDF. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Le mot de passe utilisé pour déprotéger un document protégé. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Le drapeau indiquant si la structure du document doit être préservée lors de la conversion en PDF (la valeur par défaut est False). (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | La façon dont les commentaires sont imprimés avec la feuille. La valeur par défaut est PrintNoComments. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Les dossiers de polices sont réinitialisés avant le chargement du document. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Le nombre de lignes par page utilisé pour diviser une feuille de calcul en pages, avec une valeur par défaut de 0 signifiant aucune pagination. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | La liste des index de feuilles à convertir. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Le nom de la feuille à convertir. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | L'option d'afficher les lignes de grille lors de la conversion de fichiers Excel. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | L'option d'afficher les feuilles masquées lors de la conversion de fichiers Excel. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Le paramètre qui ignore les lignes et colonnes vides lors de la conversion. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | La propriété détermine si les pieds de page sont ignorés lors de la conversion de documents de feuille de calcul. Valeur par défaut : False. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | L'option d'ignorer les en-têtes lors de la conversion de documents de feuille de calcul. Valeur par défaut : False. (hérité de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### Voir aussi
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
