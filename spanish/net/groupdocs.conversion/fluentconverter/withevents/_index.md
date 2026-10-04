---
title: "WithEvents"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Variante de etapa de entrada de la cadena fluida que comienza con controladores de eventos del ciclo de vida de la conversión. Se sitúa en la misma etapa de entrada que WithSettingsgroupdocs.conversion/fluentconverter/withsettings y el contenedor ConversionEventsgroupdocs.conversion/conversionevents resultante se dispara en cada ejecución de conversión del convertidor."
type: docs
weight: 20
url: /es/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Variante de etapa de entrada de la cadena fluida que comienza con controladores de eventos del ciclo de vida de la conversión. Se sitúa en la misma etapa de entrada que [`WithSettings`](../withsettings), y el contenedor resultante [`ConversionEvents`](../../conversionevents) se dispara en cada ejecución de conversión del convertidor.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| configure | Action`1 | Acción que muta la bolsa de eventos. |

### Valor de retorno

La etapa de selección de origen para que `Load` pueda encadenarse.

### Ver también

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
