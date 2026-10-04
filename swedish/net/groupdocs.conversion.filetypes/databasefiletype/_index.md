---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar databasdokument. Inkluderar följande filtyper Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /sv/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Definierar databasdokument. Inkluderar följande filtyper: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Serialiseringskonstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementerar [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | En fil med .log‑ändelse innehåller en lista med vanlig text med tidsstämpel. Vanligtvis loggas viss aktivitetsdetalj av programvaror eller operativsystem för att hjälpa utvecklare eller användare att spåra vad som hände under en viss tidsperiod. Läs mer om detta filformat [här](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | En fil med .nsf (Notes Storage Facility)-ändelse är ett databasfilformat som används av IBM Notes‑programvaran, som tidigare hette Lotus Notes. Den definierar schemat för att lagra olika typer av objekt såsom e‑post, möten, dokument, formulär och vyer. Läs mer om detta filformat [här](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | En fil med .sql‑ändelse är en Structured Query Language (SQL)-fil som innehåller kod för att arbeta med relationsdatabaser. Den används för att skriva SQL‑satser för CRUD‑operationer (Create, Read, Update, and Delete) på databaser. Läs mer om detta filformat [här](https://docs.fileformat.com/database/sql). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
