---
title: EmailFileType
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Definiert EMailDateiformate die von EMailAnwendungen verwendet werden um ihre verschiedenen Daten zu speichern einschließlich EMailNachrichten Anhänge Ordner Adressbücher usw. Umfasst die folgenden Dateitypen Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Erfahren Sie mehr über EMailFormateHierhttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /de/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Definiert E-Mail-Dateiformate, die von E-Mail-Anwendungen verwendet werden, um ihre verschiedenen Daten zu speichern, einschließlich E-Mail-Nachrichten, Anhänge, Ordner, Adressbücher usw. Umfasst die folgenden Dateitypen: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . Erfahren Sie mehr über E-Mail-Formate[Hier](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmailFileType](emailfiletype)() | Serialisierungskonstruktor |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Das EML-Dateiformat stellt E-Mail-Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Fast alle E-Mail-Clients unterstützen dieses Dateiformat aufgrund seiner Konformität mit dem RFC-822 Internet Message Format Standard. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. Die Apple Mail-Anwendung verwendet das EMLX-Dateiformat zum Exportieren der E-Mails. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox-Dateiformat ist ein allgemeiner Begriff, der einen Container zum Sammeln von E-Mail-Nachrichten darstellt. Die Nachrichten werden zusammen mit ihren Anhängen im Container gespeichert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange zum Speichern von E-Mail-Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST- oder Offlinespeicherdateien stellen die Postfachdaten des Benutzers im Offlinemodus auf dem lokalen Computer nach der Registrierung bei Exchange Server mit Microsoft Outlook dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Dateien mit der Erweiterung .PST stellen persönliche Outlook-Speicherdateien (auch persönliche Speichertabelle genannt) dar, in denen verschiedene Benutzerinformationen gespeichert werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. Das Format wird häufig für den Datenaustausch zwischen beliebten Informationsaustauschanwendungen verwendet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/vcf) . |

### Siehe auch

* class [FileType](../filetype)
* namensraum [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
