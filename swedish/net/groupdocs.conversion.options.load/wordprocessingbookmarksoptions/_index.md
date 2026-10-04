---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att hantera bokmärken i WordProcessing"
type: docs
weight: 2930
url: /sv/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

Alternativ för att hantera bokmärken i WordProcessing

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | Anger standardnivån i dokumentöversikten där Word-bokmärken ska visas. Standard är 0. Giltigt intervall är 0 till 9. |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | Anger hur många nivåer i dokumentöversikten som ska visas utökade när filen visas. Standard är 0. Giltigt intervall är 0 till 9. Observera att detta alternativ inte fungerar vid sparande till XPS. |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | Anger hur många nivåer av rubriker (paragrafer formaterade med rubrikstilar) som ska inkluderas i dokumentöversikten. Standard är 0. Giltigt intervall är 0 till 9. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
