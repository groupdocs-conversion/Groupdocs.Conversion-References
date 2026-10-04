---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Argumenten doorgegeven aan ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /nl/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Argumenten doorgegeven aan [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Bestandsnaam (of placeholder-id) ingebed als de afbeeldings-URI in de Markdown-uitvoer. Toewijzen om de URI te herschrijven. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Doelstream waarin de converter de afbeeldingsbytes schrijft nadat deze callback terugkeert. Vervang deze door je eigen schrijfbare stream (bijv. een FileStream voor schijfopslag of een MemoryStream die je later wilt lezen). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | Wanneer false (standaard), sluit de converter [`ImageStream`](./imagestream) na het schrijven — gebruikelijk voor FileStream-vervangingen die naar schijf moeten worden geflusht. Stel in op true om de stream open te houden nadat de conversie is voltooid (typisch voor een MemoryStream die je zelf wilt lezen); de aanroeper is dan verantwoordelijk voor het vrijgeven. |

### Zie ook

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
