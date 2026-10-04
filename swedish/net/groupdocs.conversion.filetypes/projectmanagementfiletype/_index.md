---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar projektfilformat som skapas av projektledningsprogramvara såsom Microsoft Project, Primavera P6 etc. En projektfil är en samling av uppgifter, resurser och deras schemaläggning för att få ett mätbart resultat i form av en produkt eller en tjänst. Projektledningsdokument. Inkluderar följande filtyper Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. Läs mer om projektledningsformat härhttps//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /sv/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Definierar projektfilformat som skapas av projektledningsprogramvara såsom Microsoft Project, Primavera P6 etc. En projektfil är en samling av uppgifter, resurser och deras schemaläggning för att få ett mätbart resultat i form av en produkt eller en tjänst. Projektledningsdokument. Inkluderar följande filtyper: [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). Läs mer om projektledningsformat [här](https://wiki.fileformat.com/project-management).

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP är Microsoft Project-datafil som lagrar information relaterad till projektledning på ett integrerat sätt. Läs mer om detta filformat [här](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Microsoft Project-mallfiler innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange-filformat är ett ASCII-filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra program som stödjer MPX-filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating. Läs mer om detta filformat [här](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | XER-filformatet är ett proprietärt projektfilformat som används av Primavera P6:s projektplanerings- och hanteringsapplikation. Läs mer om detta filformat [här](https://docs.fileformat.com/project-management/xer). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
