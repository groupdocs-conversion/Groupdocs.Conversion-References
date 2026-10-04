---
title: "LayoutScope"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Ottiene o imposta quali spazi di disegno vengono convertiti. Il valore predefinito è Bothgroupdocs.conversion.options.load/cadlayoutscope/both, che non limita la conversione. Viene ignorato quando LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames è fornito perché i nomi di layout espliciti hanno sempre la precedenza. Un valore null è trattato come Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /it/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Ottiene o imposta quali spazi di disegno vengono convertiti. Il valore predefinito è [`Both`](../../cadlayoutscope/both), che non limita la conversione. Viene ignorato quando [`LayoutNames`](../layoutnames) è fornito, perché i nomi di layout espliciti hanno sempre la precedenza. Un valore `null` è trattato come [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Osservazioni

Un ambito che non seleziona nessuno dei fogli offerti da un disegno provoca il fallimento della conversione con un [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) che indica l'ambito e i fogli presenti, anziché rendere gli spazi esclusi dall'ambito. Un disegno che non offre alcun foglio rimane invariato e si converte comunque come un'unica unità. Non rispettato durante la conversione in PDF/UA-1, per il motivo indicato in [`LayoutNames`](../layoutnames).

### IConversionConvertOptions

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
