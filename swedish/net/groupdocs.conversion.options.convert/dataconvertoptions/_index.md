---
title: DataConvertOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för konvertering till datafiltyp.
type: docs
weight: 1350
url: /sv/net/groupdocs.conversion.options.convert/dataconvertoptions/
---
## DataConvertOptions class

Alternativ för konvertering till datafiltyp.

```csharp
public class DataConvertOptions : ConvertOptions<DataFileType>, IPagedConvertOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [DataConvertOptions](dataconvertoptions)() | Initierar ny instans av[`DataConvertOptions`](../dataconvertoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [PageNumber](../../groupdocs.conversion.options.convert/dataconvertoptions/pagenumber) { get; set; } | Sidnumret att börja konverteringen från. |
| [PagesCount](../../groupdocs.conversion.options.convert/dataconvertoptions/pagescount) { get; set; } | Antal sidor att konvertera från`Sidonummer` . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar nuvarande alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standard hash-funktion. |

### Se även

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [DataFileType](../../groupdocs.conversion.filetypes/datafiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* namnutrymme [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
