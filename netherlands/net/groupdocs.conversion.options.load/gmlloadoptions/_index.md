---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van GML‑documenten."
type: docs
weight: 2550
url: /nl/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Opties voor het laden van GML‑documenten.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Initialiseert een nieuw exemplaar van de [`GmlLoadOptions`](../gmlloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Invoerdocument bestandstype. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Stelt de gewenste paginahoogte in voor het converteren van een GIS‑document. Standaard is 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Bepaalt of Conversie XML-schema's van internet mag laden. Indien ingesteld op false, worden schema's met absolute URI's die niet beginnen met ‘file://’ niet geladen. Standaard is false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Bepaalt of Conversie attributen in een GML-bestand mag parseren waarin een XML-schema ontbreekt of niet kan worden geladen. Indien ingesteld op true, vereist de Conversie-lezer de aanwezigheid van een XML-schema niet. Standaard is false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Spatiegescheiden lijst van URI-paren. De eerste URI in elk paar is een URI van de namespace, de tweede URI is een pad naar het XML-schema van de namespace. Indien ingesteld op null, probeert Conversie de schemaLocation uit het root‑element van het document te lezen. Standaard is null |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Stelt de gewenste paginabreedte in voor het converteren van een GIS‑document. Standaard is 1000. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
