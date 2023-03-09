---
title: FontFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert Schriftdokumente Enthält die folgenden Typen Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Erfahren Sie mehr über SchriftformateHierhttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /de/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Definiert Schriftdokumente Enthält die folgenden Typen: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Erfahren Sie mehr über Schriftformate[Hier](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FontFileType](fontfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Eine Datei mit der Erweiterung .cff ist ein Compact Font Format und wird auch als PostScript Type 1 oder CIDFont bezeichnet. CFF fungiert als Container zum gemeinsamen Speichern mehrerer Schriftarten in einer einzigen Einheit, die als FontSet bezeichnet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Eine Datei mit der Erweiterung .eot ist eine OpenType-Schriftart, die in ein Dokument eingebettet ist. Diese werden hauptsächlich in Webdateien wie einer Webseite verwendet. Es wurde von Microsoft erstellt und wird von Microsoft-Produkten unterstützt, einschließlich PowerPoint-Präsentationsdatei .pps. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Eine Datei mit der Erweiterung .otf bezieht sich auf das OpenType-Schriftformat. Das OTF-Schriftformat ist skalierbarer und erweitert die vorhandenen Funktionen von TTF-Formaten für digitale Typografie. OTF wurde von Microsoft und Adobe entwickelt und kombiniert die Funktionen von PostScript- und TrueType-Schriftformaten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Eine Datei mit der Erweiterung .ttf stellt Schriftartdateien dar, die auf der Schriftarttechnologie der TrueType-Spezifikationen basieren. Es wurde ursprünglich von Apple Computer, Inc. für Mac OS entwickelt und eingeführt und später von Microsoft für Windows OS übernommen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Typ 1-Schriftarten ist eine veraltete Adobe-Technologie, die in Desktop-basierter Publishing-Software und Druckern, die PostScript verwenden konnten, weit verbreitet war. Obwohl Typ-1-Schriftarten von vielen modernen Plattformen, Webbrowsern und mobilen Betriebssystemen nicht unterstützt werden, werden diese dennoch von einigen Betriebssystemen unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Eine Datei mit der Erweiterung .woff ist eine Webfont-Datei, die auf dem Web Open Font Format (WOFF) basiert. Es verfügt über einen formatspezifischen komprimierten Container, der entweder auf TrueType- (.TTF) oder OpenType-Schriftarten (.OTT) basiert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Eine Datei mit der Erweiterung .woff ist eine Webfont-Datei, die auf dem Web Open Font Format (WOFF) basiert. Es verfügt über einen formatspezifischen komprimierten Container, der entweder auf TrueType- (.TTF) oder OpenType-Schriftarten (.OTT) basiert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/font/woff/) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
