---
title: "Compress"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Roep deze methode aan om de resultaten van de conversie te comprimeren. Registreer een compressedstream‑handler in de entry‑fase via WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents met de instelling OnCompressionCompleted."
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

Roep deze methode aan om de resultaten van de conversie te comprimeren. Registreer een compressed-stream‑handler in de entry‑fase via [`WithEvents`](../../iconversionsettings/withevents) (instelling `OnCompressionCompleted`).

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opties | CompressionConvertOptions | Compressie‑conversie‑opties |

### Retourwaarde

Continuatie die doorgaat naar `Convert`.

### Zie ook

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
