---
title: "OnConversionCompleted"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Registra una callback da invocare quando una conversione di pagina termina con successo. Richiamare nuovamente sostituisce qualsiasi gestore impostato in precedenza."
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

Registra una callback da invocare quando una conversione di pagina termina con successo. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato.

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| onCompleted | Action`1 | Un'azione per gestire il completamento, ricevendo il contesto della pagina convertita. |

### Valore restituito

Questa fase, quindi ulteriori handler o `Convert` / `Compress` possono essere concatenati.

### IConversionConvertOptions

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
