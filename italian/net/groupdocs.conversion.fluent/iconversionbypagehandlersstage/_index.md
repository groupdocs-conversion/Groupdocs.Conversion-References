---
title: "IConversionByPageHandlersStage"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Fase dei gestori di conversione appiattita per pagina. Specchio per pagina di IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /it/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Fase dei gestori di conversione appiattita per pagina. Specchio per pagina di [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Registra una callback da invocare quando una conversione di pagina termina con successo. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Registra una callback da invocare quando una conversione di pagina fallisce. Una nuova invocazione sostituisce qualsiasi gestore precedentemente impostato. |

### IConversionConvertOptions

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
