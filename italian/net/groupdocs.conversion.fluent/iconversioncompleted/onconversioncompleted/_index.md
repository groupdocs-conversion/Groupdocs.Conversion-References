---
title: "OnConversionCompleted"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Ricevi lo stream del documento convertito. Verrà attivato solo se ConvertTostring fileName o ConvertToconvertedStreamProvider è impostato."
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

IConversionIsPasswordProtected

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertedFileStream | Action`1 | Provider di stream del documento convertito Il [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Valore restituito

Interfaccia per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
