---
title: "IConversionHandlersStage"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Fase di gestori di conversione appiattita. Consente di impostare OnConversionCompleted o OnConversionFailed in qualsiasi ordine e un numero illimitato di volte prima di procedere a Convert / Compress. Gli eventi dovrebbero essere registrati nella fase iniziale tramite WithEvents./iconversionsettings/withevents invece che in questa fase."
type: docs
weight: 1480
url: /it/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Fase di gestori di conversione appiattita. Consente di impostare `OnConversionCompleted` o `OnConversionFailed` in qualsiasi ordine e un numero illimitato di volte, prima di procedere a `Convert` / `Compress`. Gli eventi dovrebbero essere registrati nella fase iniziale tramite [`WithEvents`](../iconversionsettings/withevents) invece che in questa fase.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Registra una callback da invocare quando una conversione di documento termina con successo. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Registra una callback da invocare quando una conversione di documento fallisce. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato. |

### IConversionConvertOptions

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
