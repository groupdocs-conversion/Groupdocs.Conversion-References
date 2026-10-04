---
title: "FileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Bas-klass för filtyp"
type: docs
weight: 1130
url: /sv/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Bas-klass för filtyp

```csharp
public class FileType : Enumeration
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileType](filetype)() | Serialiseringskonstruktor |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Hämtar FileType för angivet fileExtension |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Returnerar FileType för angivet fileName |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Returnerar FileType för angiven document stream |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | Implementerar [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Returnerar alla uppräkningsvärden. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Implicit konvertering till string |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Okänd filtyp |

### Se även

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
