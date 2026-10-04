---
title: "EBookFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar EBook-dokument. Inkluderar följande filtyper Epub./ebookfiletype/epubMobi./ebookfiletype/mobiAzw3./ebookfiletype/azw3"
type: docs
weight: 1110
url: /sv/net/groupdocs.conversion.filetypes/ebookfiletype/
---
## EBookFileType class

Definierar EBook-dokument. Inkluderar följande filtyper: [`Epub`](./epub)[`Mobi`](./mobi)[`Azw3`](./azw3)

```csharp
public sealed class EBookFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EBookFileType](ebookfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementerar [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Azw3](../../groupdocs.conversion.filetypes/ebookfiletype/azw3) | AZW3, även känt som Kindle Format 8 (KF8), är den modifierade versionen av det digitala AZW‑ebook‑filformatet som utvecklats för Amazon Kindle‑enheter. Formatet är en förbättring av äldre AZW‑filer och används på Kindle Fire‑enheter endast med bakåtkompatibilitet för det föregående filformatet, dvs. MOBI och AZW. Läs mer om detta filformat [här](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.conversion.filetypes/ebookfiletype/epub) | EPUB‑extensionen är ett e‑bok‑filformat som tillhandahåller ett standardiserat digitalt publiceringsformat för utgivare och konsumenter. Formatet har blivit så vanligt nu att det stöds av många e‑läsare och programvaror. Läs mer om detta filformat [här](https://wiki.fileformat.com/ebook/epub). |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/ebookfiletype/mobi) | MOBI‑filformatet är ett av de mest använda e‑bok‑filformaten. Formatet är en förbättring av det gamla OEB (Open Ebook Format)-formatet och användes som proprietärt format för Mobipocket Reader. Läs mer om detta filformat [här](https://wiki.fileformat.com/ebook/mobi). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
