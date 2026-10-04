---
title: "BitmapInfo"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Objekt som innehåller en matris av pixlar och bitmapinformation."
type: docs
weight: 70
url: /sv/net/groupdocs.conversion.contracts/bitmapinfo/
---
## BitmapInfo class

Objekt som innehåller en matris av pixlar och bitmapinformation.

```csharp
public class BitmapInfo : ValueObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.contracts/bitmapinfo/format) { get; } | Hämtar bildpunktsformatet för bitmapen. |
| [Height](../../groupdocs.conversion.contracts/bitmapinfo/height) { get; } | Hämtar höjden på bitmapen. |
| [PixelBytes](../../groupdocs.conversion.contracts/bitmapinfo/pixelbytes) { get; } | Hämtar arrayen av bildpunkter. |
| [Width](../../groupdocs.conversion.contracts/bitmapinfo/width) { get; } | Hämtar bredden på bitmapen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/bitmapinfo/create)(byte[], int, int, PixelFormat) | Skapa ny BitmapInfo-instans |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [PixelFormat](bitmapinfo.pixelformat) | Beskriver uppräkning av pixelformat |

### Se även

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
