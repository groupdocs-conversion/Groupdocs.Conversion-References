---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het verwerken van bladwijzers in WordProcessing"
type: docs
weight: 2930
url: /nl/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

Opties voor het verwerken van bladwijzers in WordProcessing

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | Specificeert het standaardniveau in de documentstructuur waarop Word-bladwijzers worden weergegeven. Standaard is 0. Geldig bereik is 0 tot 9. |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | Specificeert hoeveel niveaus in de documentstructuur worden uitgeklapt wanneer het bestand wordt bekeken. Standaard is 0. Geldig bereik is 0 tot 9. Merk op dat deze optie niet werkt bij het opslaan naar XPS. |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | Specificeert hoeveel niveaus van koppen (alinea's opgemaakt met de Kop-stijlen) moeten worden opgenomen in de documentstructuur. Standaard is 0. Geldig bereik is 0 tot 9. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
