---
title: "FontTransformations"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Trasforma i font esistenti dopo il caricamento del documento e il completamento della sostituzione dei font. Le trasformazioni dei font possono modificare qualsiasi font nel documento, inclusi i font caricati correttamente."
type: docs
weight: 100
url: /it/net/groupdocs.conversion.options.load/pdfloadoptions/fonttransformations/
---
## PdfLoadOptions.FontTransformations property

Trasforma i caratteri esistenti dopo il caricamento del documento e il completamento della sostituzione dei caratteri. Le trasformazioni dei caratteri possono modificare qualsiasi carattere nel documento, inclusi i caratteri caricati correttamente.

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### Osservazioni

**Note:** Font transformations are applied after all font substitution steps are complete.

Le trasformazioni vengono elaborate nell'ordine in cui compaiono nell'elenco.

Casi d'uso: modifiche di stile, requisiti di branding, miglioramenti di accessibilità.

### IConversionConvertOptions

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [PdfLoadOptions](../../pdfloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
