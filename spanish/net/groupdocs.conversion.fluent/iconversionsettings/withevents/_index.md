---
title: "WithEvents"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Registre controladores de eventos del ciclo de vida de la conversión en una bolsa ConversionEventsgroupdocs.conversion/conversionevents que vive durante la vida útil del convertidor y se dispara en cada ejecución de conversión. Se sitúa en la misma etapa de entrada que WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Las llamadas múltiples acumulan la misma bolsa interna que se pasa a cada acción configure, de modo que los controladores establecidos en llamadas anteriores sobreviven a menos que sean sobrescritos por una posterior."
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Registre controladores de eventos del ciclo de vida de la conversión en una bolsa [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) que vive durante la vida útil del convertidor y se dispara en cada ejecución de conversión. Se sitúa en la misma etapa de entrada que [`WithSettings`](../withsettings). Las llamadas múltiples acumulan: la misma bolsa interna se pasa a cada acción *configure*, de modo que los controladores establecidos en llamadas anteriores sobreviven a menos que sean sobrescritos por una posterior.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| configure | Action`1 | Acción que muta la bolsa de eventos. |

### Valor de retorno

La etapa de selección de origen para que `Load` pueda encadenarse.

### Ver también

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
