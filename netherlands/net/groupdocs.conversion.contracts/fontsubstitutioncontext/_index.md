---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Beschrijft een enkele lettertypevervanging die optrad tijdens het laden of renderen van een brondocument. Instanties worden doorgegeven aan OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /nl/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Beschrijft een enkele lettertypevervanging die optrad tijdens het laden of renderen van een brondocument. Instanties worden doorgegeven aan [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Maakt een nieuw [`FontSubstitutionContext`](../fontsubstitutioncontext). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Naam van het lettertype dat door het brondocument wordt verwezen maar niet beschikbaar is voor de conversiepijplijn. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | Het substitutie‑bericht precies zoals gerapporteerd door de conversiepijplijn, letterlijk en onbewerkt. Voor documenten die lettertype‑namen structureel blootleggen kan dit `null` zijn (gebruik [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)); voor andere draagt het de volledige menselijk leesbare beschrijving, die zowel het ontbrekende als het vervangende lettertype benoemt. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Bestandsnaam van het bron‑document dat wordt geconverteerd. Wanneer de bron werd geleverd als een stream die geen FileStream is, bevat dit een gegenereerde identifier in plaats van een echte bestandsnaam. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Naam van het lettertype dat als vervanging wordt gebruikt. Kan `null` zijn voor documenten waarvan de engine de substitutie alleen als beschrijvende tekst rapporteert — in dat geval lees [`Reason`](./reason). |

### Zie ook

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
