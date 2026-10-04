---
title: "OnConversionCompleted"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Recibe el flujo del documento convertido. Se disparará solo si se establece ConvertTostring fileName o ConvertToconvertedStreamProvider."
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Reciba el flujo del documento convertido. Se disparará solo si "ConvertTo(string fileName)" o ConvertTo(convertedStreamProvider)" está configurado.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertedFileStream | Action`1 | Proveedor de flujo de documento convertido El [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Valor de retorno

Interfaz para continuar la construcción de la conversión

### Ver también

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
