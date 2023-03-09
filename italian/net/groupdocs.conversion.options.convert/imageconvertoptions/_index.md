---
title: ImageConvertOptions
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Opzioni per la conversione nel tipo di file immagine.
type: docs
weight: 1630
url: /it/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opzioni per la conversione nel tipo di file immagine.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Inizializza una nuova istanza di[`ImageConvertOptions`](../imageconvertoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Imposta il colore di sfondo dove supportato dal formato sorgente |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Regola la luminosità dell'immagine. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Regola il contrasto dell'immagine. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Modalità capovolgi immagine. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui deve essere convertito il documento di input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Il tipo di file desiderato in cui deve essere convertito il documento di input. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Regola la gamma dell'immagine. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indica se convertire in immagine in scala di grigi. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Altezza dell'immagine desiderata dopo la conversione. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Risoluzione orizzontale dell'immagine desiderata dopo la conversione. La risoluzione predefinita è la risoluzione del file di input o 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Opzioni di conversione specifiche Jpeg. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Il numero di pagina da cui iniziare la conversione. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | L'elenco degli indici delle pagine da convertire. Dovrebbe essere specificato per convertire pagine specifiche. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Numero di pagine da convertire a partire da`Numero di pagina` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Opzioni di conversione specifiche per Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Angolo di rotazione dell'immagine. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Opzioni di conversione specifiche per Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Se`VERO` , l'input viene prima convertito in PDF e successivamente nel formato desiderato. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Risoluzione verticale dell'immagine desiderata dopo la conversione. La risoluzione predefinita è la risoluzione del file di input o 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opzioni specifiche filigrana |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Opzioni di conversione specifiche per Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Larghezza dell'immagine desiderata dopo la conversione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza delle opzioni correnti. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funge da funzione hash predefinita. |

### Guarda anche

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* spazio dei nomi [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
