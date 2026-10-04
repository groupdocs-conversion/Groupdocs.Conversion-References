---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Ontvang de geconverteerde documentstroom. Wordt alleen geactiveerd als ConvertTostring fileName of ConvertToconvertedStreamProvider is ingesteld."
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Ontvang de geconverteerde document‑stroom. Wordt alleen geactiveerd als "ConvertTo(string fileName)" of ConvertTo(convertedStreamProvider)" is ingesteld.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertedFileStream | Action`1 | Provider voor geconverteerde documentstroom De [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Retourwaarde

Interface om de conversieopbouw voort te zetten

### Zie ook

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
