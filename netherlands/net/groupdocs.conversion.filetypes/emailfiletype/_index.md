---
title: "EmailFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert e-mailbestandsformaten die door e-mailtoepassingen worden gebruikt om hun verschillende gegevens op te slaan, inclusief e-mailberichten, bijlagen, mappen, adresboeken, enz. Bevat de volgende bestandstypen Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Leer meer over e-mailformaten hierhttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /nl/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Definieert e-mailbestandsformaten die door e-mailtoepassingen worden gebruikt om hun verschillende gegevens op te slaan, inclusief e-mailberichten, bijlagen, mappen, adresboeken enz. Bevat de volgende bestandstypen: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Meer informatie over e-mailformaten [hier](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [EmailFileType](emailfiletype)() | Serialisatie‑constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstypebeschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Het EML-bestandsformaat vertegenwoordigt e-mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen. Bijna alle e-mailclients ondersteunen dit bestandsformaat vanwege de naleving van de RFC-822 Internet Message Format-standaard. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Het EMLX-bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail-toepassing gebruikt het EMLX-bestandsformaat voor het exporteren van e-mails. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | Het ICS (iCalendar)-bestandsformaat wordt gebruikt om agenda- en planningsinformatie, zoals evenementen, taken en vrije/bezet-data, te vertegenwoordigen en uit te wisselen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Het MBox-bestandsformaat is een algemene term die een container voor een verzameling elektronische e-mailberichten vertegenwoordigt. De berichten worden binnen de container opgeslagen, samen met hun bijlagen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG is een bestandsformaat dat door Microsoft Outlook en Exchange wordt gebruikt om e-mailberichten, contactpersonen, afspraken of andere taken op te slaan. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | Een bestand met de extensie .olm is een Microsoft Outlook‑bestand voor het macOS. Een OLM‑bestand slaat e-mailberichten, journaals, agenda‑gegevens en andere soorten toepassingsgegevens op. Deze lijken op PST‑bestanden die door Outlook op Windows worden gebruikt. OLM‑bestanden die door Outlook voor Mac zijn gemaakt, kunnen echter niet worden geopend in Outlook voor Windows. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST‑ of Offline Storage‑bestanden vertegenwoordigen de mailboxgegevens van de gebruiker in offline‑modus op de lokale machine na registratie bij Exchange Server met Microsoft Outlook. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Bestanden met de extensie .PST vertegenwoordigen Outlook Personal Storage‑bestanden (ook wel Personal Storage Table genoemd) die verschillende gebruikersinformatie opslaan. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactinformatie. Het formaat wordt veel gebruikt voor gegevensuitwisseling tussen populaire informatie‑uitwisselingsapplicaties. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/vcf). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
