---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Representerar alternativ som stödjer sidstorlek"
type: docs
weight: 2990
url: /sv/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Representerar alternativ som stödjer sidstorlek

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Standardkonstruktor. Initierar [`PageSize`](./pagesize) till [`Unset`](../pagesize/unset). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Sidans höjd i punkter som ska tillämpas före konvertering. När den är angiven ändras [`PageSize`](./pagesize) automatiskt till [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Implementerar [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Sidans bredd i punkter som ska tillämpas före konvertering. När den är angiven ändras [`PageSize`](./pagesize) automatiskt till [`Custom`](../pagesize/custom). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
