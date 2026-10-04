---
title: "IConversionFrom"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Configurar la fuente para la conversión"
type: docs
weight: 1440
url: /es/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Configurar la fuente para la conversión

```csharp
public interface IConversionFrom
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Establecer flujo del documento fuente |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Establecer matriz de flujos de documentos fuente |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Establecer nombre de archivo del documento fuente |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Establecer matriz de documentos fuente |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Registre los controladores de eventos del ciclo de vida de la conversión en una bolsa [`ConversionEvents`](../../groupdocs.conversion/conversionevents) que vive durante la vida útil del convertidor y se dispara en cada ejecución de conversión. Puede llamarse antes o después de [`WithSettings`](../iconversionsettings/withsettings). Las llamadas múltiples se acumulan: la misma bolsa interna se pasa a cada acción *configure*, por lo que los controladores establecidos en llamadas anteriores sobreviven a menos que sean sobrescritos por una posterior. |

### Ver también

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
