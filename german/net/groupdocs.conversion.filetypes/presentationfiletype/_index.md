---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert Präsentationsdateiformate, die eine Sammlung von Datensätzen speichern, um Präsentationsdaten wie Folien, Formen, Text, Animationen, Video, Audio und eingebettete Objekte zu beherbergen. Enthält die folgenden Dateitypen Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Weitere Informationen zu Präsentationsformaten finden Sie hierhttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /de/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definiert Präsentationsdateiformate, die eine Sammlung von Datensätzen speichern, um Präsentationsdaten wie Folien, Formen, Text, Animationen, Video, Audio und eingebettete Objekte zu beherbergen. Enthält die folgenden Dateitypen: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Weitere Informationen zu Präsentationsformaten finden Sie [hier](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Dateien mit der Erweiterung FODP stellen eine OpenDocument Flat XML Presentation dar. Die Präsentationsdatei wird im OpenDocument-Format gespeichert, jedoch in einem flachen XML-Format anstelle des .ZIP‑Containers, der von Standard‑ .ODP‑Dateien verwendet wird. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Dateien mit der Erweiterung ODP stellen das von OpenOffice.org im OASIS‑Open‑Standard verwendete Präsentationsdateiformat dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Dateien mit der Erweiterung .OTP stellen Präsentationsvorlagendateien dar, die von Anwendungen im OASIS‑OpenDocument‑Standardformat erstellt wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Dateien mit der Erweiterung .POT stellen Microsoft PowerPoint‑Vorlagendateien dar, die mit PowerPoint‑Versionen 97‑2003 erstellt wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Dateien mit der Erweiterung POTM sind Microsoft PowerPoint‑Vorlagendateien mit Makro‑Unterstützung. POTM‑Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zur Erstellung weiterer Präsentationsdateien verwendet werden können. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Dateien mit der Erweiterung .POTX stellen Microsoft PowerPoint‑Vorlagepräsentationen dar, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint‑Diashow, Dateien werden mit Microsoft PowerPoint für Diashow‑Zwecke erstellt. Das Lesen und Erstellen von PPS‑Dateien wird von Microsoft PowerPoint 97‑2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Dateien mit der Erweiterung PPSM stellen ein Makro‑aktiviertes Diashow‑Dateiformat dar, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power‑Point‑Diashow, Dateien werden mit Microsoft PowerPoint 2007 und höher für Diashow‑Zwecke erstellt. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Eine Datei mit der Erweiterung PPT stellt eine PowerPoint‑Datei dar, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. Sie gibt das binäre Dateiformat an, das von Microsoft PowerPoint 97‑2003 verwendet wird. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Dateien mit der Erweiterung PPTM sind makro‑aktivierte Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Dateien mit der Erweiterung PPTX sind Präsentationsdateien, die mit der beliebten Microsoft PowerPoint‑Anwendung erstellt wurden. Im Gegensatz zur vorherigen Version des Präsentationsdateiformats PPT, das binär war, basiert das PPTX‑Format auf dem offenen XML‑Präsentationsdateiformat von Microsoft PowerPoint. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/pptx). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
