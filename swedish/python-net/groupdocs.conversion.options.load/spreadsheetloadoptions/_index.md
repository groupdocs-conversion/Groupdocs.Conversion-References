---
title: "SpreadsheetLoadOptions-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tillhandahåller alternativ för att ladda kalkylbladsdokument."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

Tillhandahåller alternativ för att ladda kalkylbladsdokument.

SpreadsheetLoadOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | Initierar en ny instans av [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/). |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Klonar aktuell instans. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestämmer om två objektinstanser är lika. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Fungerar som standard‑hashfunktion. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Egenskapen avgör om allt kolumninnehåll i ett blad renderas på en enda sida i resultatet. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Raderna anpassas automatiskt vid konvertering. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Egenskapen avgör om Excel-filrestriktioner kontrolleras när cellrelaterade objekt modifieras. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | Egenskapen ClearBuiltInDocumentProperties avgör om inbyggda dokumentegenskaper rensas när ett kalkylblad laddas. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | Egenskapen ClearCustomDocumentProperties. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Antalet kolumner per sida som används för att dela ett arbetsblad i sidor; standard är 0, vilket inaktiverar paginering. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | Egenskapen implementerar [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) och har standardvärdet False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | Egenskapen som implementerar [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). Standard är True. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Intervallet som ska konverteras vid konvertering till ett icke‑kalkylbladsformat, t.ex. "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Systemkulturinformationen som används när filen laddas. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | Standardteckensnittet för ett kalkylbladsdokument. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | Djupet för dokumentbehållarens laddningsalternativ. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | Teckensnittsalternativen som används vid konvertering av ett kalkylbladsdokument. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | Inmatningsdokumentets filtyp. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Egenskapen anger om formelberäkningsfel ska ignoreras. Felet kan vara en funktion som inte stöds, externa länkar osv. Standardvärdet är False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | Marginalinställningarna. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Egenskapen anger om innehållet i varje blad konverteras till en enda sida i PDF-dokumentet. Standardvärdet är True. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Konverteringen är optimerad för mindre filstorlek snarare än utskriftskvalitet när den är satt till True vid konvertering till PDF. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Lösenordet som används för att avskydda ett skyddat dokument. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Flaggan som indikerar om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är False). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Hur kommentarer skrivs ut med bladet. Standard är PrintNoComments. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Teckensnittsmapparna återställs innan dokumentet laddas. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Antalet rader per sida som används för att dela ett arbetsblad i sidor, med standardvärdet 0 som betyder ingen paginering. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Listan med bladindex att konvertera. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Bladnamnet att konvertera. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Alternativet att visa rutnät när Excel-filer konverteras. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Alternativet att visa dolda blad när Excel-filer konverteras. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | Storleksinställningarna, enligt definitionen i [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/). |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Inställningen som hoppar över tomma rader och kolumner vid konvertering. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | Egenskapen implementerar [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Egenskapen bestämmer om sidfötter ska hoppas över vid konvertering av kalkylbladsdokument. Standard: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Alternativet att hoppa över sidhuvuden vid konvertering av kalkylbladsdokument. Standard: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | De vitlistade resurserna enligt definitionen i [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Se även
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
