---
title: WordProcessingConvertOptions
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Opzioni per la conversione nel tipo di file WordProcessing.
type: docs
weight: 2000
url: /it/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Opzioni per la conversione nel tipo di file WordProcessing.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Inizializza una nuova istanza di[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | DPI della pagina desiderata dopo la conversione. La risoluzione predefinita è: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui deve essere convertito il documento di input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Il tipo di file desiderato in cui deve essere convertito il documento di input. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Altezza pagina desiderata dopo la conversione. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Margine inferiore della pagina desiderato in pixel dopo la conversione. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Margine sinistro della pagina desiderato in pixel dopo la conversione. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Margine destro della pagina desiderato in pixel dopo la conversione. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Margine superiore della pagina desiderato in pixel dopo la conversione. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Il numero di pagina da cui iniziare la conversione. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Orientamento della pagina desiderato dopo la conversione |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | L'elenco degli indici delle pagine da convertire. Dovrebbe essere specificato per convertire pagine specifiche. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Numero di pagine da convertire a partire da`Numero di pagina` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Dimensione pagina desiderata dopo la conversione |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Imposta questa proprietà se vuoi proteggere il documento convertito con una password. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Modalità di riconoscimento durante la conversione da pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Opzioni di conversione specifiche per RTF |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opzioni specifiche filigrana |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Larghezza pagina desiderata dopo la conversione. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Specifica il livello di zoom in percentuale. L'impostazione predefinita è 100. Lo zoom predefinito è supportato fino a Microsoft Word 2010. A partire da Microsoft Word 2013 lo zoom predefinito non è più impostato su documento, ma sembra utilizzare il fattore di zoom dell'ultimo documento aperto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza delle opzioni correnti. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funge da funzione hash predefinita. |

### Guarda anche

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* spazio dei nomi [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
