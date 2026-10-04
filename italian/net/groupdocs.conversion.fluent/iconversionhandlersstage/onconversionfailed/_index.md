---
title: "OnConversionFailed"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Registra una callback da invocare quando una conversione di documento fallisce. La reinvocazione sostituisce qualsiasi handler precedentemente impostato."
type: docs
weight: 20
url: /it/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Registra una callback da invocare quando una conversione di documento fallisce. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| onFailed | Action`2 | Un'azione per gestire il fallimento, ricevendo il contesto di conversione e l'eccezione che ha causato il fallimento. |

### Valore restituito

Questa fase, quindi ulteriori handler o `Convert` / `Compress` possono essere concatenati.

### IConversionConvertOptions

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
