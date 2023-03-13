---
title: FontFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar teckensnittsdokument Innehåller följande typer Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Läs mer om teckensnittsformathärhttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /sv/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Definierar teckensnittsdokument Innehåller följande typer: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Läs mer om teckensnittsformat[här](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [FontFileType](fontfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | En fil med filtillägget .cff är ett kompakt teckensnittsformat och kallas även för PostScript Type 1 eller CIDFont. CFF fungerar som en behållare för att lagra flera teckensnitt tillsammans i en enda enhet känd som en FontSet. Läs mer om detta filformat[här](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | En fil med filtillägget .eot är ett OpenType-teckensnitt som är inbäddat i ett dokument. Dessa används mest i webbfiler såsom en webbsida. Det skapades av Microsoft och stöds av Microsoft-produkter inklusive PowerPoint-presentation .pps-fil. Läs mer om detta filformat[här](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | En fil med filtillägget .otf hänvisar till OpenType-teckensnittsformat. OTF-teckensnittsformat är mer skalbart och utökar de befintliga funktionerna i TTF-format för digital typografi. OTF, som utvecklats av Microsoft och Adobe, kombinerar funktionerna i PostScript- och TrueType-teckensnittsformaten. Läs mer om detta filformat[här](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | En fil med filtillägget .ttf representerar teckensnittsfiler baserade på teckensnittstekniken TrueType-specifikationer. Det designades och lanserades från början av Apple Computer, Inc för Mac OS och antogs senare av Microsoft för Windows OS. Läs mer om detta filformat[här](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Typ 1-teckensnitt är en föråldrad Adobe-teknik som användes flitigt i skrivbordsbaserad publiceringsprogramvara och skrivare som kunde använda PostScript. Även om typ 1-teckensnitt inte stöds i många moderna plattformar, webbläsare och mobila operativsystem, men dessa stöds fortfarande i vissa av operativsystemen. Läs mer om detta filformat[här](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | En fil med filändelsen .woff är en webbteckensnittsfil baserad på Web Open Font Format (WOFF). Den har formatspecifika komprimerade behållare baserade på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnitt. Läs mer om detta filformat[här](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | En fil med filändelsen .woff är en webbteckensnittsfil baserad på Web Open Font Format (WOFF). Den har formatspecifika komprimerade behållare baserade på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnitt. Läs mer om detta filformat[här](https://docs.fileformat.com/font/woff/) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
