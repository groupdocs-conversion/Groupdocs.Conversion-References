---
title: "FontTransformations"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Transformera befintliga teckensnitt efter att dokumentet har lästs in och teckensnittssubstitution är klar. Teckensnittstransformationer kan ändra alla teckensnitt i dokumentet, inklusive teckensnitt som har laddats framgångsrikt."
type: docs
weight: 160
url: /sv/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations/
---
## WordProcessingLoadOptions.FontTransformations property

Transformera befintliga teckensnitt efter att dokumentet har laddats och teckensnittsersättning är klar. Teckensnittstransformationer kan ändra alla teckensnitt i dokumentet, inklusive teckensnitt som laddades framgångsrikt.

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### Anmärkningar

**Note:** Font transformations are applied after all font substitution steps are complete.

Transformationer bearbetas i den ordning de visas i listan.

Användningsfall: Stiländringar, varumärkeskrav, förbättringar av tillgänglighet.

### Se även

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
