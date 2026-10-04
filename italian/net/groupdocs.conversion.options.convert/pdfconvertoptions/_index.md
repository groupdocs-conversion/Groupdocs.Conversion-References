---
title: "PdfConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file Pdf."
type: docs
weight: 2060
url: /it/net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

Opzioni per la conversione al tipo di file Pdf.

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IDpiConvertOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IPasswordConvertOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | Inizializza una nuova istanza della classe [`PdfConvertOptions`](../pdfconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | DPI della pagina desiderata dopo la conversione. La risoluzione predefinita è: 96 dpi. |
| [EmbedFullFonts](../../groupdocs.conversion.options.convert/pdfconvertoptions/embedfullfonts) { get; set; } | Quando impostato su true, l'intero file del font viene incorporato nel PDF invece di un sottoinsieme. Questo aumenta la dimensione del file di output ma garantisce una migliore compatibilità durante la modifica del PDF risultante. Si applica solo durante la conversione da documenti WordProcessing. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/fallbackpagesize) { get; set; } | Dimensione pagina di riserva |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginsettings) { get; set; } | Impostazioni dei margini di pagina |
| [OrientationSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/orientationsettings) { get; set; } | Impostazioni dell'orientamento della pagina |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | Opzioni di conversione specifiche per PDF |
| [ResizeMode](../../groupdocs.conversion.options.convert/pdfconvertoptions/resizemode) { get; set; } | Specifica come il contenuto deve essere ridimensionato quando la dimensione della pagina viene modificata. L'impostazione predefinita è AlignTopLeft (nessuna scala). |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | Rotazione della pagina |
| [SizeSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
