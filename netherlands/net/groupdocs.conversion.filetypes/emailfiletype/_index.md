---
title: EmailFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert emailbestandsindelingen die worden gebruikt door emailtoepassingen om hun verschillende gegevens op te slaan waaronder emailberichten bijlagen mappen adresboeken enz. Omvat de volgende bestandstypen Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Meer informatie over emailindelingenhierhttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /nl/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Definieert e-mailbestandsindelingen die worden gebruikt door e-mailtoepassingen om hun verschillende gegevens op te slaan, waaronder e-mailberichten, bijlagen, mappen, adresboeken enz. Omvat de volgende bestandstypen: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . Meer informatie over e-mailindelingen[hier](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [EmailFileType](emailfiletype)() | Serialisatie-constructor |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | EML-bestandsindeling vertegenwoordigt e-mailberichten die zijn opgeslagen met behulp van Outlook en andere relevante toepassingen. Bijna alle e-mailclients ondersteunen dit bestandsformaat omdat het voldoet aan RFC-822 Internet Message Format Standard. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Het EMLX-bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail-applicatie gebruikt het EMLX-bestandsformaat voor het exporteren van de e-mails. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox-bestandsindeling is een generieke term die staat voor een container voor het verzamelen van elektronische postberichten. De berichten worden samen met hun bijlagen in de container opgeslagen. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG is een bestandsindeling die wordt gebruikt door Microsoft Outlook en Exchange om e-mailberichten, contacten, afspraken of andere taken op te slaan. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST of offline opslagbestanden vertegenwoordigen de mailboxgegevens van de gebruiker in offlinemodus op een lokale computer na registratie bij Exchange Server met behulp van Microsoft Outlook. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Bestanden met de extensie .PST vertegenwoordigen persoonlijke opslagbestanden van Outlook (ook wel persoonlijke opslagtabel genoemd) die verschillende gebruikersgegevens opslaan. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactgegevens. Het formaat wordt veel gebruikt voor gegevensuitwisseling tussen populaire toepassingen voor informatie-uitwisseling. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/email/vcf) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
