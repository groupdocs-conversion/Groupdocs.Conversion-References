---
title: "OnConversionCompleted"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Recibir flujo de página convertido. Se disparará solo si ConvertToconvertedStreamProvider está configurado."
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Recibir flujo de página convertido. Se disparará solo si "ConvertTo(convertedStreamProvider)" está configurado.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertedPageStream | Action`1 | Proveedor de flujo de página convertido El [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Valor de retorno

Interfaz para continuar la construcción de la conversión

### Ver también

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
