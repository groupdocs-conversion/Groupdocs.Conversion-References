---
title: "RasterImageLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti immagine."
type: docs
weight: 2800
url: /it/net/groupdocs.conversion.options.load/rasterimageloadoptions/
---
## RasterImageLoadOptions class

Opzioni per il caricamento di documenti immagine.

```csharp
public sealed class RasterImageLoadOptions : BaseImageLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [RasterImageLoadOptions](rasterimageloadoptions)() | Inizializza una nuova istanza della classe [`RasterImageLoadOptions`](../rasterimageloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CropArea](../../groupdocs.conversion.options.load/rasterimageloadoptions/croparea) { get; set; } | Ritaglia l'area dell'immagine prima della conversione |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Font predefinito per i tipi di documento Psd, Emf, Wmf. Il font seguente verrà utilizzato se un font è mancante. |
| [Format](../../groupdocs.conversion.options.load/rasterimageloadoptions/format) { get; set; } | Tipo di file del documento di input. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Reimposta le cartelle dei caratteri prima di caricare il documento |
| [VectorizationOptions](../../groupdocs.conversion.options.load/rasterimageloadoptions/vectorizationoptions) { get; set; } | Imposta le opzioni di vettorizzazione |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |
| [SetHeicConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setheicconnector)(IHeicConnector) | Imposta il connettore immagine Heic |
| [SetOcrConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setocrconnector)(IOcrConnector) | Imposta il connettore OCR dell'immagine |

### IConversionConvertOptions

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
