---
title: "ImageFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar bilddokument. Inkluderar följande filtyper Ai./imagefiletype/ai Avif./imagefiletype/avif Bmp./imagefiletype/bmp Cdr./imagefiletype/cdr Cmx./imagefiletype/cmx Dcm./imagefiletype/dcm Dib./imagefiletype/dib DjVu./imagefiletype/djvu Dng./imagefiletype/dng Emf./imagefiletype/emf Emz./imagefiletype/emz Gif./imagefiletype/gif Heic./imagefiletype/heicIco./imagefiletype/ico J2c./imagefiletype/j2c J2k./imagefiletype/j2k Jls./imagefiletype/jls Jp2./imagefiletype/jp2 Jpc./imagefiletype/jpc Jfif./imagefiletype/jfif. Jpeg./imagefiletype/jpeg Jpf./imagefiletype/jpf Jpg./imagefiletype/jpg Jpm./imagefiletype/jpm Jpx./imagefiletype/jpx Odg./imagefiletype/odg Png./imagefiletype/png Psd./imagefiletype/psd Tif./imagefiletype/tif Tiff./imagefiletype/tiff Webp./imagefiletype/webp Wmf./imagefiletype/wmf. Wmz./imagefiletype/wmz. Läs mer om bildformat härhttps//wiki.fileformat.com/image."
type: docs
weight: 1170
url: /sv/net/groupdocs.conversion.filetypes/imagefiletype/
---
## ImageFileType class

