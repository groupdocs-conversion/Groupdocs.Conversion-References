---
title: "WithOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Establece opciones de conversión para el proceso de conversión."
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Establece opciones de conversión para el proceso de conversión.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opciones de conversión. |

### Valor de retorno

Etapa de controladores para continuar la construcción de la conversión.

### Ver también

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Establece opciones de conversión usando una función proveedora.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optionsProvider | Func`2 | Una función que proporciona opciones de conversión basadas en el contexto de conversión. |

### Valor de retorno

Etapa de controladores para continuar la construcción de la conversión.

### Ver también

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
