---
title: "FontTransformation"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Beschrijft de configuratie voor lettertype-transformatie inclusief lettertype-attributen. Lettertype-transformaties worden toegepast na het laden van het document en de lettertypevervanging."
type: docs
weight: 260
url: /nl/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Beschrijft de configuratie voor lettertype-transformatie inclusief lettertype-attributen. Lettertype-transformaties worden toegepast na het laden van het document en de lettertypevervanging.

```csharp
public class FontTransformation : ValueObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | Wanneer true, komt elke lettergrootte overeen voor de oorspronkelijke lettertype‑naam. Wanneer false, komt de exacte lettergrootte overeen die is opgegeven in OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | Wanneer true, komt elke lettertype‑stijl (vet, cursief, onderstrepen) overeen voor het oorspronkelijke lettertype. Wanneer false, komt de exacte lettertype‑stijl overeen die is opgegeven in OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | De oorspronkelijke lettertype‑specificatie om te matchen en te vervangen. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | De vervangende lettertype‑specificatie. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Creëert een lettertype‑transformatie met exacte lettertype‑matching (grootte en stijl moeten overeenkomen). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Creëert een lettertype‑transformatie alleen op naam, waarbij elke grootte en stijl overeenkomt. Het vervangende lettertype behoudt de grootte en stijl van het oorspronkelijke lettertype. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Creëert een lettertype‑transformatie met flexibele matching‑opties. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
