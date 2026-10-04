---
title: "Komprimera"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Anropa den här metoden för att komprimera resultatet av konverteringen. Registrera en compressedstream‑hanterare i inledningssteget via WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents‑inställning OnCompressionCompleted."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

Anropa den här metoden för att komprimera resultatet av konverteringen. Registrera en compressed-stream‑hanterare i inledningssteget via [`WithEvents`](../../iconversionsettings/withevents) (inställning `OnCompressionCompleted`).

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alternativ | CompressionConvertOptions | Komprimeringsalternativ för konvertering |

### Returvärde

Fortsättning som går vidare till `Convert`.

### Se även

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
