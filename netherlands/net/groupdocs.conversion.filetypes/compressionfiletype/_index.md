---
title: CompressionFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert compressieformaten. Bevat de volgende bestandstypen Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Meer informatie over compressieindelingenhierhttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /nl/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definieert compressieformaten. Bevat de volgende bestandstypen: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Meer informatie over compressie-indelingen[hier](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Serialisatie-constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstype omschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt huidige object met andere. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Tekenreeksweergave |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 zijn gecomprimeerde bestanden die zijn gegenereerd met behulp van de BZIP2 open source-compressiemethode, meestal op UNIX- of Linux-systemen. Het wordt gebruikt voor het comprimeren van een enkel bestand en is niet bedoeld voor het archiveren van meerdere bestanden. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Een bestand met de extensie .cab behoort tot een Windows Cabinet-bestand dat tot de categorie systeembestanden behoort. Het is een bestand dat wordt opgeslagen in het archiefbestandsformaat in de versies van Microsoft Windows die gecomprimeerde gegevensalgoritmen ondersteunen, zoals LZX, Quantum en ZIP. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio is een algemeen hulpprogramma voor het archiveren van bestanden en het bijbehorende bestandsformaat. Het wordt voornamelijk geïnstalleerd op Unix-achtige computerbesturingssystemen. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Een GZ-bestand is een gecomprimeerd archief dat is gemaakt met behulp van het standaard gzip (GNU zip)-compressiealgoritme. Het kan meerdere gecomprimeerde bestanden, mappen en bestandsstubs bevatten. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Een Gzip-bestand is een gecomprimeerd archief dat is gemaakt met het standaard gzip-compressiealgoritme (GNU-zip). Het kan meerdere gecomprimeerde bestanden, mappen en bestandsstubs bevatten. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Een bestand met de extensie .lz is een gecomprimeerd archiefbestand gemaakt met Lzip, een gratis opdrachtregelprogramma voor compressie. Het ondersteunt aaneenschakeling om ondersteuningsbestanden te comprimeren. LZ-bestanden hebben het mediatype application/lzip en ondersteunen hogere compressieverhoudingen dan BZ2. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Een bestand met de extensie .lzma is een gecomprimeerd archiefbestand dat is gemaakt met behulp van de LZMA-compressiemethode (Lempel-Ziv-Markov chain Algorithm). Deze worden voornamelijk gevonden/gebruikt op het Unix-besturingssysteem en zijn vergelijkbaar met andere compressie-algoritmen zoals ZIP voor het minimaliseren van de bestandsgrootte. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Bestanden met de extensie .rar zijn archiefbestanden die zijn gemaakt om informatie in gecomprimeerde of normale vorm op te slaan. RAR, wat staat voor Roshal ARchive file format. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z is een archiveringsformaat voor het comprimeren van bestanden en mappen met een hoge compressieverhouding. Het is gebaseerd op Open Source-architectuur die het mogelijk maakt om alle compressie- en coderingsalgoritmen te gebruiken. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Bestanden met de extensie .tar zijn archieven die zijn gemaakt met een op Unix gebaseerd hulpprogramma voor het verzamelen van een of meer bestanden. Meerdere bestanden worden opgeslagen in een niet-gecomprimeerd formaat met ondersteuning voor het toevoegen van bestanden en mappen aan het archief. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ is een gecomprimeerd bestandsformaat dat gebruik maakt van het LZMA2-compressiealgoritme. Het is ontworpen als vervanging voor de populaire gzip- en bzip2-formaten en biedt een aantal voordelen ten opzichte van deze oudere standaarden. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | AZ-bestand is een categorie bestanden die behoren tot de UNIX-gecomprimeerde gegevensbestanden. Gecomprimeerde Unix-bestanden zijn het meest populaire en meest gebruikte extensietype van het Z-bestand. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Een bestand met de extensie .zip is een archief dat een of meer bestanden of mappen kan bevatten. Op het archief kan compressie worden toegepast op de opgenomen bestanden om de ZIP-bestandsgrootte te verkleinen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/compression/zip/) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
