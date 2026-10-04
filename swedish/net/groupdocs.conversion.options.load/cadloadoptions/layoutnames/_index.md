---
title: "LayoutNames"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Anger vilka CAD‑layouter som ska konverteras"
type: docs
weight: 70
url: /sv/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Anger vilka CAD‑layouter som ska konverteras

```csharp
public string[] LayoutNames { get; set; }
```

### Anmärkningar

Respekteras inte vid konvertering till PDF/UA-1. Det målet renderar ritningen som en enda taggad sida, vilket inte kan innehålla ett blad per valt layout, så hela ritningen konverteras istället och inget här gäller för den. Alla andra mål, inklusive PDF, respekterar urvalet. På dessa mål matchas namn exakt mot de layouter som ritningen innehåller, så ett namn som bara skiljer sig i versal/gemen är ett annat namn. Ett namn som inte matchar något släpps och kostar anroparen endast det bladet; en lista där inget matchar får konverteringen att misslyckas med ett [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) som namnger de namn som saknades och de layouter som ritningen faktiskt har, snarare än att rendera blad som anroparen inte begärde. En ritning som inte innehåller några layouter alls är undantagen: det finns inget för ett namn att matcha, så inget avvisas.

### Se även

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
