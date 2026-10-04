---
title: "WebConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file Web."
type: docs
weight: 2320
url: /it/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

Opzioni per la conversione al tipo di file Web.

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>, IUsePdfConvertOptions, 
    IZoomConvertOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | Inizializza una nuova istanza della classe [`WebConvertOptions`](../webconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [EmbedFontResources](../../groupdocs.conversion.options.convert/webconvertoptions/embedfontresources) { get; set; } | Specifica se incorporare le risorse dei font all'interno dell'HTML principale. Il valore predefinito è false. Nota: se FixedLayout è impostato su true, le risorse dei font saranno sempre incorporate. |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Se `true` verrà utilizzato il layout fisso, ad esempio elementi HTML posizionati assolutamente. Predefinito: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Mostra i bordi della pagina durante la conversione a layout fisso. Il valore predefinito è True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SlideShow](../../groupdocs.conversion.options.convert/webconvertoptions/slideshow) { get; set; } | Si applica solo alla conversione di una presentazione in [`Html`](../../groupdocs.conversion.filetypes/webfiletype/html) o [`Htm`](../../groupdocs.conversion.filetypes/webfiletype/htm) e viene ignorato per tutte le altre conversioni. Specifica se la presentazione diventa una presentazione HTML interattiva con transizioni tra diapositive e animazioni di forme, invece della pagina HTML statica predefinita. Il valore predefinito è false. |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Se `true`, l'input viene prima convertito in PDF e poi nel formato desiderato. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Specifica il livello di zoom in percentuale. Il valore predefinito è 100. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
