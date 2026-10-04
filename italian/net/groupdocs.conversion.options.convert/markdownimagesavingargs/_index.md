---
title: "MarkdownImageSavingArgs"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Argomenti passati a ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /it/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Argomenti passati a [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Nome file (o ID segnaposto) incorporato come URI dell'immagine nell'output Markdown. Assegnare per riscrivere l'URI. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Stream di destinazione in cui il convertitore scriverà i byte dell'immagine dopo il ritorno di questa callback. Sostituirlo con il proprio stream scrivibile (ad es. un FileStream per la persistenza su disco o un MemoryStream che si intende leggere successivamente). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | Quando è false (predefinito), il convertitore chiude [`ImageStream`](./imagestream) dopo la scrittura — comportamento tipico per sostituzioni di FileStream che devono essere svuotate su disco. Impostare a true per mantenere lo stream aperto dopo il completamento della conversione (tipico per un MemoryStream che si intende leggere personalmente); il chiamante gestisce quindi lo smaltimento. |

### IConversionConvertOptions

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
