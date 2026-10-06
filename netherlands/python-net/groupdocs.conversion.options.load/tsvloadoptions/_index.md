---
title: "TsvLoadOptions-klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt opties voor het laden van TSV-documenten voor."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/tsvloadoptions/
is_root: false
weight: 480
---


## TsvLoadOptions class

Stelt opties voor het laden van TSV-documenten voor.

Het TsvLoadOptions-type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/__init__/) | Initialiseert een nieuw exemplaar van [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/). |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Kloont de huidige instantie. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bepaalt of twee objectinstellingen gelijk zijn. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als de standaard hash-functie. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_built_in_document_properties/) | De eigenschap verwijdert ingebouwde metagegevens-eigenschappen uit het document. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_custom_document_properties/) | De eigenschap die aangepaste metagegevens-eigenschappen uit het document verwijdert. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owned/) | De optie om te bepalen of de eigendom-documenten in de documentencontainer moeten worden geconverteerd. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owner/) | De optie om te bepalen of de container van het document zelf moet worden geconverteerd; indien true, wordt de container het eerste geconverteerde document. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/default_font/) | Het lettertype dat moet worden gebruikt als een lettertype ontbreekt. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/depth/) | De optie om te bepalen hoeveel niveaus diep de conversie moet worden uitgevoerd. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/font_substitutes/) | De lettertypevervangers. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/format/) | Het type invoerdocumentbestand. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/margin_settings/) | De paginamarge-instellingen. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/size_settings/) | De paginagrootte-instellingen. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/skip_external_resources/) | De eigenschap bepaalt of externe bronnen worden geladen; indien True, worden alle externe bronnen niet geladen behalve die in de lijst van [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). Standaard: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/whitelisted_resources/) | De externe bronnen die altijd worden geladen. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | De eigenschap bepaalt of alle kolominhoud van een blad op één enkele pagina in het resultaat wordt weergegeven. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | De rijen worden automatisch aangepast bij het converteren. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | De eigenschap bepaalt of Excel-bestandsbeperkingen worden gecontroleerd bij het wijzigen van celgerelateerde objecten. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Het aantal kolommen per pagina dat wordt gebruikt om een werkblad in pagina's te splitsen; standaard is 0, wat paginering uitschakelt. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Het bereik dat moet worden geconverteerd bij het converteren naar een niet‑spreadsheetformaat, bijv. "D1:F8". (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | De systeemcultuurinfo die wordt gebruikt wanneer het bestand wordt geladen. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | De eigenschap geeft aan of formuleberekeningsfouten moeten worden genegeerd. De fout kan een niet‑ondersteunde functie, externe koppelingen, enz. zijn. Standaard is False. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | De eigenschap geeft aan of de inhoud van elk blad wordt geconverteerd naar één enkele pagina in het PDF‑document. Standaardwaarde is True. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | De conversie wordt geoptimaliseerd voor een kleinere bestandsgrootte in plaats van afdrukkwaliteit wanneer deze op True is ingesteld tijdens het converteren naar PDF. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Het wachtwoord dat wordt gebruikt om een beveiligd document te ontgrendelen. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | De vlag die aangeeft of de documentstructuur moet worden behouden bij het converteren naar PDF (standaard is False). (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | De manier waarop opmerkingen worden afgedrukt met het blad. Standaard is PrintNoComments. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | De lettertype‑mappen worden gereset voordat het document wordt geladen. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Het aantal rijen per pagina dat wordt gebruikt om een werkblad in pagina's te splitsen, met een standaardwaarde van 0 wat betekent dat er geen paginering is. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | De lijst met blad‑indexen die moeten worden geconverteerd. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | De bladnaam die moet worden geconverteerd. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | De optie om rasterlijnen weer te geven bij het converteren van Excel‑bestanden. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | De optie om verborgen bladen weer te geven bij het converteren van Excel‑bestanden. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | De instelling die lege rijen en kolommen overslaat bij het converteren. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | De eigenschap bepaalt of voetteksten worden overgeslagen bij het converteren van spreadsheet‑documenten. Standaard: False. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | De optie om kopteksten over te slaan bij het converteren van spreadsheet‑documenten. Standaard: False. (geërfd van [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### Zie ook
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
