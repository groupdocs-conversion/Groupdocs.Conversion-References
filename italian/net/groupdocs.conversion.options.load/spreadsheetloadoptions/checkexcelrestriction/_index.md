---
title: "CheckExcelRestriction"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Indica se verificare le restrizioni del file Excel quando l'utente modifica oggetti correlati alle celle. Ad esempio, Excel non consente l'inserimento di una stringa più lunga di 32K. Quando si inserisce un valore più lungo di 32K, se questa proprietà è true si otterrà un'Exception. Se questa proprietà è false accetteremo la stringa inserita come valore della cella, così in seguito sarà possibile esportare la stringa completa in altri formati di file come CSV. Tuttavia, se si imposta un valore di questo tipo non valido per il formato Excel, non si dovrebbe salvare la cartella di lavoro in formato Excel in seguito. Altrimenti potrebbero verificarsi errori imprevisti nel file Excel generato."
type: docs
weight: 40
url: /it/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Se verificare le restrizioni del file excel quando l'utente modifica gli oggetti correlati alle celle. Ad esempio, excel non consente l'inserimento di una stringa più lunga di 32K. Quando inserisci un valore più lungo di 32K, se questa proprietà è true, otterrai un'Exception. Se questa proprietà è false, accetteremo la tua stringa di input come valore della cella in modo che in seguito tu possa esportare la stringa completa per altri formati di file come CSV. Tuttavia, se hai impostato un valore di questo tipo non valido per il formato file excel, non dovresti salvare la cartella di lavoro come formato file excel in seguito. Altrimenti potrebbero verificarsi errori imprevisti nel file excel generato.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### IConversionConvertOptions

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
