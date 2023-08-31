---
title: EBookFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar eboksdokument. Inkluderar följande filtyper Epub./ebookfiletype/epubMobi./ebookfiletype/mobiAzw3./ebookfiletype/azw3
type: docs
weight: 910
url: /sv/net/groupdocs.conversion.filetypes/ebookfiletype/
---
## EBookFileType class

Definierar e-boksdokument. Inkluderar följande filtyper: [`Epub`](./epub)[`Mobi`](./mobi)[`Azw3`](./azw3)

```csharp
public sealed class EBookFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EBookFileType](ebookfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypsbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filtillägget |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standard hash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Azw3](../../groupdocs.conversion.filetypes/ebookfiletype/azw3) | AZW3, även känd som Kindle Format 8 (KF8), är den modifierade versionen av det digitala filformatet AZW e-bok som utvecklats för Amazon Kindle-enheter. Formatet är en förbättring av äldre AZW-filer och används endast på Kindle Fire-enheter med bakåtkompatibilitet för förfaderfilformatet, dvs. MOBI och AZW. Läs mer om detta filformat[här](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Epub](../../groupdocs.conversion.filetypes/ebookfiletype/epub) | EPUB-tillägget är ett filformat för e-böcker som tillhandahåller ett standardformat för digitala publikationer för förlag och konsumenter. Formatet har varit så vanligt vid det här laget att det stöds av många e-läsare och program. Läs mer om detta filformat[här](https://wiki.fileformat.com/ebook/epub) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/ebookfiletype/mobi) | MOBI-filformatet är ett av de mest använda e-boksfilformaten. Formatet är en förbättring av det gamla OEB-formatet (Open Ebook Format) och användes som proprietärt format för Mobipocket Reader. Läs mer om detta filformat[här](https://wiki.fileformat.com/ebook/mobi) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->