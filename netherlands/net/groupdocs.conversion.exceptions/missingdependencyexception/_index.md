---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "GroupDocs-uitzondering die wordt gegooid wanneer een conversie niet kan worden uitgevoerd omdat een assembly waar het van afhankelijk is niet aanwezig is in de uitvoer van de applicatie. Het document is niet de schuldige."
type: docs
weight: 1030
url: /nl/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

GroupDocs exception gegooid wanneer een conversie niet kan worden uitgevoerd omdat een assembly waar het van afhankelijk is niet aanwezig is in de uitvoer van de applicatie. Het document is niet de schuld.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Standaardconstructor |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Maakt een exceptie‑instantie met een bericht |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Maakt een uitzondering‑instantie met een bericht en geeft de interne uitzondering door |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Maakt een uitzondering‑instantie met de naam van de assembly die niet kon worden geladen |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | De eenvoudige naam van de assembly die niet kon worden geladen, of null wanneer deze niet kon worden bepaald. |

### Zie ook

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
