---
title: FileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Filtyp basklass
type: docs
weight: 850
url: /sv/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Filtyp basklass

```csharp
public class FileType : Enumeration
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [FileType](filetype)() | Serialiseringskonstruktor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypsbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filtillägget |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Hämtar FileType för tillhandahållen fileExtension |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Returnerar filtyp för angivet filnamn |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Returnerar filtyp för tillhandahållen dokumentström |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standard hash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Returnerar alla uppräkningsvärden. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Implicit konvertering till string |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Okänd filtyp |

### Se även

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->