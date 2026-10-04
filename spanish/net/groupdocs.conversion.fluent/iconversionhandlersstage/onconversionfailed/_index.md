---
title: "OnConversionFailed"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de documento falle. Reinvocar reemplaza cualquier controlador previamente establecido."
type: docs
weight: 20
url: /es/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Registra una devolución de llamada que se invocará cuando una conversión de documento falle. Volver a invocar reemplaza cualquier controlador previamente establecido.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onFailed | Action`2 | Una acción para manejar la falla, recibiendo el contexto de conversión y la excepción que causó la falla. |

### Valor de retorno

Esta etapa, por lo que se pueden encadenar controladores adicionales o `Convert` / `Compress`.

### Ver también

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
