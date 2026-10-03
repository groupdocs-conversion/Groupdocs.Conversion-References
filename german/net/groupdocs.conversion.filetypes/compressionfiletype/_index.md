---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert Komprimierungsformate. Enthält die folgenden Dateitypen Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Weitere Informationen zu Komprimierungsformaten hierhttps//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /de/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definiert Komprimierungsformate. Enthält die folgenden Dateitypen: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Weitere Informationen zu Komprimierungsformaten [hier](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dateitypbeschreibung |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Die Dateierweiterung |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Die Dateifamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Das Dateiformat |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Definiert, ob das Format mehrere Dateien/Ordner in einem einzigen Archiv unterstützt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergleicht das aktuelle Objekt mit einem anderen. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementiert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als Standard-Hashfunktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String-Darstellung |

## Fields

| Name | Beschreibung |
| --- | --- |
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | Eine Datei mit der Erweiterung .aar ist ein Apple Archive, der Container, den Apple mit macOS für das Gruppieren von Dateien und Ordnern bereitstellt. Jeder Eintrag wird einzeln komprimiert, meist mit LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | Eine Datei mit der Erweiterung .alz ist ein ALZip-Archiv, ein Format von ESTsoft, das in Südkorea weit verbreitet ist. Einträge können einzeln mit einem Passwort verschlüsselt werden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 sind komprimierte Dateien, die mit der Open-Source-Komprimierungsmethode BZIP2 erzeugt werden, meist auf UNIX- oder Linux-Systemen. Sie werden zur Komprimierung einer einzelnen Datei verwendet und sind nicht für die Archivierung mehrerer Dateien gedacht. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Eine Datei mit der Erweiterung .cab gehört zu einer Windows-Cabinet-Datei, die zur Kategorie der Systemdateien zählt. Es ist eine Datei, die im Archivdateiformat in den Versionen von Microsoft Windows gespeichert wird, die komprimierte Datenalgorithmen wie LZX, Quantum und ZIP unterstützen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio ist ein allgemeines Dateiarchivierungswerkzeug und das zugehörige Dateiformat. Es ist hauptsächlich auf unixähnlichen Betriebssystemen installiert. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Eine GZ-Datei ist ein komprimiertes Archiv, das mit dem Standardgzip‑Algorithmus (GNU zip) erstellt wird. Sie kann mehrere komprimierte Dateien, Verzeichnisse und Dateistubs enthalten. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Eine Gzip-Datei ist ein komprimiertes Archiv, das mit dem Standardgzip‑Algorithmus (GNU zip) erstellt wird. Sie kann mehrere komprimierte Dateien, Verzeichnisse und Dateistubs enthalten. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | Eine Datei mit der Erweiterung .iso ist ein unkomprimiertes Archiv-Disk-Image, das den gesamten Inhalt eines optischen Datenträgers wie CD oder DVD darstellt. Basierend auf dem ISO‑9660‑Standard enthält das ISO‑Image-Dateiformat die Disc‑Daten sowie die darin gespeicherten Dateisysteminformationen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | Eine Datei mit den Erweiterungen .lzh und .lha bezieht sich in der Regel auf ein Archiv-Komprimierungsdateiformat. Dieses Dateiformat ist dasselbe wie andere Komprimierungsformate wie ZIP, RAR usw. Der Hauptzweck dieser Formate besteht darin, die Größe zu reduzieren, um sie leicht versenden zu können, und sie zusammen in komprimierter Form zu behalten. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Eine Datei mit der Erweiterung .lz ist eine komprimierte Archivdatei, die mit Lzip erstellt wird, einem freien Befehlszeilen‑Tool zur Kompression. Sie unterstützt das Zusammenfügen, um unterstützende Dateien zu komprimieren. LZ‑Dateien haben den Medientyp application/lzip und bieten höhere Kompressionsraten als BZ2. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | Eine Datei mit der Erweiterung .lz4 ist eine komprimierte Archivdatei, die mit Anwendungen/Dienstprogrammen erstellt wird, die LZ4‑Kompression unterstützen. Der LZ4‑Algorithmus konzentriert sich auf den Kompromiss zwischen Geschwindigkeit und Kompressionsrate. Komprimierte LZ4‑Archive können mit dem LZ4‑Kommandozeilen‑Utility erstellt und mit demselben wieder dekomprimiert werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Eine Datei mit der Erweiterung .lzma ist eine komprimierte Archivdatei, die mit dem LZMA‑Verfahren (Lempel‑Ziv‑Markov‑Ketten‑Algorithmus) erstellt wird. Diese werden hauptsächlich auf Unix‑Betriebssystemen gefunden/verwendet und sind anderen Kompressionsalgorithmen wie ZIP ähnlich, um die Dateigröße zu minimieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Dateien mit der Erweiterung .rar sind Archivdateien, die zum Speichern von Informationen in komprimierter oder normaler Form erstellt werden. RAR steht für Roshal ARchive‑Dateiformat. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z ist ein Archivformat zum Komprimieren von Dateien und Ordnern mit einem hohen Kompressionsgrad. Es basiert auf einer Open‑Source‑Architektur, die die Verwendung beliebiger Kompressions‑ und Verschlüsselungsalgorithmen ermöglicht. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Dateien mit der Erweiterung .tar sind Archive, die mit einem Unix‑basierten Dienstprogramm zum Sammeln von einer oder mehreren Dateien erstellt werden. Mehrere Dateien werden in einem unkomprimierten Format gespeichert, wobei das Hinzufügen von Dateien sowie Ordnern zum Archiv unterstützt wird. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Ein uuencodiertes Archiv ist eine Datei oder Sammlung von Dateien, die mit dem Unix‑to‑Unix‑Kodierungsschema (uuencode) kodiert wurden. Diese Kodierungsmethode wandelt Binärdaten in ein Textformat um, was das Senden von Dateien über Kanäle, die nur Text unterstützen, wie E‑Mail, erleichtert. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | Eine Datei mit der Erweiterung .wim ist ein Windows Imaging Format‑Archiv, ein dateibasiertes Festplatten‑Image, das Microsoft zur Bereitstellung von Windows verwendet. Ein einzelnes Archiv enthält ein oder mehrere Images und speichert jede Datei nur einmal, unabhängig davon, wie viele Images darauf verweisen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | Eine Datei mit der Erweiterung .xar ist ein eXtensible ARchive, ein Format, das um ein Inhaltsverzeichnis herum aufgebaut ist, das als komprimiertes XML gespeichert wird. Es wird verwendet, um macOS‑Installationspakete zu verteilen, und hält jeden Eintrag separat komprimiert. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ ist ein komprimiertes Dateiformat, das den LZMA2‑Kompressionsalgorithmus verwendet. Es wurde als Ersatz für die beliebten Formate gzip und bzip2 entwickelt und bietet gegenüber diesen älteren Standards mehrere Vorteile. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Eine Z-Datei ist eine Kategorie von Dateien, die zu den UNIX-komprimierten Datendateien gehören. Komprimierte Unix-Dateien sind die beliebteste und am weitesten verbreitete Erweiterungsart der Z-Datei. Erfahren Sie mehr über dieses Dateiformat [here](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Eine Datei mit der Erweiterung .zip ist ein Archiv, das eine oder mehrere Dateien oder Verzeichnisse enthalten kann. Auf das Archiv kann Kompression angewendet werden, um die Größe der ZIP-Datei zu reduzieren. Erfahren Sie mehr über dieses Dateiformat [here](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | Eine ZST-Datei ist eine komprimierte Datei, die mit dem Zstandard (zstd)-Kompressionsalgorithmus erzeugt wird. Es handelt sich um eine komprimierte Datei, die vom Algorithmus verlustfrei erstellt wird. Erfahren Sie mehr über dieses Dateiformat [here](https://docs.fileformat.com/compression/zst/). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
