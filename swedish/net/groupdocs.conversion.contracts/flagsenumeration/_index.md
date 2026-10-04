---
title: "FlagsEnumeration"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Representerar en abstrakt basklass för att skapa uppräkningar som stödjer bitvisa flaggoperationer."
type: docs
weight: 220
url: /sv/net/groupdocs.conversion.contracts/flagsenumeration/
---
## FlagsEnumeration class

Representerar en abstrakt basklass för att skapa uppräkningar som stödjer bitvisa flaggoperationer.

```csharp
public abstract class FlagsEnumeration : Enumeration
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Kontrollerar om den aktuella flaggan har den angivna flaggan. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Kontrollerar om den aktuella flaggan har det angivna värdet. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Konverterar det aktuella objektet till en sträng. |
| static [Combine&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/combine)(T, T) | Kombinerar två flagguppräkningar till en. |

### Se även

* class [Enumeration](../enumeration)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
