---
title: "OnConversionCompleted"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Ricevi lo stream della pagina convertita. Verrà attivato solo se ConvertToconvertedStreamProvider è impostato."
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Ricevi lo stream della pagina convertita. Verrà attivato solo se "ConvertTo(convertedStreamProvider)" è impostato.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertedPageStream | Action`1 | Provider dello stream della pagina convertita Il [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Valore restituito

Interfaccia per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
