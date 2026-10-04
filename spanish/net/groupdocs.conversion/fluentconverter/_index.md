---
title: "FluentConverter"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Clase para la configuración fluida de la conversión."
type: docs
weight: 1580
url: /es/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Clase para la configuración fluida de la conversión.

```csharp
public static class FluentConverter
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Configura la secuencia del documento fuente |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Configura el conjunto de secuencias de documentos fuente |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Configura el documento fuente para la conversión |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Configura el conjunto de documentos fuente |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Variante de etapa de entrada de la cadena fluida que comienza con controladores de eventos del ciclo de vida de la conversión. Se sitúa en la misma etapa de entrada que [`WithSettings`](./withsettings), y la bolsa resultante de [`ConversionEvents`](../conversionevents) se dispara en cada ejecución de conversión por el convertidor. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Configura los ajustes de conversión |

### Observaciones

Ejemplo de uso de conversión fluida:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Recomendado: agregar controladores mediante WithEvents en la etapa temprana (antes de Load).
FluentConverter
    .WithEvents(e =>
    {
        e.OnDocumentConverted = ctx       => Console.WriteLine($"Done: {ctx.SourceFileName}");
        e.OnDocumentFailed    = (ctx, ex) => Console.Error.WriteLine(ex.Message);
    })
    .Load("input.docx")
    .ConvertTo("output.pdf").WithOptions(new PdfConvertOptions())
    .Convert();
```

```csharp
// Espejo por página: controladores por página mediante WithEvents en la etapa temprana.
FluentConverter
    .WithEvents(e =>
    {
        e.OnPageConverted = ctx       => Console.WriteLine($"page {ctx.Page} done");
        e.OnPageFailed    = (ctx, ex) => Console.Error.WriteLine($"page {ctx.Page}: {ex.Message}");
    })
    .Load("input.pdf")
    .ConvertByPageTo(ctx => new FileStream($"page-{ctx.Page}.png", FileMode.Create))
    .WithOptions(new ImageConvertOptions { Format = ImageFileType.Png })
    .Convert();
```

```csharp
// La cadena heredada aún se compila sin cambios (ahora respaldada por las interfaces escalonadas obsoletas):
FluentConverter.WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
FluentConverter.Load("").GetPossibleConversions();
FluentConverter.Load("").GetDocumentInfo();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### Ver también

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
