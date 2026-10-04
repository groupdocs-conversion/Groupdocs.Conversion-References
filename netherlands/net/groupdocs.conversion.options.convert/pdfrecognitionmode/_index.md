---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Staat toe te controleren hoe een PDF-document wordt geconverteerd naar een tekstverwerkingsdocument."
type: docs
weight: 2160
url: /nl/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Staat toe te controleren hoe een PDF-document wordt geconverteerd naar een tekstverwerkingsdocument.

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Retourneert een string die het huidige object vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Volledige herkenningsmodus, de engine voert groepering en meerlagige analyse uit om de intentie van de oorspronkelijke documentauteur te herstellen en een zo bewerkbaar mogelijk document te produceren. Het nadeel is dat het uitvoerdocument er anders uit kan zien dan het oorspronkelijke PDF‑bestand. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Deze modus is snel en geschikt om het oorspronkelijke uiterlijk van het PDF‑bestand zo veel mogelijk te behouden, maar de bewerkbaarheid van het resulterende document kan beperkt zijn. Elk visueel gegroepeerd tekstblok in het oorspronkelijke PDF‑bestand wordt omgezet in een tekstvak in het resulterende document. Dit zorgt voor een maximale gelijkenis tussen het uitvoerdocument en het oorspronkelijke PDF‑bestand. Het uitvoerdocument ziet er goed uit, maar bestaat volledig uit tekstvakken, waardoor verder bewerken van het document in Microsoft Word behoorlijk moeilijk kan zijn. Dit is de standaardmodus. |

### Zie ook

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
