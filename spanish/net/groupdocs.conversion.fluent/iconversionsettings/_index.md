---
title: "IConversionSettings"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Configura la configuración de conversión o eventos en la etapa de entrada antes de Load."
type: docs
weight: 1540
url: /es/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Configura la configuración de conversión o eventos en la etapa de entrada (antes de `Load`).

```csharp
public interface IConversionSettings
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Registra controladores de eventos del ciclo de vida de la conversión en una bolsa [`ConversionEvents`](../../groupdocs.conversion/conversionevents) que vive durante la vida útil del conversor y se dispara en cada ejecución de conversión. Se sitúa en la misma etapa de entrada que [`WithSettings`](./withsettings). Las llamadas múltiples se acumulan: la misma bolsa interna se pasa a cada acción *configure*, de modo que los controladores establecidos en llamadas anteriores sobreviven a menos que sean sobrescritos por una posterior. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Establecer la configuración del conversor |

### Ver también

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
