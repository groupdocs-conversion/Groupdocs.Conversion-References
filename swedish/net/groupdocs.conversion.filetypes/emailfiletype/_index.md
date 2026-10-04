---
title: "EmailFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar e‑postfilformat som används av e‑postprogram för att lagra deras olika data inklusive e‑postmeddelanden, bilagor, mappar, adressböcker etc. Inkluderar följande filtyper Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Läs mer om e‑postformat härhttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /sv/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Definierar e‑postfilformat som används av e‑postprogram för att lagra deras olika data inklusive e‑postmeddelanden, bilagor, mappar, adressböcker etc. Inkluderar följande filtyper: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Läs mer om e‑postformat [här](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EmailFileType](emailfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementerar [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | EML‑filformatet representerar e‑postmeddelanden som sparats med Outlook och andra relevanta program. Nästan alla e‑postklienter stödjer detta filformat på grund av dess efterlevnad av RFC‑822 Internet Message Format‑standard. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | EMLX‑filformatet är implementerat och utvecklat av Apple. Apple Mail‑applikationen använder EMLX‑filformatet för att exportera e‑postmeddelanden. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | ICS (iCalendar)-filformatet används för att representera och utbyta kalender‑ och schemaläggningsinformation såsom händelser, uppgifter och ledig/uppbokad‑data. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox-filformatet är en allmän term som representerar en behållare för en samling e‑postmeddelanden. Meddelandena lagras i behållaren tillsammans med deras bilagor. Läs mer om detta filformat [här](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e‑postmeddelanden, kontakter, möten eller andra uppgifter. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | En fil med .olm‑ändelse är en Microsoft Outlook‑fil för macOS. En OLM‑fil lagrar e‑postmeddelanden, journaler, kalenderdata och andra typer av programdata. Dessa liknar PST‑filer som används av Outlook på Windows. Däremot kan OLM‑filer som skapats av Outlook för Mac inte öppnas i Outlook för Windows. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST‑ eller Offline Storage‑filer representerar användarens brevlådedata i offlineläge på den lokala maskinen efter registrering mot Exchange‑server med Microsoft Outlook. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Filer med .PST‑ändelse representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar olika typer av användarinformation. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) eller vCard är ett digitalt filformat för lagring av kontaktinformation. Formatet används i stor utsträckning för datautbyte mellan populära informationsutbytesprogram. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/vcf). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
