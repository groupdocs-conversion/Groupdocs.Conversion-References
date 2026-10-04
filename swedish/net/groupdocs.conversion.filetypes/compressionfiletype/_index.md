---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar komprimeringsformat. Inkluderar följande filtyper Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Läs mer om komprimeringsformat härhttps//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /sv/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definierar komprimeringsformat. Inkluderar följande filtyper: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Läs mer om komprimeringsformat [här](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Definierar om formatet stödjer flera filer/mappar i ett enda arkiv. |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | En fil med .aar‑ändelse är ett Apple‑arkiv, den behållare som Apple levererar med macOS för att gruppera filer och mappar. Varje post komprimeras separat, oftast med LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | En fil med .alz‑extension är ett ALZip‑arkiv, ett format från ESTsoft som är allmänt använt i Sydkorea. Poster kan krypteras individuellt med ett lösenord. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 är komprimerade filer som genereras med BZIP2‑metoden för öppen källkod, främst på UNIX‑ eller Linux‑system. Den används för komprimering av en enskild fil och är inte avsedd för arkivering av flera filer. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | En fil med .cab‑extension är en Windows‑cabinetfil som tillhör kategorin systemfiler. Det är en fil som sparas i arkivfilformatet i de versioner av Microsoft Windows som stödjer komprimerade data‑algoritmer, såsom LZX, Quantum och ZIP. Läs mer om detta filformat [här](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio är ett allmänt filarkiveringsverktyg och dess tillhörande filformat. Det installeras främst på Unix‑liknande operativsystem. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | En GZ‑fil är ett komprimerat arkiv som skapas med den standardiserade gzip‑algoritmen (GNU zip). Den kan innehålla flera komprimerade filer, kataloger och filstubbar. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | En Gzip‑fil är ett komprimerat arkiv som skapas med den standardiserade gzip‑algoritmen (GNU zip). Den kan innehålla flera komprimerade filer, kataloger och filstubbar. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | En fil med .iso‑extension är en okomprimerad arkivdiskavbildningsfil som representerar innehållet på hela data på en optisk skiva såsom CD eller DVD. Baserat på ISO‑9660‑standarden innehåller ISO‑avbildningsfilformatet skivdata tillsammans med filsystemsinformationen som lagras i den. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | En fil med .lzh‑ och .lha‑extension hänvisar vanligtvis till ett arkivkomprimeringsfilformat. Detta filformat är detsamma som andra filkomprimeringsformat som ZIP, RAR osv. Huvudsyftet med dessa filformat är att minska storleken för enkel överföring samt att hålla dem ihop i komprimerad form. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | En fil med .lz‑extension är en komprimerad arkivfil skapad med Lzip, ett gratis kommandoradsverktyg för komprimering. Den stödjer sammanslagning för att komprimera stödjande filer. LZ‑filer har mediatypen application/lzip och ger högre komprimeringsförhållanden än BZ2. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | En fil med .lz4‑extension är en komprimerad arkivfil skapad med program/verktyg som stödjer LZ4‑komprimering. LZ4‑algoritmen fokuserar på en avvägning mellan hastighet och komprimeringsgrad. Komprimerade LZ4‑arkiv kan skapas med LZ4‑kommandoradsverktyget och kan dekomprimeras med samma. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | En fil med .lzma‑extension är en komprimerad arkivfil som skapats med LZMA‑metoden (Lempel‑Ziv‑Markov‑kedje‑algoritmen). Dessa finns främst på Unix‑operativsystemet och liknar andra komprimeringsalgoritmer såsom ZIP för att minska filstorleken. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Filer med .rar‑extension är arkivfiler som skapas för att lagra information i komprimerad eller normal form. RAR, som står för Roshal ARchive‑filformat. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z är ett arkiveringsformat för att komprimera filer och mappar med hög komprimeringsgrad. Det är baserat på öppen källkod‑arkitektur som möjliggör användning av alla komprimerings‑ och krypteringsalgoritmer. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Filer med .tar‑extension är arkiv som skapats med ett Unix‑baserat verktyg för att samla en eller flera filer. Flera filer lagras i ett okomprimerat format med stöd för att lägga till både filer och mappar i arkivet. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Ett uu‑kodad arkiv är en fil eller samling av filer som har kodats med Unix‑to‑Unix‑kodningsschemat (uuencode). Denna kodningsmetod konverterar binär data till ett textformat, vilket gör det enklare att skicka filer via kanaler som endast stöder text, såsom e‑post. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | En fil med .wim‑extension är ett Windows Imaging Format‑arkiv, en filbaserad diskavbildning som Microsoft använder för att distribuera Windows. Ett enda arkiv innehåller en eller flera avbilder och lagrar varje fil en gång, oavsett hur många avbilder som refererar till den. Läs mer om detta filformat [här](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | En fil med .xar‑extension är ett eXtensible ARchive, ett format byggt kring ett innehållsförteckning lagrad som komprimerad XML. Det används för att distribuera macOS‑installationspaket och håller varje post komprimerad separat. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ är ett komprimerat filformat som använder LZMA2‑komprimeringsalgoritmen. Det designades som en ersättning för de populära gzip‑ och bzip2‑formaten och erbjuder ett antal fördelar jämfört med dessa äldre standarder. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | En Z‑fil är en kategori av filer som tillhör UNIX‑komprimerade datafiler. Komprimerade Unix‑filer är den mest populära och mest använda filändelsen av Z‑filen. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | En fil med .zip‑extension är ett arkiv som kan innehålla en eller flera filer eller kataloger. Arkivet kan ha komprimering tillämpad på de inkluderade filerna för att minska ZIP‑filens storlek. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | En ZST-fil är en komprimerad fil som genereras med Zstandard (zstd) komprimeringsalgoritmen. Det är en komprimerad fil som skapas med förlustfri kompression av algoritmen. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/zst/). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
