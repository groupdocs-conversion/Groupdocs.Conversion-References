---
title: "WithOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Establecer opciones de conversión"
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Establecer opciones de conversión

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opciones de conversión |

### Valor de retorno

Interfaz para continuar la construcción de la conversión

### Ver también

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Establecer opciones de conversión

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Descripción |
| --- | --- |
| convertOptionsProvider | Proveedor de opciones de conversión |
| convertOptionsProvider arg1arg1 | El [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Valor de retorno

Interfaz para continuar la construcción de la conversión

### Ver también

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
