---
title: "OnConversionCompleted"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito. Reinvocar reemplaza cualquier controlador previamente establecido."
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito. Volver a invocar reemplaza cualquier controlador previamente establecido.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onCompleted | Action`1 | Una acción para manejar la finalización, recibiendo el contexto de conversión. |

### Valor de retorno

Esta etapa, por lo que se pueden encadenar controladores adicionales o `Convert` / `Compress`.

### Ver también

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
