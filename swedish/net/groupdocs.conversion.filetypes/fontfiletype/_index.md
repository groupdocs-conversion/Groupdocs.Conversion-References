---
title: "FontFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar teckensnittsdokument Inkluderar följande typer Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Läs mer om teckensnittformat härhttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /sv/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Definierar teckensnittsdokument Inkluderar följande typer: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Läs mer om teckensnittformat [här](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FontFileType](fontfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | En fil med .cff‑tillägg är ett Compact Font Format och är även känt som PostScript Type 1 eller CIDFont. CFF fungerar som en behållare för att lagra flera teckensnitt tillsammans i en enhet som kallas FontSet. Läs mer om detta filformat [här](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | En fil med .eot‑tillägg är ett OpenType‑teckensnitt som är inbäddat i ett dokument. Dessa används främst i webbfil­er såsom en webbsida. Den skapades av Microsoft och stöds av Microsoft‑produkter inklusive PowerPoint‑presentationen .pps‑fil. Läs mer om detta filformat [här](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | En fil med .otf‑tillägg avser OpenType‑teckensnittformat. OTF‑teckensnittformatet är mer skalbart och utökar de befintliga funktionerna i TTF‑formaten för digital typografi. Utvecklat av Microsoft och Adobe kombinerar OTF funktionerna i PostScript‑ och TrueType‑teckensnittformat. Läs mer om detta filformat [här](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | En fil med .ttf‑tillägg representerar teckensnittsfiler baserade på TrueType‑specifikationernas teckensnittsteknologi. Den designades och lanserades ursprungligen av Apple Computer, Inc för Mac OS och antogs senare av Microsoft för Windows OS. Läs mer om detta filformat [här](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1‑teckensnitt är en föråldrad Adobe‑teknik som var allmänt använd i skrivbordsbaserad publiceringsprogramvara och skrivare som kunde använda PostScript. Även om Type 1‑teckensnitt inte stöds i många moderna plattformar, webbläsare och mobila operativsystem, stöds de fortfarande i vissa operativsystem. Läs mer om detta filformat [här](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | En fil med .woff‑tillägg är en webbteckensnittfil baserad på Web Open Font Format (WOFF). Den har ett format‑specifikt komprimerat paket baserat på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnittstyper. Läs mer om detta filformat [här](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | En fil med .woff‑tillägg är en webbteckensnittfil baserad på Web Open Font Format (WOFF). Den har ett format‑specifikt komprimerat paket baserat på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnittstyper. Läs mer om detta filformat [här](https://docs.fileformat.com/font/woff/). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
