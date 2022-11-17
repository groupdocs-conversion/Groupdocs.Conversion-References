---
title: CsvLoadOptions
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Opzioni per il caricamento di documenti Csv.
type: docs
weight: 1860
url: /it/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Opzioni per il caricamento di documenti Csv.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Inizializza la nuova istanza di[`CsvLoadOptions`](../csvloadoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Se controlla la restrizione del file excel quando l'utente modifica gli oggetti relativi alle celle. Ad esempio, Excel non consente di inserire un valore di stringa più lungo di 32K. Quando inserisci un valore più lungo di 32K, se questa proprietà è true, otterrai un'eccezione. Se questa proprietà è false, accetteremo il valore della stringa di input come valore della cella in modo che in seguito tu possa restituire il valore della stringa completo per altri formati di file come CSV. Tuttavia, se hai impostato un tipo di valore non valido per il formato di file Excel, non dovresti salvare la cartella di lavoro come formato di file Excel in un secondo momento. Altrimenti potrebbe esserci un errore imprevisto per il file excel generato. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Indica se la stringa nel file viene convertita in data. L'impostazione predefinita è True. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Indica se la stringa nel file viene convertita in numerica. L'impostazione predefinita è True. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Converti intervallo specifico durante la conversione in un formato diverso dal foglio di calcolo. Esempio: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Ottieni o imposta le informazioni sulla cultura del sistema al momento del caricamento del file |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Carattere predefinito per il documento del foglio di calcolo. Se manca un carattere, verrà utilizzato il seguente carattere. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Codifica. L'impostazione predefinita è Encoding.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Sostituisci caratteri specifici durante la conversione di un foglio di calcolo. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Tipo di file del documento di input. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Indica se il testo è una formula se inizia con "=". |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Nascondi commenti. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True significa che il file contiene diverse codifiche. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Se OnePagePerSheet è true, il contenuto del foglio verrà convertito in una pagina nel documento PDF. Il valore predefinito è true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Se True e la conversione in Pdf la conversione è ottimizzata per una dimensione del file migliore rispetto alla qualità di stampa. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Imposta la password per rimuovere la protezione del documento protetto. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Delimitatore di un file Csv. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nome foglio da convertire |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Mostra le linee della griglia durante la conversione di file Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Mostra fogli nascosti durante la conversione di file Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Salta righe e colonne vuote durante la conversione. L'impostazione predefinita è True. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serve come funzione hash predefinita. |

### Guarda anche

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* spazio dei nomi [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
