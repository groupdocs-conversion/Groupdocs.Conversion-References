---
title: "WithOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Imposta le opzioni di conversione"
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Imposta le opzioni di conversione

```csharp
public IConversionByPageHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opzioni di conversione |

### Valore restituito

Interfaccia per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Imposta le opzioni di conversione

```csharp
public IConversionByPageHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Opzioni di conversione Le [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Valore restituito

Interfaccia per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
