---
title: "FontTransformation"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Beskriver konfiguration för teckensnittstransformation inklusive teckensnittsattribut. Teckensnittstransformationer tillämpas efter dokumentladdning och teckensnittssubstitution."
type: docs
weight: 260
url: /sv/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Beskriver konfiguration för teckensnittstransformation inklusive teckensnittsattribut. Teckensnittstransformationer tillämpas efter dokumentladdning och teckensnittssubstitution.

```csharp
public class FontTransformation : ValueObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | När true, matchar vilken teckenstorlek som helst för det ursprungliga teckensnittsnamnet. När false, matchar exakt teckenstorlek som anges i OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | När true, matchar vilken teckensnittsstil som helst (fet, kursiv, understruken) för det ursprungliga teckensnittet. När false, matchar exakt teckensnittsstil som anges i OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | Den ursprungliga teckensnittsspecifikationen att matcha och ersätta. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | Den ersättande teckensnittsspecifikationen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Skapar en teckensnittstransformation med exakt teckenmatchning (storlek och stil måste matcha). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Skapar en teckensnittstransformation enbart efter namn, som matchar vilken storlek och stil som helst. Det ersättande teckensnittet kommer bevara det ursprungliga teckensnittets storlek och stil. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Skapar en teckensnittstransformation med flexibla matchningsalternativ. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
