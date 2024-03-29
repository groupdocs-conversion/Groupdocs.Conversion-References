---
title: EmailLoadOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för att ladda epostdokument.
type: docs
weight: 2110
url: /sv/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Alternativ för att ladda e-postdokument.

```csharp
public sealed class EmailLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Initierar ny instans av[`EmailLoadOptions`](../emailloadoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Möjlighet att kontrollera om de ägda dokumenten i dokumentbehållaren måste konverteras |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Alternativ för att kontrollera om själva dokumentbehållaren måste konverteras Om den här egenskapen är sann kommer dokumentbehållaren att vara den första konverterade document |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Alternativ för att styra hur många nivåer i djupet som ska utföras konvertering |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Möjlighet att visa eller dölja "hemlig kopia" e-postadress. Standard: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Möjlighet att visa eller dölja e-postadressen "Cc". Standard: false. |
| [DisplayEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddress) { get; set; } | Möjlighet att visa eller dölja e-postadress. Standard: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Möjlighet att visa eller dölja "från" e-postadress. Standard: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Möjlighet att visa eller dölja e-posthuvudet. Standard: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Möjlighet att visa eller dölja "till" e-postadress. Standard: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | Mappningen mellan e-postmeddelanden[`EmailField`](../emailfield) och fälttext representation |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Inmatningsdokumentfiltyp. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentfiltyp. |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Definierar om behovet av att behålla den ursprungliga datumrubriksträngen i e-postmeddelandet när du sparar eller inte (standardvärdet är sant) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Timeout för laddning av externa resurser |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Hämtar eller ställer in UTC-förskjutningen (Coordinated Universal Time) för meddelandedatum. Den här egenskapen definierar tidszonsskillnaden mellan lokaltid och UTC. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Klonar aktuell instans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standard hash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namnutrymme [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
