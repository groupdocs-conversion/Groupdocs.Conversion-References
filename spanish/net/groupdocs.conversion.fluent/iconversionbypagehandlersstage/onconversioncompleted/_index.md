---
title: "OnConversionCompleted"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de página se complete con éxito. Reinvocar reemplaza cualquier controlador previamente establecido."
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

Registra una devolución de llamada que se invocará cuando una conversión de página se complete con éxito. Reinvocar reemplaza cualquier controlador previamente establecido.

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onCompleted | Action`1 | Una acción para manejar la finalización, recibiendo el contexto de la página convertida. |

### Valor de retorno

Esta etapa, por lo que se pueden encadenar controladores adicionales o `Convert` / `Compress`.

### Ver también

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
