---
title: "KeepImageStreamOpen"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Quando è false (predefinito) il convertitore chiude ImageStreamgroupdocs.conversion.options.convert/markdownimagesavingargs/imagestream dopo la scrittura, modalità tipica per sostituzioni di FileStream che devono essere svuotate su disco. Impostare a true per mantenere il flusso aperto dopo il completamento della conversione, tipico per un MemoryStream che si intende leggere autonomamente; il chiamante gestisce quindi lo smaltimento."
type: docs
weight: 30
url: /it/net/groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen/
---
## MarkdownImageSavingArgs.KeepImageStreamOpen property

Quando è false (predefinito), il convertitore chiude [`ImageStream`](../imagestream) dopo la scrittura — modalità tipica per sostituzioni di FileStream che devono essere svuotate su disco. Impostare a true per mantenere il flusso aperto dopo il completamento della conversione (tipico per un MemoryStream che si intende leggere autonomamente); il chiamante gestisce quindi lo smaltimento.

```csharp
public bool KeepImageStreamOpen { get; set; }
```

### IConversionConvertOptions

* class [MarkdownImageSavingArgs](../../markdownimagesavingargs)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
