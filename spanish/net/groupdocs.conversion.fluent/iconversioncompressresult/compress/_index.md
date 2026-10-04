---
title: "Compress"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Llame a este método para comprimir los resultados de la conversión. Registre un controlador compressedstream en la etapa de entrada mediante WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents configurando OnCompressionCompleted."
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

Llame a este método para comprimir los resultados de la conversión. Registre un controlador compressed-stream en la etapa de entrada mediante [`WithEvents`](../../iconversionsettings/withevents) (configuración `OnCompressionCompleted`).

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | CompressionConvertOptions | Opciones de conversión de compresión |

### Valor de retorno

Continuación que procede a `Convert`.

### Ver también

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
