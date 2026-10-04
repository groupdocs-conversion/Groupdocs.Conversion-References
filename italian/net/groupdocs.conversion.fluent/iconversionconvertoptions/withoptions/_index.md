---
title: "WithOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Imposta le opzioni di conversione"
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Imposta le opzioni di conversione

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opzioni di conversione |

### Valore restituito

Interfaccia per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Imposta le opzioni di conversione

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parameter | Descrizione |
| --- | --- |
| convertOptionsProvider | Provider di opzioni di conversione |
| convertOptionsProvider arg1arg1 | Il [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Valore restituito

Interfaccia per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
