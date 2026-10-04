---
title: "PresentationConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Descrive le opzioni per la conversione al tipo di file Presentazione."
type: docs
weight: 2170
url: /it/net/groupdocs.conversion.options.convert/presentationconvertoptions/
---
## PresentationConvertOptions class

Descrive le opzioni per la conversione al tipo di file Presentazione.

```csharp
public class PresentationConvertOptions : CommonConvertOptions<PresentationFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PresentationConvertOptions](presentationconvertoptions)() | Inizializza una nuova istanza della classe [`PresentationConvertOptions`](../presentationconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/presentationconvertoptions/password) { get; set; } | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/presentationconvertoptions/zoom) { get; set; } | Specifica il livello di zoom in percentuale. Il valore predefinito è 100. Lo zoom predefinito è supportato fino a Microsoft Powerpoint 2010. A partire da Microsoft Powerpoint 2013 lo zoom predefinito non è più impostato sul documento, ma sembra utilizzare il fattore di zoom dell'ultimo documento aperto. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PresentationFileType](../../groupdocs.conversion.filetypes/presentationfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
