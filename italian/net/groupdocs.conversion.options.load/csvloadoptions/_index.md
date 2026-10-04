---
title: "CsvLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Csv."
type: docs
weight: 2450
url: /it/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Opzioni per il caricamento di documenti Csv.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Inizializza una nuova istanza della classe [`CsvLoadOptions`](../csvloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | Se AllColumnsInOnePagePerSheet è true, tutto il contenuto delle colonne di un foglio verrà esportato in una sola pagina nel risultato. La larghezza del formato carta del pagesetup sarà invalida, mentre le altre impostazioni del pagesetup continueranno ad avere effetto. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Adatta automaticamente tutte le righe durante la conversione |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Se verificare le restrizioni del file excel quando l'utente modifica gli oggetti correlati alle celle. Ad esempio, excel non consente l'inserimento di una stringa più lunga di 32K. Quando inserisci un valore più lungo di 32K, se questa proprietà è true, otterrai un'Exception. Se questa proprietà è false, accetteremo la tua stringa di input come valore della cella in modo che in seguito tu possa esportare la stringa completa per altri formati di file come CSV. Tuttavia, se hai impostato un valore di questo tipo non valido per il formato file excel, non dovresti salvare la cartella di lavoro come formato file excel in seguito. Altrimenti potrebbero verificarsi errori imprevisti nel file excel generato. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Rimuove le proprietà dei metadati integrate dal documento. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Rimuove le proprietà dei metadati personalizzate dal documento. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Dividi un foglio di lavoro in pagine per colonne. Il valore predefinito è 0, nessuna paginazione. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Indica se la stringa nel file viene convertita in data. Il valore predefinito è True. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Indica se la stringa nel file viene convertita in numerico. Il valore predefinito è True. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Il valore predefinito è false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Il valore predefinito è true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Converti un intervallo specifico durante la conversione in un formato diverso da quello del foglio di calcolo. Esempio: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Ottieni o imposta le informazioni sulla cultura di sistema al momento del caricamento del file |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Carattere predefinito per il documento del foglio di calcolo. Il carattere seguente verrà utilizzato se un carattere è mancante. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 1 |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Codifica. Il valore predefinito è Encoding.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Sostituisci caratteri specifici durante la conversione del documento del foglio di calcolo. |
| [Format](../../groupdocs.conversion.options.load/csvloadoptions/format) { get; } | Tipo di file del documento di input. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Indica se il testo è una formula se inizia con "=". |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Indica se ignorare gli errori di calcolo delle formule. L'errore può essere una funzione non supportata, collegamenti esterni, ecc. Il valore predefinito è false. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True indica che il file contiene diverse codifiche. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Impostazioni dei margini di pagina |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Se OnePagePerSheet è true, il contenuto del foglio verrà convertito in una pagina nel documento PDF. Il valore predefinito è true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Se True e si converte in Pdf, la conversione è ottimizzata per una dimensione del file migliore rispetto alla qualità di stampa. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Imposta la password per rimuovere la protezione del documento protetto. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | Determina se la struttura del documento deve essere preservata durante la conversione in PDF (il valore predefinito è false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Rappresenta il modo in cui i commenti vengono stampati con il foglio. Il valore predefinito è PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Reimposta le cartelle dei caratteri prima di caricare il documento |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Dividi un foglio di lavoro in pagine per righe. Il valore predefinito è 0, nessuna paginazione. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Delimitatore di un file Csv. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Elenco degli indici dei fogli da convertire. Gli indici devono essere basati su zero |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nome del foglio da convertire |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Mostra le linee della griglia durante la conversione dei file Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Mostra i fogli nascosti durante la conversione dei file Excel. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Salta righe e colonne vuote durante la conversione. Il valore predefinito è True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Salta i piè di pagina durante la conversione dei documenti del foglio di calcolo. Predefinito: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Salta le intestazioni durante la conversione dei documenti del foglio di calcolo. Predefinito: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Implementa [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
