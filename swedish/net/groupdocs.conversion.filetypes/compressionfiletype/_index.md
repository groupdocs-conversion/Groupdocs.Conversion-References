---
title: CompressionFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar komprimeringsformat. Inkluderar följande filtyper Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Läs mer om komprimeringsformathärhttps//docs.fileformat.com/compression/ .
type: docs
weight: 810
url: /sv/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definierar komprimeringsformat. Inkluderar följande filtyper: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Läs mer om komprimeringsformat[här](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Serialiseringskonstruktor |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standard hash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 är komprimerade filer som genereras med BZIP2-komprimeringsmetoden med öppen källkod, mestadels på UNIX- eller Linux-system. Den används för komprimering av en enda fil och är inte avsedd för arkivering av flera filer. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | En fil med filtillägget .cab tillhör en Windows-kabinettfil som tillhör kategorin systemfiler. Det är en fil som sparas i arkivfilformatet i versionerna av Microsoft Windows som stöder komprimerade dataalgoritmer, såsom LZX, Quantum och ZIP. Läs mer om detta filformat[här](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio är ett allmänt filarkiveringsverktyg och dess tillhörande filformat. Det är främst installerat på Unix-liknande datoroperativsystem. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | En GZ-fil är ett komprimerat arkiv som skapas med hjälp av standardkompressionsalgoritmen gzip (GNU zip). Den kan innehålla flera komprimerade filer, kataloger och filstubbar. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | En Gzip-fil är ett komprimerat arkiv som skapas med hjälp av standardkompressionsalgoritmen för gzip (GNU zip). Den kan innehålla flera komprimerade filer, kataloger och filstubbar. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | En fil med filtillägget .lz är en komprimerad arkivfil skapad med Lzip, som är ett gratis kommandoradsverktyg för komprimering. Den stöder sammanlänkning för att komprimera stödfiler. LZ-filer har mediatyp application/lzip och stöder högre komprimeringskvoter än BZ2. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | En fil med tillägget .lzma är en komprimerad arkivfil skapad med komprimeringsmetoden LZMA (Lempel-Ziv-Markov chain Algorithm). Dessa finns/används huvudsakligen på Unix operativsystem och liknar andra komprimeringsalgoritmer som ZIP för att minimera filstorleken. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Filer med tillägget .rar är arkivfiler som skapas för att lagra information i komprimerad eller normal form. RAR, som står för Roshal ARchive file format. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z är ett arkiveringsformat för att komprimera filer och mappar med ett högt komprimeringsförhållande. Den är baserad på Open Source-arkitektur som gör det möjligt att använda alla komprimerings- och krypteringsalgoritmer. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Filer med tillägget .tar är arkiv skapade med Unix-baserat verktyg för att samla in en eller flera filer. Flera filer lagras i ett okomprimerat format med stöd för att lägga till såväl filer som mappar till arkivet. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ är ett komprimerat filformat som använder LZMA2-komprimeringsalgoritmen. Det designades som en ersättning för de populära formaten gzip och bzip2 och erbjuder ett antal fördelar jämfört med dessa äldre standarder. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | AZ-fil är en kategori av filer som tillhör UNIX-komprimerade datafiler. Komprimerade Unix-filer är den mest populära och mest använda tilläggstypen för Z-filen. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | En fil med filtillägget .zip är ett arkiv som kan innehålla en eller flera filer eller kataloger. Arkivet kan ha komprimering tillämpad på de inkluderade filerna för att minska ZIP-filstorleken. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/zip/) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
