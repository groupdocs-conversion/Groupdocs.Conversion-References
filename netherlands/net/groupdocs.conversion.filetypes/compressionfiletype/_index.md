---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert compressieformaten. Bevat de volgende bestandstypen Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Meer informatie over compressieformaten hierhttps//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /nl/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definieert compressieformaten. Bevat de volgende bestandstypen: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Meer informatie over compressieformaten [hier](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstypebeschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Definieert of het formaat meerdere bestanden/mappen in één archief ondersteunt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementeert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Stringrepresentatie |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | Een bestand met .aar-extensie is een Apple Archive, de container die Apple levert met macOS voor het groeperen van bestanden en mappen. Elke entry wordt afzonderlijk gecomprimeerd, meestal met LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | Een bestand met .alz-extensie is een ALZip-archief, een formaat van ESTsoft dat veel wordt gebruikt in Zuid‑Korea. Items kunnen individueel versleuteld worden met een wachtwoord. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 zijn gecomprimeerde bestanden die zijn gegenereerd met de BZIP2 open‑source compressiemethode, meestal op UNIX‑ of Linux‑systemen. Het wordt gebruikt voor compressie van één enkel bestand en is niet bedoeld voor het archiveren van meerdere bestanden. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Een bestand met een .cab-extensie behoort tot een Windows‑cabinetbestand dat tot de categorie systeembestanden behoort. Het is een bestand dat wordt opgeslagen in het archiefformaat in de versies van Microsoft Windows die gecomprimeerde gegevensalgoritmen ondersteunen, zoals LZX, Quantum en ZIP. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio is een algemene bestandsarchiveringsutility en het bijbehorende bestandsformaat. Het wordt voornamelijk geïnstalleerd op Unix‑achtige besturingssystemen. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Een GZ‑bestand is een gecomprimeerd archief dat is gemaakt met het standaard gzip (GNU zip) compressie‑algoritme. Het kan meerdere gecomprimeerde bestanden, mappen en bestandsstubs bevatten. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Een Gzip‑bestand is een gecomprimeerd archief dat is gemaakt met het standaard gzip (GNU zip) compressie‑algoritme. Het kan meerdere gecomprimeerde bestanden, mappen en bestandsstubs bevatten. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | Een bestand met de .iso-extensie is een ongecomprimeerd archief‑diskimagebestand dat de inhoud van alle gegevens op een optische schijf, zoals een cd of dvd, weergeeft. Op basis van de ISO‑9660‑standaard bevat het ISO‑imagebestandsformaat de schijff gegevens samen met de bestandsysteeminformatie die erin is opgeslagen. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | Een bestand met de .lzh- en .lha-extensie verwijst meestal naar een archiefcompressie‑bestandsformaat. Dit bestandsformaat is hetzelfde als andere bestandscompressieformaten zoals ZIP, RAR, enz. Het belangrijkste doel van deze bestandsformaten is om de grootte van het bestand te verkleinen voor gemakkelijke verzending en om ze samen in gecomprimeerde vorm te bewaren. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Een bestand met de .lz-extensie is een gecomprimeerd archiefbestand gemaakt met Lzip, een gratis commandoregeltool voor compressie. Het ondersteunt concatenatie om ondersteunende bestanden te comprimeren. LZ‑bestanden hebben mediatype application/lzip en bieden een hogere compressieverhouding dan BZ2. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | Een bestand met de .lz4-extensie is een gecomprimeerd archiefbestand gemaakt met applicaties/hulpmiddelen die LZ4‑compressie ondersteunen. Het LZ4‑algoritme richt zich op een afweging tussen snelheid en compressieverhouding. Gecomprimeerde LZ4‑archieven kunnen worden gemaakt met de LZ4‑commandoregeltool en kunnen met dezelfde tool worden gedecomprimeerd. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Een bestand met de .lzma-extensie is een gecomprimeerd archiefbestand gemaakt met de LZMA (Lempel‑Ziv‑Markov‑ketenalgoritme) compressiemethode. Deze worden voornamelijk aangetroffen/gebruikt op Unix‑besturingssystemen en lijken op andere compressie‑algoritmen zoals ZIP voor het verkleinen van de bestandsgrootte. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Bestanden met de .rar-extensie zijn archiefbestanden die worden aangemaakt om informatie op te slaan in gecomprimeerde of normale vorm. RAR, wat staat voor Roshal ARchive‑bestandsformaat. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z is een archiveringsformaat voor het comprimeren van bestanden en mappen met een hoge compressieverhouding. Het is gebaseerd op een open‑source‑architectuur, waardoor het mogelijk is om allerlei compressie‑ en encryptie‑algoritmen te gebruiken. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Bestanden met de .tar-extensie zijn archieven die zijn gemaakt met een Unix‑gebaseerd hulpprogramma voor het verzamelen van één of meer bestanden. Meerdere bestanden worden opgeslagen in een ongecomprimeerd formaat met de mogelijkheid om zowel bestanden als mappen aan het archief toe te voegen. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Een uuencoded‑archief is een bestand of een verzameling bestanden die zijn gecodeerd met het Unix‑to‑Unix‑coderingsschema (uuencode). Deze coderingsmethode zet binaire gegevens om in een tekstformaat, waardoor het eenvoudiger wordt om bestanden te verzenden via kanalen die alleen tekst ondersteunen, zoals e‑mail. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | Een bestand met de .wim-extensie is een Windows Imaging Format‑archief, een bestand‑gebaseerde schijf‑image die Microsoft gebruikt om Windows te distribueren. Eén enkel archief bevat één of meer images en slaat elk bestand één keer op, ongeacht hoeveel images ernaar verwijzen. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | Een bestand met de .xar-extensie is een eXtensible ARchive, een formaat dat is opgebouwd rond een inhoudsopgave die wordt opgeslagen als gecomprimeerde XML. Het wordt gebruikt om macOS‑installatiepakketten te distribueren en houdt elke entry afzonderlijk gecomprimeerd. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ is een gecomprimeerd bestandsformaat dat het LZMA2‑compressie‑algoritme gebruikt. Het is ontworpen als vervanging voor de populaire gzip‑ en bzip2‑formaten en biedt een aantal voordelen ten opzichte van deze oudere standaarden. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Een Z‑bestand is een categorie bestanden die behoren tot de UNIX‑gecomprimeerde gegevensbestanden. Gecomprimeerde Unix‑bestanden zijn het populairste en meest gebruikte extensietype van het Z‑bestand. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Een bestand met de .zip‑extensie is een archief dat één of meer bestanden of mappen kan bevatten. Op het archief kan compressie worden toegepast op de opgenomen bestanden om de grootte van het ZIP‑bestand te verkleinen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | Een ZST‑bestand is een gecomprimeerd bestand dat wordt gegenereerd met het Zstandard‑ (zstd) compressie‑algoritme. Het is een gecomprimeerd bestand dat door het algoritme wordt gemaakt met verliesloze compressie. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/compression/zst/). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
