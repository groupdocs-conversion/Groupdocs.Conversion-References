---
title: "SpreadsheetConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file Spreadsheet."
type: docs
weight: 2240
url: /it/net/groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
## SpreadsheetConvertOptions class

Opzioni per la conversione al tipo di file Spreadsheet.

```csharp
public class SpreadsheetConvertOptions : CommonConvertOptions<SpreadsheetFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [SpreadsheetConvertOptions](spreadsheetconvertoptions)() | Inizializza una nuova istanza della classe [`SpreadsheetConvertOptions`](../spreadsheetconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/encoding) { get; set; } | Specifica la codifica da utilizzare quando si converte in formati delimitati |
| [Format](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. (2 proprietà) |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/password) { get; set; } | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
| [Separator](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/separator) { get; set; } | Specifica il separatore da utilizzare quando si converte in formati delimitati |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/zoom) { get; set; } | Specifica il livello di zoom in percentuale. Il valore predefinito è 100. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [SpreadsheetFileType](../../groupdocs.conversion.filetypes/spreadsheetfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
