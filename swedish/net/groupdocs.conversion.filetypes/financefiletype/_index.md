---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar finansiella dokument Inkluderar följande typer Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx Läs mer om finansiella format härhttps//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /sv/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Definierar finansiella dokument Inkluderar följande typer: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) Läs mer om finansiella format [här](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FinanceFileType](financefiletype)() | Serialiseringskonstruktor |

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
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | I iXBRL är innehållet i XBRL inbäddat i xHTML‑filformat som använder XML‑taggar. Precis som XBRL är det rot‑elementet i iXBRL‑filer. XHTML‑formatet representerar dess innehåll som en samling av olika dokumenttyper och moduler. Alla filer i XHTML baseras på XML‑filformat och följer XML‑dokumentstandarderna. Läs mer om detta filformat [här](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) är ett datastream‑format för utbyte av finansiell information som utvecklades från Microsofts Open Financial Connectivity (OFC) och Intuits Open Exchange‑filformat. Läs mer om detta filformat [här](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL är en öppen internationell standard för digital affärsrapportering som används i stor utsträckning globalt. Det är ett XML‑baserat språk som använder XBRL‑element, kända som taggar, för att beskriva varje affärsdatapunkt och formulera data för rapportsortering och analys. Läs mer om detta filformat [här](https://docs.fileformat.com/finance/xbrl/). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
