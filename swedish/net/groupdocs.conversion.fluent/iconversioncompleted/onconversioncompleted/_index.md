---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ta emot konverterad dokumentström. Kommer att avfyras endast om ConvertTostring fileName eller ConvertToconvertedStreamProvider är angivet."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Ta emot konverterad dokumentström. Kommer endast att utlösas om "ConvertTo(string fileName)" eller ConvertTo(convertedStreamProvider)" är angivet.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertedFileStream | Action`1 | Leverantör av konverterad dokumentström Den [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Returvärde

Gränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
