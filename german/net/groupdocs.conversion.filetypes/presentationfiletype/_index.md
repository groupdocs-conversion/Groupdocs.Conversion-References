---
title: PresentationFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert Präsentationsdateiformate die eine Sammlung von Datensätzen speichern um Präsentationsdaten wie Folien Formen Text Animationen Video Audio und eingebettete Objekte aufzunehmen. Umfasst die folgenden Dateitypen Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Erfahren Sie mehr über PräsentationsformateHierhttps//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /de/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definiert Präsentationsdateiformate, die eine Sammlung von Datensätzen speichern, um Präsentationsdaten wie Folien, Formen, Text, Animationen, Video, Audio und eingebettete Objekte aufzunehmen. Umfasst die folgenden Dateitypen: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Erfahren Sie mehr über Präsentationsformate[Hier](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Dateien mit der Erweiterung FODP repräsentieren OpenDocument Flat XML Presentation. Präsentationsdatei im OpenDocument-Format gespeichert, aber in einem flachen XML-Format anstelle des .ZIP-Containers gespeichert, der von standardmäßigen .ODP-Dateien verwendet wird |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Dateien mit der Erweiterung ODP stellen das Präsentationsdateiformat dar, das von OpenOffice.org im OASISOpen-Standard verwendet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Dateien mit der Erweiterung .OTP stellen Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Dateien mit der Erweiterung .POT stellen Microsoft PowerPoint-Vorlagendateien dar, die von PowerPoint 97-2003-Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Dateien mit der Erweiterung POTM sind Microsoft PowerPoint-Vorlagendateien mit Unterstützung für Makros. POTM-Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zum Erstellen weiterer Präsentationsdateien verwendet werden können. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Dateien mit der Erweiterung .POTX stellen Microsoft PowerPoint-Vorlagenpräsentationen dar, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint-Diashow, Dateien werden mit Microsoft PowerPoint für Diashowzwecke erstellt. Das Lesen und Erstellen von PPS-Dateien wird von Microsoft PowerPoint 97-2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Dateien mit der Erweiterung PPSM stellen ein makrofähiges Diashow-Dateiformat dar, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power Point Slide Show, Dateien werden mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Eine Datei mit der Erweiterung PPT stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien besteht, die als Diashow angezeigt werden. Es gibt das von Microsoft PowerPoint 97-2003 verwendete binäre Dateiformat an. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Dateien mit der Erweiterung PPTM sind makrofähige Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder höheren Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Dateien mit der Erweiterung PPTX sind Präsentationsdateien, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurden. Anders als die vorherige Version des Präsentationsdateiformats PPT, die binär war, basiert das PPTX-Format auf dem offenen XML-Präsentationsdateiformat von Microsoft PowerPoint. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pptx) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
