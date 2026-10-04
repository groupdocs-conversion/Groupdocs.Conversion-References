---
title: "WithOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Establecer opciones de conversión"
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Establecer opciones de conversión

```csharp
public IConversionByPageHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opciones de conversión |

### Valor de retorno

Interfaz para continuar la construcción de la conversión

### Ver también

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Establecer opciones de conversión

```csharp
public IConversionByPageHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Opciones de conversión El [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Valor de retorno

Interfaz para continuar la construcción de la conversión

### Ver también

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
