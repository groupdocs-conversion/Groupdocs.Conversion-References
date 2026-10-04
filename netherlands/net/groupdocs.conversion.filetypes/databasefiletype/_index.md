---
title: "DatabaseBestandstype"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert database-documenten. Bevat de volgende bestandstypen Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /nl/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Definieert database-documenten. Bevat de volgende bestandstypen: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Serialisatie‑constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstypebeschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementeert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Stringrepresentatie |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | Een bestand met de extensie .log bevat een lijst van platte tekst met tijdstempel. Gewoonlijk wordt bepaalde activiteitsdetail vastgelegd door de software of besturingssystemen om ontwikkelaars of gebruikers te helpen bij het volgen van wat er op een bepaald tijdstip gebeurde. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | Een bestand met de extensie .nsf (Notes Storage Facility) is een databasebestandsformaat dat wordt gebruikt door de IBM Notes‑software, die eerder bekend stond als Lotus Notes. Het definieert het schema om verschillende soorten objecten op te slaan, zoals e‑mail, afspraken, documenten, formulieren en weergaven. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | Een bestand met de extensie .sql is een Structured Query Language (SQL)-bestand dat code bevat om met relationele databases te werken. Het wordt gebruikt om SQL‑statements te schrijven voor CRUD‑ (Create, Read, Update, Delete) bewerkingen op databases. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/database/sql). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
