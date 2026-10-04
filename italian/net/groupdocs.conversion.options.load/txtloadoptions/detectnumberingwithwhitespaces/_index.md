---
title: "DetectNumberingWithWhitespaces"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Consente di specificare come vengono riconosciuti gli elementi delle liste numerate quando il documento di testo semplice viene convertito. Il valore predefinito è true."
type: docs
weight: 30
url: /it/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Consente di specificare come vengono riconosciuti gli elementi delle liste numerate quando il documento di testo semplice viene convertito. Il valore predefinito è true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Osservazioni

Se questa opzione è impostata su false, l'algoritmo di riconoscimento delle liste rileva i paragrafi di elenco quando i numeri di elenco terminano con un punto, una parentesi chiusa o simboli di elenco (come "•", "*", "-" o "o").

Se questa opzione è impostata su true, gli spazi bianchi sono anche usati come delimitatori dei numeri di elenco: l'algoritmo di riconoscimento delle liste per la numerazione in stile arabo (1., 1.1.2.) utilizza sia gli spazi bianchi sia il simbolo punto (".").

### IConversionConvertOptions

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
