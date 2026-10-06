---
title: "CsvLoadOptions-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tillhandahåller alternativ för att läsa in CSV‑dokument."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/csvloadoptions/
is_root: false
weight: 80
---


## CsvLoadOptions class

Tillhandahåller alternativ för att läsa in CSV‑dokument.

CsvLoadOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/__init__/) | Initierar en ny [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/) instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Klonar aktuell instans. (ärvd från [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestämmer om två objektinstanser är lika. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Fungerar som standard‑hashfunktion. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_built_in_document_properties/) | Egenskapen tar bort inbyggda metadataegenskaper från dokumentet. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_custom_document_properties/) | Egenskapen som tar bort anpassade metadataegenskaper från dokumentet. |
| [convert_date_time_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_date_time_data/) | Egenskapen indikerar om strängen i filen konverteras till datum. Standardvärdet är True. |
| [convert_numeric_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_numeric_data/) | Flaggan som indikerar om strängar i filen konverteras till numeriska värden. Standard är True. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owned/) | Alternativet för att styra om de ägda dokumenten i dokumentbehållaren måste konverteras. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owner/) | Alternativet för att kontrollera om dokumentbehållaren själv måste konverteras; om true, blir behållaren det första konverterade dokumentet. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/default_font/) | Typsnittet som ska användas om ett typsnitt saknas. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/depth/) | Djupalternativet styr hur många nivåer i djupet som konverteringen ska utföras på. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/encoding/) | Kodningen som används för CSV-filer. Standard är `Encoding.Default`. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/font_substitutes/) | Typsnittsersättningar. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/format/) | Inmatningsdokumentets filtyp. |
| [has_formula](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/has_formula/) | Egenskapen indikerar om texten är en formel om den börjar med "=". |
| [is_multi_encoded](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/is_multi_encoded/) | Egenskapen indikerar om filen innehåller flera kodningar. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/margin_settings/) | Sidmarginalinställningarna. |
| [separator](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/separator/) | Avgränsaren för en CSV-fil. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/size_settings/) | Sidstorleksinställningarna. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/) | Egenskapen indikerar om externa resurser laddas. Om True kommer alla externa resurser inte att laddas förutom de i listan [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). Standard: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/whitelisted_resources/) | De externa resurser som alltid kommer att laddas. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Egenskapen bestämmer om allt kolumninnehåll i ett blad renderas på en enda sida i resultatet. (ärvd från [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Raderna anpassas automatiskt vid konvertering. (ärvd från [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Egenskapen bestämmer om Excel‑filrestriktioner kontrolleras när cellrelaterade objekt modifieras. (ärvd från [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Antalet kolumner per sida som används för att dela ett arbetsblad i sidor; standard är 0, vilket inaktiverar paginering. (ärvd från [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Området som ska konverteras vid konvertering till ett icke‑kalkylbladsformat, t.ex. "D1:F8". (ärvd från [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Systemets kulturinformation som används när filen laddas. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Egenskapen anger om formelberäkningsfel ska ignoreras. Felet kan vara en funktion som inte stöds, externa länkar osv. Standardvärdet är False. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Egenskapen anger om innehållet i varje blad konverteras till en enda sida i PDF-dokumentet. Standardvärdet är True. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Konverteringen optimeras för mindre filstorlek snarare än utskriftskvalitet när den är satt till True vid konvertering till PDF. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Lösenordet som används för att ta bort skyddet på ett skyddat dokument. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Flaggan som indikerar om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är False). (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Hur kommentarer skrivs ut med bladet. Standard är PrintNoComments. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Teckensnittsmapparna återställs innan dokumentet laddas. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Antalet rader per sida som används för att dela ett kalkylblad i sidor, med standardvärdet 0 som betyder ingen paginering. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Listan med bladindex att konvertera. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Bladnamnet att konvertera. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Alternativet att visa rutnät när Excel-filer konverteras. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Alternativet att visa dolda blad när Excel-filer konverteras. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Inställningen som hoppar över tomma rader och kolumner vid konvertering. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Egenskapen bestämmer om sidfötter ska hoppas över vid konvertering av kalkylbladsdokument. Standard: False. (inherited from [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Alternativet att hoppa över rubriker när kalkylbladsdokument konverteras. Standard: False. (ärvd från [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### Se även
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
