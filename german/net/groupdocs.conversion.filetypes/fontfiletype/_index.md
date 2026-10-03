---
title: "FontFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert Schriftdateien. Enthält die folgenden Typen Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Erfahren Sie mehr über Schriftformate hier https//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /de/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Definiert Schriftdateien. Enthält die folgenden Typen: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Erfahren Sie mehr über Schriftformate [hier](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FontFileType](fontfiletype)() | Serialisierungskonstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dateitypbeschreibung |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Die Dateierweiterung |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Die Dateifamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Das Dateiformat |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Eine Datei mit der Erweiterung .cff ist ein Compact Font Format und ist auch als PostScript Type 1 oder CIDFont bekannt. CFF dient als Container, um mehrere Schriftarten zusammen in einer einzigen Einheit, dem FontSet, zu speichern. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Eine Datei mit der Erweiterung .eot ist eine OpenType‑Schrift, die in ein Dokument eingebettet ist. Diese werden hauptsächlich in Web‑Dateien wie einer Webseite verwendet. Sie wurde von Microsoft erstellt und wird von Microsoft‑Produkten, einschließlich PowerPoint‑Präsentationen im .pps‑Format, unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Eine Datei mit der Erweiterung .otf bezieht sich auf das OpenType‑Schriftformat. Das OTF‑Schriftformat ist skalierbarer und erweitert die bestehenden Funktionen der TTF‑Formate für digitale Typografie. Entwickelt von Microsoft und Adobe, kombiniert OTF die Merkmale von PostScript‑ und TrueType‑Schriftformaten. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Eine Datei mit der Erweiterung .ttf stellt Schriftdateien dar, die auf der TrueType‑Spezifikation basieren. Sie wurde ursprünglich von Apple Computer, Inc. für macOS entwickelt und später von Microsoft für Windows‑OS übernommen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type‑1‑Schriften sind eine veraltete Adobe‑Technologie, die in Desktop‑Publishing‑Software und Druckern, die PostScript unterstützen, weit verbreitet war. Obwohl Type‑1‑Schriften in vielen modernen Plattformen, Web‑Browsern und mobilen Betriebssystemen nicht mehr unterstützt werden, sind sie in einigen Betriebssystemen weiterhin verfügbar. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Eine Datei mit der Erweiterung .woff ist eine Web‑Schriftdatei, die auf dem Web Open Font Format (WOFF) basiert. Sie enthält einen format­spezifischen komprimierten Container, der entweder auf TrueType‑(.TTF) oder OpenType‑(.OTT) Schriftarten beruht. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Eine Datei mit der Erweiterung .woff ist eine Web‑Schriftdatei, die auf dem Web Open Font Format (WOFF) basiert. Sie enthält einen format­spezifischen komprimierten Container, der entweder auf TrueType‑(.TTF) oder OpenType‑(.OTT) Schriftarten beruht. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/font/woff/). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
