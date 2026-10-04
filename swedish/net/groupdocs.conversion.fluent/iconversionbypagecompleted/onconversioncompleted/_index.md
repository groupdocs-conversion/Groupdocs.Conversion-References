---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ta emot konverterad sidström. Kommer endast att utlösas om ConvertToconvertedStreamProvider är inställd."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Ta emot konverterad sidström. Kommer att avfyras endast om "ConvertTo(convertedStreamProvider)" är inställd.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertedPageStream | Action`1 | Konverterad sidströmleverantör Den [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Returvärde

Gränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
