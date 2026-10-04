---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till kalkylbladsfiltyp."
type: docs
weight: 2240
url: /sv/net/groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
## SpreadsheetConvertOptions class

Alternativ för konvertering till kalkylbladsfiltyp.

```csharp
public class SpreadsheetConvertOptions : CommonConvertOptions<SpreadsheetFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SpreadsheetConvertOptions](spreadsheetconvertoptions)() | Initierar en ny instans av klassen [`SpreadsheetConvertOptions`](../spreadsheetconvertoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/encoding) { get; set; } | Anger den kodning som ska användas vid konvertering till ett avgränsat format. |
| [Format](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. (2 egenskaper) |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementerar [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/password) { get; set; } | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
| [Separator](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/separator) { get; set; } | Anger den separator som ska användas vid konvertering till ett avgränsat format. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementerar [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/zoom) { get; set; } | Anger zoomnivån i procent. Standard är 100. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [SpreadsheetFileType](../../groupdocs.conversion.filetypes/spreadsheetfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
