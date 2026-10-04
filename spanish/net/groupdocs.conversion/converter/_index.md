---
title: "Converter"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Representa la clase principal que controla el proceso de conversión de documentos."
type: docs
weight: 890
url: /es/net/groupdocs.conversion/converter/
---
## Converter class

Representa la clase principal que controla el proceso de conversión de documentos.

```csharp
public sealed class Converter : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter). |
| [Converter](converter#constructor_5)(string) | Inicializa una nueva instancia de la clase [`Converter`](../converter). |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter). |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter). |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter) con eventos de conversión explícitos. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter). |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter) con eventos de conversión explícitos. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter). |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter) con eventos de conversión explícitos. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inicializa una nueva instancia de la clase [`Converter`](../converter) con eventos de conversión explícitos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Libera los recursos. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Obtiene información del documento fuente: recuento de páginas y otras propiedades del documento específicas del tipo de archivo. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Obtiene información del documento fuente: recuento de páginas y otras propiedades del documento específicas del tipo de archivo. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Obtiene conversiones posibles para el documento fuente. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Comprueba si el documento de origen está protegido con contraseña |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Obtiene todas las conversiones compatibles |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Obtiene las conversiones compatibles para la extensión de documento proporcionada |

### Ejemplos

**Basic conversion from file path:**

```csharp
// Convertir DOCX a PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Convertir DOCX a PDF con marca de agua y rango de páginas específico
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions
    {
        PageNumber = 1,
        PagesCount = 3,
        Watermark = new WatermarkTextOptions("CONFIDENTIAL")
        {
            Color = System.Drawing.Color.Red,
            Width = 300,
            Height = 100
        }
    };
    converter.Convert("output.pdf", options);
}
```

**Conversion from stream:**

```csharp
// Convertir documento de flujo a flujo
using (var sourceStream = File.OpenRead("sample.docx"))
using (var converter = new Converter(() => sourceStream))
using (var outputStream = File.Create("output.pdf"))
{
    var options = new PdfConvertOptions();
    converter.Convert((SaveContext context) => outputStream, options);
}
```

**Conversion with load options (password-protected document):**

```csharp
// Cargar documento protegido con contraseña y convertir a PDF
var loadOptions = new WordProcessingLoadOptions
{
    Password = "secret_password"
};
using (var converter = new Converter("protected.docx", (LoadContext context) => loadOptions))
{
    var convertOptions = new PdfConvertOptions();
    converter.Convert("output.pdf", convertOptions);
}
```

**Page-by-page conversion:**

```csharp
// Convertir páginas del documento a archivos de imagen separados
using (var converter = new Converter("sample.pdf"))
{
    var options = new ImageConvertOptions
    {
        Format = ImageFileType.Png
    };

    converter.Convert(
        (SavePageContext context) => File.Create($"page-{context.Page}.png"),
        options
    );
}
```

**Registering conversion event handlers (recommended path):**

```csharp
// Agrupa todos los controladores de eventos en un contenedor ConversionEvents y pásalo al Converter.
var events = new ConversionEvents
{
    OnDocumentConverted = ctx       => Console.WriteLine($"Done: {ctx.SourceFileName}"),
    OnDocumentFailed    = (ctx, ex) => Console.Error.WriteLine($"Conversion of {ctx.SourceFileName} failed: {ex.Message}"),
    OnPageFailed        = (ctx, ex) => Console.Error.WriteLine($"Page {ctx.Page} of {ctx.SourceFileName} failed: {ex.Message}"),
};
using (var converter = new Converter("sample.docx", () => new ConverterSettings(), () => events))
{
    converter.Convert("output.pdf", new PdfConvertOptions());
}
```

Las propiedades planas `OnConversionFailed`, `OnConversionByPageFailed` y `OnCompressionCompleted` en [`ConverterSettings`](../convertersettings) siguen funcionando pero están obsoletas; el nuevo código debe pasar una instancia de [`ConversionEvents`](../conversionevents) mediante el parámetro del constructor `events`.

**Get document information:**

```csharp
// Recuperar los metadatos del documento antes de la conversión
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Ver también

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
