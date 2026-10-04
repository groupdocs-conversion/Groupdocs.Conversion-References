---
title: "IConversionHandlersStage"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Etapa de controladores de conversión aplanada. Permite establecer OnConversionCompleted o OnConversionFailed en cualquier orden y cualquier número de veces antes de proceder a Convert / Compress. Los eventos deben registrarse en la etapa temprana mediante WithEvents./iconversionsettings/withevents en lugar de en esta etapa."
type: docs
weight: 1480
url: /es/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Etapa de controladores de conversión aplanada. Permite establecer `OnConversionCompleted` o `OnConversionFailed` en cualquier orden y cualquier número de veces, antes de proceder a `Convert` / `Compress`. Los eventos deben registrarse en la etapa temprana mediante [`WithEvents`](../iconversionsettings/withevents) en lugar de en esta etapa.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito. Volver a invocar reemplaza cualquier controlador previamente establecido. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Registra una devolución de llamada que se invocará cuando una conversión de documento falle. Volver a invocar reemplaza cualquier controlador previamente establecido. |

### Ver también

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
