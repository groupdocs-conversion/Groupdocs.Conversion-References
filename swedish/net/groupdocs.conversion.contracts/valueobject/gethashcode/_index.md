---
title: "GetHashCode"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Fungerar som standardhash-funktion."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

Fungerar som standardhash-funktion.

```csharp
public override int GetHashCode()
```

### Returvärde

En hashkod för det aktuella objektet.

### Anmärkningar

Array-, lista- och dictionarykomponenter hash‑as efter deras innehåll, i enlighet med hur likhet jämför dem, så två objekt som jämförs som lika hash‑as också lika och kan användas som nycklar i dictionary eller som medlemmar i en mängd. Detta gäller INTE för en komponent som är någon annan IEnumerable: en sådan komponent hash‑as efter referens, och en som exponeras som en lazy‑iterator ger ett annat värde vid varje åtkomst, så ett objekt som bär den kan inte användas som nyckel alls. Inbäddade samlingar jämförs och hash‑as också efter referens snarare än rekursivt. En annan följd är att mutera en samling som ett värdeobjekt exponerar – lägga till i en sidlista eller skriva in i en layout‑namn‑array – ändrar objektets hash, så en instans som redan lagrats i en hash‑behållare blir oåtkomlig. Behandla ett värdeobjekt som fryst när det har använts som nyckel.

### Se även

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
