---
title: "FluentConverter"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Classe pour la configuration fluide de la conversion."
type: docs
weight: 1580
url: /fr/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Classe pour la configuration fluide de la conversion.

```csharp
public static class FluentConverter
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Configurer le flux du document source |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Configurer l'ensemble des flux de documents source |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Configurer le document source pour la conversion |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Configurer l'ensemble des documents source |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Variante d'étape d'entrée de la chaîne fluide qui commence avec les gestionnaires d'événements du cycle de vie de la conversion. Se situe au même stade d'entrée que [`WithSettings`](./withsettings), et le sac [`ConversionEvents`](../conversionevents) résultant se déclenche à chaque exécution de conversion par le convertisseur. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Configurer les paramètres de conversion |

### Remarques

Exemple d'utilisation fluide de la conversion :

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Recommandé : agréger les gestionnaires via WithEvents à un stade précoce (avant Load).
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
// Miroir par page : gestionnaires par page via WithEvents à un stade précoce.
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
// La chaîne héritée compile toujours inchangée (maintenant prise en charge par les interfaces stagées obsolètes) :
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

### Voir aussi

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
