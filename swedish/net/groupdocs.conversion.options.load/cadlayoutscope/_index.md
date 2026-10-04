---
title: "CadLayoutScope"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Representerar vilka ritningsutrymmen en CAD-konvertering väljer: modellutrymmet, pappersutrymmeslayouterna eller båda."
type: docs
weight: 2420
url: /sv/net/groupdocs.conversion.options.load/cadlayoutscope/
---
## CadLayoutScope class

Representerar vilka ritningsutrymmen en CAD‑konvertering väljer: modellutrymmet, pappersutrymmeslayouterna eller båda.

```csharp
public class CadLayoutScope : Enumeration
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Both](../../groupdocs.conversion.options.load/cadlayoutscope/both) | Väljer modellutrymmet och varje pappersutrymmeslayout. Detta är standardvärdet och det begränsar inte konverteringen: ritningen renderas exakt som den är när ingen omfattning uttrycks. |
| static readonly [Layouts](../../groupdocs.conversion.options.load/cadlayoutscope/layouts) | Väljer endast pappersutrymmeslayouterna. Modellutrymmet utesluts. |
| static readonly [Model](../../groupdocs.conversion.options.load/cadlayoutscope/model) | Väljer endast modellutrymmet. |

### Se även

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
