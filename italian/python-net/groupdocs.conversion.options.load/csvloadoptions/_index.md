---
title: "Classe CsvLoadOptions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Fornisce opzioni per il caricamento di documenti CSV."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/csvloadoptions/
is_root: false
weight: 80
---


## CsvLoadOptions class

Fornisce opzioni per il caricamento di documenti CSV.

Il tipo CsvLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/__init__/) | Inizializza una nuova istanza di [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Clona l'istanza corrente. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina se due istanze di oggetti sono uguali. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Funge da funzione hash predefinita. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_built_in_document_properties/) | La proprietà rimuove le proprietà di metadati integrate dal documento. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_custom_document_properties/) | La proprietà che rimuove le proprietà di metadati personalizzate dal documento. |
| [convert_date_time_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_date_time_data/) | La proprietà indica se la stringa nel file viene convertita in data. Il valore predefinito è True. |
| [convert_numeric_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_numeric_data/) | Il flag indica se le stringhe nel file vengono convertite in valori numerici. Il valore predefinito è True. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owned/) | L'opzione per controllare se i documenti posseduti nel contenitore dei documenti devono essere convertiti. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owner/) | L'opzione per controllare se il contenitore dei documenti stesso deve essere convertito; se vero, il contenitore sarà il primo documento convertito. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/default_font/) | Il carattere da utilizzare se un carattere è mancante. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/depth/) | L'opzione di profondità controlla quanti livelli di profondità eseguire la conversione. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/encoding/) | La codifica utilizzata per i file CSV. Il valore predefinito è `Encoding.Default`. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/font_substitutes/) | I sostituti del carattere. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/format/) | Il tipo di file del documento di input. |
| [has_formula](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/has_formula/) | La proprietà indica se il testo è una formula se inizia con "=". |
| [is_multi_encoded](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/is_multi_encoded/) | La proprietà indica se il file contiene diverse codifiche. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/margin_settings/) | Le impostazioni dei margini della pagina. |
| [separator](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/separator/) | Il delimitatore di un file CSV. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/size_settings/) | Le impostazioni delle dimensioni della pagina. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/) | La proprietà indica se le risorse esterne vengono caricate. Se True, tutte le risorse esterne non verranno caricate eccetto quelle nella lista [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). Valore predefinito: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/whitelisted_resources/) | Le risorse esterne che saranno sempre caricate. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | La proprietà determina se tutto il contenuto delle colonne di un foglio viene renderizzato su una singola pagina nel risultato. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Le righe vengono adattate automaticamente durante la conversione. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | La proprietà determina se le restrizioni dei file Excel vengono verificate quando si modificano oggetti correlati alle celle. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Il numero di colonne per pagina utilizzato per suddividere un foglio di lavoro in pagine; il valore predefinito è 0, che disabilita l'impaginazione. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | L'intervallo da convertire quando si converte in un formato non‑foglio di calcolo, ad es. "D1:F8". (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Le informazioni sulla cultura di sistema utilizzate quando il file viene caricato. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | La proprietà indica se ignorare gli errori di calcolo delle formule. L'errore può essere una funzione non supportata, collegamenti esterni, ecc. Il valore predefinito è False. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | La proprietà indica se il contenuto di ogni foglio viene convertito in una singola pagina nel documento PDF. Il valore predefinito è True. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | La conversione è ottimizzata per una dimensione del file più piccola anziché per la qualità di stampa quando impostata su True durante la conversione in PDF. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | La password utilizzata per rimuovere la protezione di un documento protetto. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Il flag indica se la struttura del documento deve essere preservata durante la conversione in PDF (il valore predefinito è False). (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Il modo in cui i commenti vengono stampati con il foglio. Il valore predefinito è PrintNoComments. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Le cartelle dei font vengono reimpostate prima di caricare il documento. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Il numero di righe per pagina utilizzato per suddividere un foglio di lavoro in pagine, con un valore predefinito di 0 che indica nessuna paginazione. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | L'elenco degli indici dei fogli da convertire. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Il nome del foglio da convertire. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | L'opzione per mostrare le linee della griglia durante la conversione dei file Excel. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | L'opzione per mostrare i fogli nascosti durante la conversione dei file Excel. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | L'impostazione che salta righe e colonne vuote durante la conversione. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | La proprietà determina se i piè di pagina vengono saltati durante la conversione dei documenti di foglio di calcolo. Predefinito: False. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | L'opzione per saltare le intestazioni durante la conversione dei documenti di foglio di calcolo. Predefinito: False. (eredita da [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### Vedi anche
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
