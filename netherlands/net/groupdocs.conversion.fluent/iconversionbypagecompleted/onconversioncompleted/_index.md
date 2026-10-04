---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Ontvang de geconverteerde paginastroom. Wordt alleen geactiveerd als ConvertToconvertedStreamProvider is ingesteld."
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Ontvang geconverteerde paginastroom. Wordt alleen geactiveerd als "ConvertTo(convertedStreamProvider)" is ingesteld.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertedPageStream | Action`1 | Provider voor geconverteerde paginastroom De [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Retourwaarde

Interface om de conversieopbouw voort te zetten

### Zie ook

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
