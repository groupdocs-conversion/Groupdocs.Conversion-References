---
title: "IConversionByPageHandlersStage"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Etapa de controladores de conversión aplanada por página. Espejo por página de IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /es/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Etapa de controladores de conversión aplanada por página. Espejo por página de [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Registra una devolución de llamada que se invocará cuando una conversión de página se complete con éxito. Reinvocar reemplaza cualquier controlador previamente establecido. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Registra una devolución de llamada que se invocará cuando una conversión de página falle. Reinvocar reemplaza cualquier controlador previamente establecido. |

### Ver también

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
