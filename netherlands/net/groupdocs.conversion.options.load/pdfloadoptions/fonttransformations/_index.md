---
title: "FontTransformations"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Transformeer bestaande lettertypen nadat het document is geladen en de lettertypevervanging voltooid is. Lettertype-transformaties kunnen alle lettertypen in het document wijzigen, inclusief lettertypen die succesvol zijn geladen."
type: docs
weight: 100
url: /nl/net/groupdocs.conversion.options.load/pdfloadoptions/fonttransformations/
---
## PdfLoadOptions.FontTransformations property

Transformeer bestaande lettertypen nadat het document is geladen en de lettertypevervanging voltooid is. Lettertype‑transformaties kunnen alle lettertypen in het document wijzigen, inclusief lettertypen die succesvol geladen zijn.

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### Opmerkingen

**Note:** Font transformations are applied after all font substitution steps are complete.

Transformaties worden verwerkt in de volgorde waarin ze in de lijst verschijnen.

Gebruikssituaties: stijlwijzigingen, merkvereisten, toegankelijkheidsverbeteringen.

### Zie ook

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [PdfLoadOptions](../../pdfloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
