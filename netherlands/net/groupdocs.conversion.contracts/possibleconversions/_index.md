---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stelt een mapping voor van welke conversieparen worden ondersteund voor een specifiek bronbestandformaat"
type: docs
weight: 510
url: /nl/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Stelt een mapping voor van welke conversieparen worden ondersteund voor een specifiek bronbestandformaat

```csharp
public sealed class PossibleConversions : ValueObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Alle doelbestandstypen en primaire/secundaire vlag IEnumerable van [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Retourneert doelconversie voor opgegeven doelbestandstype (2 indexers) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Vooraf gedefinieerde laadopties die kunnen worden gebruikt om te converteren vanaf het huidige type |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Primaire doelbestandstypen |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Secundaire doelbestandstypen |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Bronbestandformaten |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
