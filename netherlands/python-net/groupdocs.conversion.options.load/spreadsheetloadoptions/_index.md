---
title: "SpreadsheetLoadOptions klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Biedt opties voor het laden van Spreadsheet-documenten."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

Biedt opties voor het laden van Spreadsheet-documenten.

Het SpreadsheetLoadOptions type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | Initialiseert een nieuw exemplaar van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/). |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Kloont de huidige instantie. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bepaalt of twee objectinstellingen gelijk zijn. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als de standaard hash-functie. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | De eigenschap bepaalt of alle kolominhoud van een blad op één enkele pagina in het resultaat wordt weergegeven. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | De rijen worden automatisch aangepast bij het converteren. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | De eigenschap bepaalt of Excel‑bestandbeperkingen worden gecontroleerd bij het wijzigen van celgerelateerde objecten. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | De eigenschap ClearBuiltInDocumentProperties bepaalt of ingebouwde documenteigenschappen worden gewist bij het laden van een spreadsheet. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | De eigenschap ClearCustomDocumentProperties. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Het aantal kolommen per pagina dat wordt gebruikt om een werkblad in pagina's te splitsen; standaard is 0, wat paginering uitschakelt. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | De eigenschap implementeert [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) en heeft standaard de waarde False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | De eigenschap die [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/) implementeert. Standaard is True. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Het bereik dat moet worden geconverteerd bij het omzetten naar een niet‑spreadsheetformaat, bijv. "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | De systeemcultuurinfo die wordt gebruikt wanneer het bestand wordt geladen. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | Het standaardlettertype voor een spreadsheet‑document. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | De diepte van de documentencontainer‑laadopties. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | De lettertype‑substituten die worden gebruikt bij het converteren van een spreadsheet‑document. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | Het type invoerdocumentbestand. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | De eigenschap geeft aan of formule‑berekeningsfouten moeten worden genegeerd. De fout kan een niet‑ondersteunde functie, externe koppelingen, enz. zijn. Standaard is False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | De margesettings. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | De eigenschap geeft aan of de inhoud van elk blad wordt geconverteerd naar één enkele pagina in het PDF‑document. Standaardwaarde is True. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | De conversie is geoptimaliseerd voor een kleinere bestandsgrootte in plaats van afdrukkwaliteit wanneer deze op True is ingesteld tijdens het converteren naar PDF. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Het wachtwoord dat wordt gebruikt om een beveiligd document te ontgrendelen. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | De vlag die aangeeft of de documentstructuur behouden moet blijven bij het converteren naar PDF (standaard is False). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | De manier waarop opmerkingen worden afgedrukt met het blad. Standaard is PrintNoComments. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | De lettertype‑mappen worden gereset vóór het laden van het document. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Het aantal rijen per pagina dat wordt gebruikt om een werkblad in pagina's te splitsen, met een standaardwaarde van 0 wat betekent dat er geen paginering is. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | De lijst met bladindexen om te converteren. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | De bladnaam om te converteren. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | De optie om rasterlijnen weer te geven bij het converteren van Excel‑bestanden. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | De optie om verborgen bladen weer te geven bij het converteren van Excel‑bestanden. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | De grootte‑instellingen, zoals gedefinieerd door [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/). |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | De instelling die lege rijen en kolommen overslaat bij het converteren. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | De eigenschap implementeert [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | De eigenschap bepaalt of voetteksten worden overgeslagen bij het converteren van spreadsheet‑documenten. Standaard: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | De optie om kopteksten over te slaan bij het converteren van spreadsheet‑documenten. Standaard: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | De toegestane bronnen zoals gedefinieerd door [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Zie ook
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
