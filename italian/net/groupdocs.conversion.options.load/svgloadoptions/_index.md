---
title: "SvgLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Svg."
type: docs
weight: 2830
url: /it/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Opzioni per il caricamento di documenti Svg.

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Inizializza una nuova istanza della classe [`SvgLoadOptions`](../svgloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | Ottiene o imposta un valore che indica se ritagliare il riquadro di delimitazione SVG ai limiti del contenuto prima della conversione. Il valore predefinito è false. |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | Imposta l'altezza minima per la conversione del documento SVG. Viene usata durante la conversione in formati raster. Il valore predefinito è 600. |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | Imposta la larghezza minima per la conversione del documento SVG. Viene usata durante la conversione in formati raster. Il valore predefinito è 800. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | Risorse esterne che saranno sempre caricate. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
