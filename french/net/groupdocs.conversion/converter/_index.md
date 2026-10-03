---
title: "Converter"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Représente la classe principale qui contrôle le processus de conversion de documents."
type: docs
weight: 890
url: /fr/net/groupdocs.conversion/converter/
---
## Converter class

Représente la classe principale qui contrôle le processus de conversion de documents.

```csharp
public sealed class Converter : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter). |
| [Converter](converter#constructor_5)(string) | Initialise une nouvelle instance de la classe [`Converter`](../converter). |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter). |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter). |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter) avec des événements de conversion explicites. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter). |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter) avec des événements de conversion explicites. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter). |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter) avec des événements de conversion explicites. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialise une nouvelle instance de la classe [`Converter`](../converter) avec des événements de conversion explicites. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Convertit le document source. Enregistre le document converti complet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Convertit le document source. Enregistre le document converti complet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Convertit le document source. Enregistre le document converti complet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Convertit le document source. Enregistre le document converti complet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Convertit le document source. Enregistre le document converti complet. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Libère les ressources. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Obtient les informations du document source - nombre de pages et autres propriétés du document spécifiques au type de fichier. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Obtient les informations du document source - nombre de pages et autres propriétés du document spécifiques au type de fichier. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Obtient les conversions possibles pour le document source. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Vérifie si le document source est protégé par mot de passe |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Obtient toutes les conversions prises en charge |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Obtient les conversions prises en charge pour l'extension de document fournie |

### Exemples

**Basic conversion from file path:**

```csharp
// Convertir DOCX en PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Convertir DOCX en PDF avec filigrane et plage de pages spécifique
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
// Convertir le document d'un flux à un autre
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
// Charger un document protégé par mot de passe et le convertir en PDF
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
// Convertir les pages du document en fichiers image séparés
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
// Regroupez tous les gestionnaires d'événements dans un sac ConversionEvents et transmettez‑le au Converter.
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

Les propriétés plates `OnConversionFailed`, `OnConversionByPageFailed` et `OnCompressionCompleted` sur [`ConverterSettings`](../convertersettings) fonctionnent toujours mais sont obsolètes ; le nouveau code doit passer une instance de [`ConversionEvents`](../conversionevents) via le paramètre du constructeur `events`.

**Get document information:**

```csharp
// Récupérer les métadonnées du document avant la conversion
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Voir aussi

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
