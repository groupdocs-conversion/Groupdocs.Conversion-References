---
title: "WithOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Imposta le opzioni di caricamento"
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionloadoptions/withoptions/
---
## WithOptions(LoadOptions) {#withoptions}

Imposta le opzioni di caricamento

```csharp
public IConversionSourceDocumentLoaded WithOptions(LoadOptions loadOptions)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| loadOptions | LoadOptions | Opzioni di caricamento |

### IConversionConvertOptions

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;LoadContext, LoadOptions&gt;) {#withoptions_1}

Fornisci le opzioni di caricamento per il documento attualmente in fase di caricamento

```csharp
public IConversionSourceDocumentLoaded WithOptions(
    Func<LoadContext, LoadOptions> loadOptionsProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| loadOptionsProvider | Func`2 | Provider di opzioni di caricamento Il contesto delle opzioni di caricamento |

### IConversionConvertOptions

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadContext](../../../groupdocs.conversion/loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
