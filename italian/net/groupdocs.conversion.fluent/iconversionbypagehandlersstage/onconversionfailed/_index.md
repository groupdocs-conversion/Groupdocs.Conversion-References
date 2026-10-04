---
title: "OnConversionFailed"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Registra una callback da invocare quando una conversione di pagina fallisce. Richiamare nuovamente sostituisce qualsiasi gestore impostato in precedenza."
type: docs
weight: 20
url: /it/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Registra una callback da invocare quando una conversione di pagina fallisce. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| onFailed | Action`2 | Un'azione per gestire il fallimento, ricevendo il contesto della pagina convertita e l'eccezione che ha causato il fallimento. |

### Valore restituito

Questa fase, quindi ulteriori handler o `Convert` / `Compress` possono essere concatenati.

### IConversionConvertOptions

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