Definierar bilddokument. Inkluderar följande filtyper: [`Ai`](./ai), [`Avif`](./avif), [`Bmp`](./bmp), [`Cdr`](./cdr), [`Cmx`](./cmx), [`Dcm`](./dcm), [`Dib`](./dib), [`DjVu`](./djvu), [`Dng`](./dng), [`Emf`](./emf), [`Emz`](./emz), [`Gif`](./gif), [`Heic`](./heic)[`Ico`](./ico), [`J2c`](./j2c), [`J2k`](./j2k), [`Jls`](./jls), [`Jp2`](./jp2), [`Jpc`](./jpc), [`Jfif`](./jfif). [`Jpeg`](./jpeg), [`Jpf`](./jpf), [`Jpg`](./jpg), [`Jpm`](./jpm), [`Jpx`](./jpx), [`Odg`](./odg), [`Png`](./png), [`Psd`](./psd), [`Tif`](./tif), [`Tiff`](./tiff), [`Webp`](./webp), [`Wmf`](./wmf). [`Wmz`](./wmz). Läs mer om bildformat [här](https://wiki.fileformat.com/image).

```csharp
public sealed class ImageFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageFileType](imagefiletype)() | Serialiseringskonstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |
| [IsRaster](../../groupdocs.conversion.filetypes/imagefiletype/israster) { get; } | Definierar om bilden är raster |

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
| static readonly [Ai](../../groupdocs.conversion.filetypes/imagefiletype/ai) | AI, Adobe Illustrator Artwork, representerar enkelsidiga vektorbaserade teckningar i antingen EPS- eller PDF-format. |
| static readonly [Avif](../../groupdocs.conversion.filetypes/imagefiletype/avif) | AVIF (AV1 Image File Format) är ett bildfilformat som lagrar bilder komprimerade med AV1 i HEIF-filformat. AVIF-filer lagras med filändelsen .avif. Version 1 av AVIF slutfördes i februari 2019. Det har funktioner som High Dynamic Range (HDR), stöd för 8, 10 och 12 bitars färgdjup, stöd för alla färgrymder (ISO/IEC CICP och ICC-profiler, brett färgomfång) osv. Läs mer om detta filformat [här](https://docs.fileformat.com/image/avif/). |
| static readonly [Bmp](../../groupdocs.conversion.filetypes/imagefiletype/bmp) | BMP representerar Bitmap Image-filer som används för att lagra bitmapdigitala bilder. Dessa bilder är oberoende av grafikadapter och kallas också device independent bitmap (DIB)-filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/bmp). |
| static readonly [Cdr](../../groupdocs.conversion.filetypes/imagefiletype/cdr) | En CDR-fil är en vektorritningsbildfil som ursprungligen skapas med CorelDRAW för att lagra digitala bilder som kodas och komprimeras. En sådan ritningsfil innehåller text, linjer, former, bilder, färger och effekter för vektorrepresentation av bildinnehåll. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/cdr). |
| static readonly [Cmx](../../groupdocs.conversion.filetypes/imagefiletype/cmx) | Filer med CMX‑tillägg är Corel Exchange‑bildfilformat som används som presentation i CorelSuite‑applikationer. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/cmx). |
| static readonly [Dcm](../../groupdocs.conversion.filetypes/imagefiletype/dcm) | Filer med .DCM‑tillägg representerar digitala bilder som lagrar medicinsk information om patienter, såsom MR‑bilder, CT‑skanningar och ultraljudsbilder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/dcm). |
| static readonly [Dib](../../groupdocs.conversion.filetypes/imagefiletype/dib) | DIB‑fil (Device Independent Bitmap) är en rasterbildfil som är liknande i struktur till standard‑Bitmap‑filer (BMP) men har ett annat huvud. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/dib). |
| static readonly [Dicom](../../groupdocs.conversion.filetypes/imagefiletype/dicom) | Filer med .DICOM‑tillägg representerar digitala bilder som lagrar medicinsk information om patienter, såsom MR‑bilder, CT‑skanningar och ultraljudsbilder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/dicom). |
| static readonly [DjVu](../../groupdocs.conversion.filetypes/imagefiletype/djvu) | DjVu är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/djvu). |
| static readonly [Dng](../../groupdocs.conversion.filetypes/imagefiletype/dng) | DNG är ett digitalt kamerabildformat som används för lagring av råfiler. Det utvecklades av Adobe i september 2004. Det skapades i huvudsak för digital fotografering. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/dng). |
| static readonly [Emf](../../groupdocs.conversion.filetypes/imagefiletype/emf) | Enhanced metafile format (EMF) lagrar grafiska bilder enhetsoberoende. EMF‑metafiler består av variabelängdliga poster i kronologisk ordning som kan återge den lagrade bilden efter parsning på vilken utskriftsenhet som helst. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/emf). |
| static readonly [Emz](../../groupdocs.conversion.filetypes/imagefiletype/emz) | En EMZ‑fil är i själva verket en komprimerad version av en Microsoft EMF‑fil. Detta möjliggör enklare distribution av filen online. När en EMF‑fil komprimeras med .GZIP‑komprimeringsalgoritmen får den .emz‑filändelsen. |
| static readonly [Fodg](../../groupdocs.conversion.filetypes/imagefiletype/fodg) | FODG är en okomprimerad XML‑formatfil som används för att lagra OpenDocument‑textdata. FODG‑tillägget är associerat med de öppna kontorssviterna LibreOffice och OpenOffice.org. |
| static readonly [Gif](../../groupdocs.conversion.filetypes/imagefiletype/gif) | En GIF eller Graphical Interchange Format är en typ av starkt komprimerad bild. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel och upp till 256 färger är tillåtna i bilden. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/gif). |
| static readonly [Heic](../../groupdocs.conversion.filetypes/imagefiletype/heic) | En HEIC-fil är ett High-Efficiency Container Image-filformat som kan lagra flera bilder som en samling i en enda fil. Formatet antogs av Apple som en variant av HEIF med lanseringen av iOS 11. Läs mer om detta filformat [här](https://docs.fileformat.com/image/heic/). |
| static readonly [Ico](../../groupdocs.conversion.filetypes/imagefiletype/ico) | Filer med ICO‑extension är bildfiltyper som används som ikon för att representera ett program på Microsoft Windows. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/ico). |
| static readonly [J2c](../../groupdocs.conversion.filetypes/imagefiletype/j2c) | J2c-dokumentformat |
| static readonly [J2k](../../groupdocs.conversion.filetypes/imagefiletype/j2k) | En J2K-fil är en bild som komprimeras med wavelet‑komprimering istället för DCT‑komprimering. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/j2k). |
| static readonly [Jfif](../../groupdocs.conversion.filetypes/imagefiletype/jfif) | JFIF (JPEG File Interchange Format (JFIF)) är en bildfilformat som använder .jfif‑extensionen. JFIF bygger vidare på JIF (JPEG Interchange Format) genom att minska komplexiteten och lösa dess begränsningar. Läs mer om detta filformat [här](https://docs.fileformat.com/image/jfif/). |
| static readonly [Jls](../../groupdocs.conversion.filetypes/imagefiletype/jls) | Jls-dokumentformat |
| static readonly [Jp2](../../groupdocs.conversion.filetypes/imagefiletype/jp2) | JPEG 2000 (JP2) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jp2). |
| static readonly [Jpc](../../groupdocs.conversion.filetypes/imagefiletype/jpc) | Jpc-dokumentformat |
| static readonly [Jpeg](../../groupdocs.conversion.filetypes/imagefiletype/jpeg) | En JPEG är en typ av bildformat som sparas med förlustkomprimering. Den resulterande bilden, som ett resultat av komprimeringen, är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpf](../../groupdocs.conversion.filetypes/imagefiletype/jpf) | Jpf-dokumentformat |
| static readonly [Jpg](../../groupdocs.conversion.filetypes/imagefiletype/jpg) | En JPG är en typ av bildformat som sparas med förlustkomprimering. Den resulterande bilden, som ett resultat av komprimeringen, är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpm](../../groupdocs.conversion.filetypes/imagefiletype/jpm) | Jpm-dokumentformat |
| static readonly [Jpx](../../groupdocs.conversion.filetypes/imagefiletype/jpx) | Jpx-dokumentformat |
| static readonly [Odg](../../groupdocs.conversion.filetypes/imagefiletype/odg) | ODG‑filformatet används av Apache OpenOffice Draw‑applikationen för att lagra ritningselement som en vektorbild. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/odg). |
| static readonly [Otg](../../groupdocs.conversion.filetypes/imagefiletype/otg) | En OTG-fil är en ritningsmall som skapas med OpenDocument‑standarden som följer OASIS Office Applications 1.0‑specifikationen. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/otg). |
| static readonly [Png](../../groupdocs.conversion.filetypes/imagefiletype/png) | PNG, Portable Network Graphics, avser en typ av rasterbildfilformat som använder förlustfri komprimering. Detta filformat skapades som ett ersättningsalternativ till Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/png). |
| static readonly [Psb](../../groupdocs.conversion.filetypes/imagefiletype/psb) | Adobe Photoshop sparar filer i två format. Filer med 30 000 × 30 000 pixlar sparas med PSD‑extensionen och filer som är större än PSD upp till 300 000 × 300 000 pixlar sparas med PSB‑extensionen som kallas “Photoshop Big”. Läs mer om detta filformat [här](https://docs.fileformat.com/image/psb). |
| static readonly [Psd](../../groupdocs.conversion.filetypes/imagefiletype/psd) | PSD, Photoshop Document, är Adobe Photshops inhemska filformat som används för grafisk design och utveckling. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/psd). |
| static readonly [Tga](../../groupdocs.conversion.filetypes/imagefiletype/tga) | En fil med .tga‑extension är ett rastergrafikformat och skapades av Truevision Inc. Läs mer om detta filformat [här](https://docs.fileformat.com/image/tga). |
| static readonly [Tif](../../groupdocs.conversion.filetypes/imagefiletype/tif) | TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Den kan beskriva tvånivå-, gråskala-, palettfärg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff). |
| static readonly [Tiff](../../groupdocs.conversion.filetypes/imagefiletype/tiff) | TIFF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Den kan beskriva tvånivå-, gråskala-, palettfärg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff). |
| static readonly [Webp](../../groupdocs.conversion.filetypes/imagefiletype/webp) | WebP, introducerat av Google, är ett modernt rasterwebbbildformat som bygger på förlustfri och förlustkomprimering. Det ger samma bildkvalitet samtidigt som det avsevärt minskar bildstorleken. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/webp). |
| static readonly [Wmf](../../groupdocs.conversion.filetypes/imagefiletype/wmf) | Filer med WMF‑extension representerar Microsoft Windows Metafile (WMF) för lagring av både vektor‑ och bitmap‑format bilddata. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/wmf). |
| static readonly [Wmz](../../groupdocs.conversion.filetypes/imagefiletype/wmz) | En WMZ‑fil är i själva verket en komprimerad version av en Microsoft WMF‑fil. Detta möjliggör enklare distribution av filen online. När en EWMFMF‑fil komprimeras med .GZIP‑komprimeringsalgoritmen får den .wmz‑filändelsen. |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
