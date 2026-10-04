---
title: "LayoutScope"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Haalt op of stelt in welke tekenruimtes worden geconverteerd. Standaard is Bothgroupdocs.conversion.options.load/cadlayoutscope/both, wat de conversie niet beperkt. Wordt genegeerd wanneer LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames wordt opgegeven, omdat expliciete lay-outnamen altijd prevaleren. Een null-waarde wordt behandeld als Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /nl/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Haalt op of stelt in welke tekenruimtes worden geconverteerd. Standaard is [`Both`](../../cadlayoutscope/both), wat de conversie niet beperkt. Wordt genegeerd wanneer [`LayoutNames`](../layoutnames) wordt opgegeven, omdat expliciete lay-outnamen altijd prevaleren. Een `null`-waarde wordt behandeld als [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Opmerkingen

Een scope die geen van de bladen selecteert die een tekening aanbiedt, laat de conversie falen met een [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) die de scope en de aanwezige bladen benoemt, in plaats van de ruimtes te renderen die de scope uitsluit. Een tekening die helemaal geen blad aanbiedt, blijft onaangetast en wordt nog steeds als één enkele eenheid geconverteerd. Wordt niet gerespecteerd bij het converteren naar PDF/UA-1, om de reden die wordt gegeven bij [`LayoutNames`](../layoutnames).

### Zie ook

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
