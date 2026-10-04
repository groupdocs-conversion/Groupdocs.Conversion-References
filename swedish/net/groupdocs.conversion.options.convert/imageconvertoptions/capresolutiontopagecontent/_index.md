---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "När den är inställd begränsar den PDF‑renderingsupplösningen per sida till sidans inhemska rasterupplösning så att en sida aldrig renderas med en högre DPI än den inbäddade bilden faktiskt har, och sidan exporteras med dess inhemska mindre pixelmått och inhemska DPI i det slutliga resultatet istället för att återuppblåsa den till den begärda DPI:n. Endast bild‑dominerade skanningssidor påverkas; sidor med text eller vektor­innehåll mjukas aldrig upp och exporteras med den begärda DPI:n. Hoppar över när en explicit utdata‑Widthgroupdocs.conversion.options.convert/imageconvertoptions/width eller Heightgroupdocs.conversion.options.convert/imageconvertoptions/height är angiven. Standardvärdet är false ingen begränsning; varje sida renderas och exporteras med den begärda DPI:n."
type: docs
weight: 40
url: /sv/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

När den är inställd begränsar den PDF‑renderingsupplösningen per sida till sidans inhemska rasterupplösning så att en sida aldrig renderas med en högre DPI än den inbäddade bilden faktiskt har, och sidan exporteras med dess inhemska (småare) pixelmått och inhemska DPI i det slutliga resultatet istället för att återuppblåsa den till den begärda DPI:n. Endast bild‑dominerade (skannade) sidor påverkas; sidor med text eller vektor­innehåll mjukas aldrig upp och exporteras med den begärda DPI:n. Hoppar över när en explicit utdata‑[`Width`](../width) eller [`Height`](../height) är angiven. Standardvärdet är `false` (ingen begränsning; varje sida renderas och exporteras med den begärda DPI:n).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### Se även

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
