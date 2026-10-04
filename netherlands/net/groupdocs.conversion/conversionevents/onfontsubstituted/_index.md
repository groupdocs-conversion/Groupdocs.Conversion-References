---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Wordt afgevuurd wanneer een lettertype dat door het brondocument wordt gerefereerd niet beschikbaar is en wordt vervangen, hetzij door een door de klant geleverde FontSubstitutegroupdocs.conversion.contracts/fontsubstitute‑regel, hetzij door het geconfigureerde standaardlettertype, of door de interne fallback van de conversiepijplijn."
type: docs
weight: 80
url: /nl/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Wordt afgevuurd wanneer een lettertype dat door het brondocument wordt gerefereerd niet beschikbaar is en wordt vervangen (hetzij door een door de klant geleverde [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute)‑regel, hetzij door het geconfigureerde standaardlettertype, of door de interne fallback van de conversiepijplijn).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Opmerkingen

Het evenement wordt gededupliceerd per `(SourceFileName, OriginalFontName)` binnen één `Converter.Convert(...)`‑aanroep — abonnees ontvangen hooguit één melding per ontbrekend lettertype per brondocument. Wordt synchroon afgevuurd op de conversiedraad. Wordt niet opgewekt voor afbeeldingsconversies.

Voor presentatiedocumenten wordt lettertypevervanging alleen gedetecteerd op Windows, omdat de engine dit oplost via platformspecifieke lettertypematching die niet beschikbaar is op andere besturingssystemen.

### Zie ook

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
