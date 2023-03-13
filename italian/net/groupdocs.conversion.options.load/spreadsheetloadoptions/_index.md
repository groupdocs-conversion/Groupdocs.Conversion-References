---
title: SpreadsheetLoadOptions
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Opzioni per il caricamento dei documenti del foglio di calcolo.
type: docs
weight: 2260
url: /it/net/groupdocs.conversion.options.load/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Opzioni per il caricamento dei documenti del foglio di calcolo.

```csharp
public class SpreadsheetLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Inizializza una nuova istanza di[`SpreadsheetLoadOptions`](../spreadsheetloadoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Se controlla la restrizione del file excel quando l'utente modifica gli oggetti relativi alle celle. Ad esempio, Excel non consente di inserire un valore di stringa più lungo di 32K. Quando inserisci un valore più lungo di 32K, se questa proprietà è true, otterrai un'eccezione. Se questa proprietà è false, accetteremo il valore della stringa di input come valore della cella in modo che in seguito tu possa restituire il valore della stringa completo per altri formati di file come CSV. Tuttavia, se hai impostato un tipo di valore non valido per il formato di file Excel, non dovresti salvare la cartella di lavoro come formato di file Excel in un secondo momento. Altrimenti potrebbe esserci un errore imprevisto per il file excel generato. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Converti un intervallo specifico durante la conversione in un formato diverso dal foglio di calcolo. Esempio: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Ottieni o imposta le informazioni sulla cultura del sistema al momento del caricamento del file |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Carattere predefinito per il documento del foglio di calcolo. Se manca un carattere, verrà utilizzato il seguente carattere. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Sostituisci caratteri specifici durante la conversione di un foglio di calcolo. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Tipo di file del documento di input. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Nascondi commenti. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Se OnePagePerSheet è vero, il contenuto del foglio verrà convertito in una pagina nel documento PDF. Il valore predefinito è true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Se True e la conversione in Pdf, la conversione è ottimizzata per una dimensione del file migliore rispetto alla qualità di stampa. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Imposta la password per rimuovere la protezione del documento protetto. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Elenco degli indici dei fogli da convertire. Gli indici devono essere a base zero |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nome foglio da convertire |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Mostra le linee della griglia durante la conversione di file Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Mostra fogli nascosti durante la conversione di file Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Salta righe e colonne vuote durante la conversione. Il valore predefinito è True. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funge da funzione hash predefinita. |

### Guarda anche

* class [LoadOptions](../loadoptions)
* spazio dei nomi [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
