---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Wanneer ingesteld, beperkt het de per‑pagina PDF‑renderresolutie tot de native rasterresolutie van de pagina zodat een pagina nooit wordt gerenderd op een hogere DPI dan de ingesloten afbeelding daadwerkelijk bevat en wordt die pagina uitgegeven met zijn native kleinere pixelafmetingen en native DPI in de uiteindelijke output in plaats van deze opnieuw op te blazen naar de gevraagde DPI. Alleen door afbeeldingen gedomineerde scanpagina's worden beïnvloed; pagina's met tekst of vectorinhoud worden nooit verzacht en worden uitgegeven met de gevraagde DPI. Overgeslagen wanneer een expliciete output Widthgroupdocs.conversion.options.convert/imageconvertoptions/width of Heightgroupdocs.conversion.options.convert/imageconvertoptions/height is ingesteld. Standaard is `false` (geen begrenzing); elke pagina wordt gerenderd en uitgegeven met de gevraagde DPI."
type: docs
weight: 40
url: /nl/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

Wanneer ingesteld, beperkt het de per‑pagina PDF‑renderresolutie tot de native rasterresolutie van de pagina zodat een pagina nooit wordt gerenderd op een hogere DPI dan de ingesloten afbeelding daadwerkelijk bevat, en wordt die pagina uitgegeven met zijn native (kleinere) pixelafmetingen en native DPI in de uiteindelijke output in plaats van deze opnieuw op te blazen naar de gevraagde DPI. Alleen door afbeeldingen gedomineerde (scan) pagina's worden beïnvloed; pagina's met tekst of vectorinhoud worden nooit verzacht en worden uitgegeven met de gevraagde DPI. Overgeslagen wanneer een expliciete output [`Width`](../width) of [`Height`](../height) is ingesteld. Standaard is `false` (geen begrenzing; elke pagina wordt gerenderd en uitgegeven met de gevraagde DPI).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### Zie ook

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
