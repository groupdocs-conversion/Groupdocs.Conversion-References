---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Aggregeert gebeurtenishandlers voor de levenscyclus van conversies. Geef een instantie door aan de Converter./converter constructors events‑parameter of aan de fluente WithEvents‑methode. Geef de voorkeur aan dit boven de individuele ConverterSettings./convertersettings‑handler‑eigenschappen, die verouderd zijn."
type: docs
weight: 850
url: /nl/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Aggregeert gebeurtenishandlers voor de levenscyclus van conversies. Geef een instantie door aan de [`Converter`](../converter) constructor's `events`‑parameter of aan de fluente `WithEvents`‑methode. Geef de voorkeur aan dit boven de individuele [`ConverterSettings`](../convertersettings)‑handler‑eigenschappen, die verouderd zijn.

```csharp
public sealed class ConversionEvents
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ConversionEvents](conversionevents)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Wordt geactiveerd wanneer de compressie van de conversie‑output voltooid is. Wordt alleen aangeroepen in builds die de compressiepijplijn (LIB_ZIP) bevatten. |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Wordt één keer geactiveerd wanneer de conversierun eindigt, ongeacht succes of falen. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Wordt periodiek geactiveerd met de voortgang van de conversie als een percentage (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Wordt één keer geactiveerd aan het begin van de conversierun, voordat een document wordt verwerkt. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Wordt één keer geactiveerd per volledige‑documentconversie die succesvol voltooid is. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Wordt één keer geactiveerd per volledige‑documentconversie die faalt. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Wordt geactiveerd wanneer een lettertype dat door het bron‑document wordt gerefereerd niet beschikbaar is en wordt vervangen (ofwel door een door de klant geleverde [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute)‑regel, door het geconfigureerde standaardlettertype, of door de interne fallback van de conversiepijplijn). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Wordt één keer per pagina geactiveerd wanneer een per‑pagina conversie succesvol voltooid is. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Wordt één keer per pagina geactiveerd wanneer een per‑pagina conversie faalt. |

### Zie ook

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
