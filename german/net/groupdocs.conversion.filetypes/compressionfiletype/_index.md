---
title: CompressionFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert Komprimierungsformate. Enthält die folgenden Dateitypen Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Erfahren Sie mehr über KomprimierungsformateHierhttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /de/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definiert Komprimierungsformate. Enthält die folgenden Dateitypen: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Erfahren Sie mehr über Komprimierungsformate[Hier](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Serialisierungskonstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Beschreibung des Dateityps |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Die Dateiendung |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Die Dateifamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Das Dateiformat |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergleicht aktuelles Objekt mit anderem. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als Standard-Hash-Funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Zeichenfolgendarstellung |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 sind komprimierte Dateien, die mit der BZIP2-Open-Source-Komprimierungsmethode generiert werden, hauptsächlich auf UNIX- oder Linux-Systemen. Es wird für die Komprimierung einer einzelnen Datei verwendet und ist nicht für die Archivierung mehrerer Dateien gedacht. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Eine Datei mit der Erweiterung .cab gehört zu einer Windows Cabinet-Datei, die zur Kategorie der Systemdateien gehört. Es handelt sich um eine Datei, die im Archivdateiformat in den Versionen von Microsoft Windows gespeichert wird, die komprimierte Datenalgorithmen unterstützen, wie z. B. LZX, Quantum und ZIP. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio ist ein allgemeines Dateiarchivierungsprogramm und das zugehörige Dateiformat. Es wird hauptsächlich auf Unix-ähnlichen Computerbetriebssystemen installiert. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Eine GZ-Datei ist ein komprimiertes Archiv, das mit dem Standardkomprimierungsalgorithmus gzip (GNU zip) erstellt wird. Es kann mehrere komprimierte Dateien, Verzeichnisse und Datei-Stubs enthalten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Eine Gzip-Datei ist ein komprimiertes Archiv, das mit dem Standardkomprimierungsalgorithmus gzip (GNU zip) erstellt wird. Es kann mehrere komprimierte Dateien, Verzeichnisse und Datei-Stubs enthalten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Eine Datei mit der Erweiterung .lz ist eine komprimierte Archivdatei, die mit Lzip erstellt wurde, einem kostenlosen Befehlszeilentool für die Komprimierung. Es unterstützt die Verkettung, um Support-Dateien zu komprimieren. LZ-Dateien haben den Medientyp application/lzip und unterstützen höhere Komprimierungsraten als BZ2. . Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Eine Datei mit der Erweiterung .lzma ist eine komprimierte Archivdatei, die mit der Komprimierungsmethode LZMA (Lempel-Ziv-Markov-Kettenalgorithmus) erstellt wurde. Diese werden hauptsächlich auf Unix-Betriebssystemen gefunden/verwendet und ähneln anderen Komprimierungsalgorithmen wie ZIP zum Minimieren der Dateigröße. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Dateien mit der Erweiterung .rar sind Archivdateien, die zum Speichern von Informationen in komprimierter oder normaler Form erstellt werden. RAR steht für Roshal ARchive file format. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z ist ein Archivierungsformat zum Komprimieren von Dateien und Ordnern mit hoher Komprimierungsrate. Es basiert auf einer Open-Source-Architektur, die es ermöglicht, beliebige Komprimierungs- und Verschlüsselungsalgorithmen zu verwenden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Dateien mit der Erweiterung .tar sind Archive, die mit einem Unix-basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. Mehrere Dateien werden in einem unkomprimierten Format gespeichert, wobei das Hinzufügen von Dateien und Ordnern zum Archiv unterstützt wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ ist ein komprimiertes Dateiformat, das den LZMA2-Komprimierungsalgorithmus verwendet. Es wurde als Ersatz für die gängigen Formate gzip und bzip2 entwickelt und bietet gegenüber diesen älteren Standards eine Reihe von Vorteilen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | AZ-Datei ist eine Kategorie von Dateien, die zu den komprimierten UNIX-Datendateien gehören. Komprimierte Unix-Dateien sind der beliebteste und am weitesten verbreitete Erweiterungstyp der Z-Datei. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Eine Datei mit der Erweiterung .zip ist ein Archiv, das eine oder mehrere Dateien oder Verzeichnisse enthalten kann. Auf die enthaltenen Dateien des Archivs kann eine Komprimierung angewendet werden, um die Größe der ZIP-Datei zu reduzieren. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/compression/zip/) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
