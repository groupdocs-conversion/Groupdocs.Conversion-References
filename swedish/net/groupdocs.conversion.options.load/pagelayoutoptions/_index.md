---
title: "PageLayoutOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Beskriver sidlayoutlägen när webbdokument läses in."
type: docs
weight: 2720
url: /sv/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Beskriver sidlayoutlägen när webbdokument läses in.

```csharp
public class PageLayoutOptions : FlagsEnumeration
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
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | Kombinerar två [`PageLayoutOptions`](../pagelayoutoptions)-flaggor med bitvis OR. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | Standardvärde |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | Denna flagga indikerar att dokumentets innehåll kommer att skalas för att passa höjden på den första sidan. Allt dokumentinnehåll kommer endast att placeras på en enda sida. |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | Indikerar att dokumentets innehåll kommer att skalas för att passa sidan där skillnaden mellan den tillgängliga sidbredden och det överlappande innehållet är störst. |

### Se även

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
