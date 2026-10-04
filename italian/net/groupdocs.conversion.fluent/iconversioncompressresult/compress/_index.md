---
title: "Compress"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Chiama questo metodo per comprimere i risultati della conversione. Registra un handler compressedstream nella fase di ingresso tramite WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents impostazione OnCompressionCompleted."
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

Registra un handler compressed-stream nella fase di ingresso tramite [`WithEvents`](../../iconversionsettings/withevents) (impostazione `OnCompressionCompleted`).

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| opzioni | CompressionConvertOptions | Opzioni di conversione della compressione |

### Valore restituito

Continuazione che procede a `Convert`.

### IConversionConvertOptions

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
