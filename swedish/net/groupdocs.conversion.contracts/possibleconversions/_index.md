---
title: "Möjliga konverteringar"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Representerar en mappning av vilka konverteringspar som stöds för ett specifikt källfilformat"
type: docs
weight: 510
url: /sv/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Representerar en mappning av vilka konverteringspar som stöds för ett specifikt källfilformat

```csharp
public sealed class PossibleConversions : ValueObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Alla målfiltyper och primär/sekundär flagga IEnumerable av [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Returnerar målkonvertering för angiven målfiltyp (2 indexerare) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Fördefinierade laddningsalternativ som kan användas för att konvertera från aktuell typ |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Primära målfiltyper |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Sekundära målfiltyper |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Källfilformat |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
