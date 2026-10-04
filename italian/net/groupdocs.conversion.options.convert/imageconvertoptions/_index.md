---
title: "ImageConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file Image."
type: docs
weight: 1950
url: /it/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opzioni per la conversione al tipo di file Image.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Inizializza una nuova istanza della classe [`ImageConvertOptions`](../imageconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Imposta il colore di sfondo dove supportato dal formato di origine |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Regola la luminosità dell'immagine. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Quando impostato, limita la risoluzione di rendering PDF per pagina alla risoluzione raster nativa della pagina in modo che una pagina non venga mai renderizzata a un DPI superiore a quello effettivamente contenuto nell'immagine incorporata, e emette quella pagina alle sue dimensioni pixel native (più piccole) e DPI nativo nell'output finale invece di reinflarla al DPI richiesto. Solo le pagine dominate da immagini (scansioni) sono interessate; le pagine con testo o contenuto vettoriale non vengono mai ammorbidite e sono emesse al DPI richiesto. Ignorato quando è impostato un valore esplicito di output [`Width`](./width) o [`Height`](./height). Il valore predefinito è `false` (nessuna limitazione; ogni pagina è renderizzata ed emessa al DPI richiesto). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Regola il contrasto dell'immagine. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Ritaglia l'area dell'immagine raster dopo la conversione |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Modalità di ribaltamento dell'immagine. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Regola la gamma dell'immagine. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indica se convertire in immagine in scala di grigi. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Altezza desiderata dell'immagine dopo la conversione. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Risoluzione orizzontale desiderata dell'immagine dopo la conversione. La risoluzione predefinita è quella del file di input o 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Opzioni di conversione specifiche per Jpeg. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Limite inferiore per asse applicato al DPI di rendering limitato quando [`CapResolutionToPageContent`](./capresolutiontopagecontent) è abilitato. Il DPI limitato non viene mai ridotto al di sotto di questo valore. Il valore predefinito è `0` (nessun limite inferiore). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Opzioni di conversione specifiche per Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Angolo di rotazione dell'immagine. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Opzioni di conversione specifiche per Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Se `true`, l'input viene prima convertito in PDF e poi nel formato desiderato. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Risoluzione verticale desiderata dell'immagine dopo la conversione. La risoluzione predefinita è quella del file di input o 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Opzioni di conversione specifiche per Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Larghezza desiderata dell'immagine dopo la conversione. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
