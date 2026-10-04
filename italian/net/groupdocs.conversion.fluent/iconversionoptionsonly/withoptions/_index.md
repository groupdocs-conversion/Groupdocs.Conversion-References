---
title: "WithOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Imposta le opzioni di conversione per il processo di conversione."
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Imposta le opzioni di conversione per il processo di conversione.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opzioni di conversione. |

### Valore restituito

Fase dei gestori per continuare la costruzione della conversione.

### IConversionConvertOptions

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Imposta le opzioni di conversione utilizzando una funzione provider.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| optionsProvider | Func`2 | Una funzione che fornisce le opzioni di conversione in base al contesto di conversione. |

### Valore restituito

Fase dei gestori per continuare la costruzione della conversione.

### IConversionConvertOptions

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
