---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "GroupDocs‑undantag som kastas när en konvertering inte kan köras eftersom ett assembly som den är beroende av inte finns i applikationens utdata. Dokumentet är inte orsaken."
type: docs
weight: 1030
url: /sv/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

GroupDocs-undantag kastas när en konvertering inte kan köras eftersom ett beroende assembly inte finns i applikationens output. Dokumentet är inte orsaken.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Standardkonstruktor |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Skapar ett undantags‑objekt med ett meddelande. |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Skapar ett undantags‑objekt med ett meddelande och vidarebefordrar det inre undantaget. |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Skapar ett undantags‑objekt som namnger det assembly som inte kunde laddas. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | Det enkla namnet på det assembly som inte kunde laddas, eller null när det inte kunde bestämmas. |

### Se även

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
