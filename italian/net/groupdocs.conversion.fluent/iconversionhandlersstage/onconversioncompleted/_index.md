---
title: "OnConversionCompleted"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Registra una callback da invocare quando una conversione di documento si completa con successo. La reinvocazione sostituisce qualsiasi handler precedentemente impostato."
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Registra una callback da invocare quando una conversione di documento termina con successo. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| onCompleted | Action`1 | Un'azione per gestire il completamento, ricevendo il contesto di conversione. |

### Valore restituito

Questa fase, quindi ulteriori handler o `Convert` / `Compress` possono essere concatenati.

### IConversionConvertOptions

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
