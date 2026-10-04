---
title: "WordProcessingConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file WordProcessing."
type: docs
weight: 2340
url: /it/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Opzioni per la conversione al tipo di file WordProcessing.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IDpiConvertOptions, IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, 
    IPasswordConvertOptions, IPdfRecognitionModeOptions, IZoomConvertOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Inizializza una nuova istanza della classe [`WordProcessingConvertOptions`](../wordprocessingconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | DPI della pagina desiderata dopo la conversione. La risoluzione predefinita è: 96 dpi. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallbackpagesize) { get; set; } | Dimensione pagina di riserva |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginsettings) { get; set; } | Impostazioni dei margini di pagina |
| [MarkdownOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdownoptions) { get; set; } | Implementa [`MarkdownOptions`](./markdownoptions) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientationsettings) { get; set; } | Impostazioni dell'orientamento della pagina |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Implementa [`PdfRecognitionMode`](../ipdfrecognitionmodeoptions/pdfrecognitionmode) |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Opzioni di conversione specifiche per RTF |
| [SizeSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Specifica il livello di zoom in percentuale. Il valore predefinito è 100. Lo zoom predefinito è supportato fino a Microsoft Word 2010. A partire da Microsoft Word 2013 lo zoom predefinito non è più impostato sul documento, ma sembra utilizzare il fattore di zoom dell'ultimo documento aperto. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
