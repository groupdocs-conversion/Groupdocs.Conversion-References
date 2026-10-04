---
title: "Rektangel"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Representerar en rektangel definierad av sina kanter för beskärningsändamål."
type: docs
weight: 580
url: /sv/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Representerar en rektangel definierad av sina kanter för beskärningsändamål.

```csharp
public sealed class Rectangle : ValueObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Initierar en ny instans av strukturen [`Rectangle`](../rectangle) med angivna kanter. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Hämtar den nedre kanten av rektangeln. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Hämtar höjden på rektangeln baserat på övre och nedre kanter. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Hämtar den vänstra kanten av rektangeln. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Hämtar den högra kanten av rektangeln. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Hämtar den övre kanten av rektangeln. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Hämtar bredden på rektangeln baserat på vänster och höger kant. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Skapar en beskuren version av den aktuella rektangeln genom att ta bort angivna marginaler. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Returnerar en strängrepresentation av rektangeln. |

### Se även

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
