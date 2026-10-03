---
title: "EmailFileType"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Definiert E‑Mail‑Dateiformate, die von E‑Mail‑Anwendungen verwendet werden, um ihre verschiedenen Daten einschließlich E‑Mail‑Nachrichten, Anhänge, Ordner, Adressbücher usw. zu speichern. Enthält die folgenden Dateitypen Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Erfahren Sie mehr über E‑Mail‑Formate hierhttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /de/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Definiert E‑Mail‑Dateiformate, die von E‑Mail‑Anwendungen verwendet werden, um ihre verschiedenen Daten einschließlich E‑Mail‑Nachrichten, Anhänge, Ordner, Adressbücher usw. zu speichern. Enthält die folgenden Dateitypen: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Erfahren Sie mehr über E‑Mail‑Formate [hier](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EmailFileType](emailfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Das EML-Dateiformat stellt E-Mail-Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Fast alle E-Mail-Clients unterstützen dieses Dateiformat, da es dem RFC-822 Internet Message Format Standard entspricht. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. Die Apple‑Mail‑Anwendung verwendet das EMLX-Dateiformat zum Exportieren der E‑Mails. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | Das ICS (iCalendar)-Dateiformat wird verwendet, um Kalender‑ und Terminplanungsinformationen wie Ereignisse, Aufgaben und Frei‑/Belegt‑Daten darzustellen und auszutauschen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Das MBox-Dateiformat ist ein generischer Begriff, der einen Container für eine Sammlung von elektronischen Nachrichten darstellt. Die Nachrichten werden zusammen mit ihren Anhängen im Container gespeichert. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E‑Mail‑Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | Eine Datei mit der Erweiterung .olm ist eine Microsoft‑Outlook‑Datei für das macOS. Eine OLM‑Datei speichert E‑Mail‑Nachrichten, Journale, Kalenderdaten und andere Arten von Anwendungsdaten. Diese sind ähnlich zu PST‑Dateien, die von Outlook unter Windows verwendet werden. Allerdings können OLM‑Dateien, die von Outlook für Mac erstellt wurden, nicht in Outlook für Windows geöffnet werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST‑ oder Offline‑Storage‑Dateien stellen die Postfachdaten eines Benutzers im Offline‑Modus auf dem lokalen Rechner dar, nachdem er sich über Microsoft Outlook beim Exchange‑Server registriert hat. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Dateien mit der Erweiterung .PST stellen Outlook Personal Storage Files (auch Personal Storage Table genannt) dar, die eine Vielzahl von Benutzerdaten speichern. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. Das Format wird häufig für den Datenaustausch zwischen beliebten Informationsaustausch‑Anwendungen verwendet. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/vcf). |

### Siehe auch

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
