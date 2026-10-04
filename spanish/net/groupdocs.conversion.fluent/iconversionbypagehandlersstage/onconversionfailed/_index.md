---
title: "OnConversionFailed"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Registra una devolución de llamada que se invocará cuando falle una conversión de página. Reinvocar reemplaza cualquier controlador previamente establecido."
type: docs
weight: 20
url: /es/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Registra una devolución de llamada que se invocará cuando una conversión de página falle. Reinvocar reemplaza cualquier controlador previamente establecido.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onFailed | Action`2 | Una acción para manejar el error, recibiendo el contexto de la página convertida y la excepción que provocó el error. |

### Valor de retorno

Esta etapa, por lo que se pueden encadenar controladores adicionales o `Convert` / `Compress`.

### Ver también

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
