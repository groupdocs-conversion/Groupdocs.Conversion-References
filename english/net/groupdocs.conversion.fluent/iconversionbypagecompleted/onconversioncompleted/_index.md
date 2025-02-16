---
title: OnConversionCompleted
second_title: GroupDocs.Conversion for .NET API Reference
description: Receive converted page stream. Will be fired only if ConvertToconvertedStreamProvider is set.
type: docs
weight: 10
url: /net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Receive converted page stream. Will be fired only if "ConvertTo(convertedStreamProvider)" is set.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| convertedPageStream | Action`1 | Converted page stream provider The [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Return Value

Interface to continue conversion building

### See Also

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
