---
title: "DiagramConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till Diagram-filtyp."
type: docs
weight: 1780
url: /sv/net/groupdocs.conversion.options.convert/diagramconvertoptions/
---
## DiagramConvertOptions class

Alternativ för konvertering till Diagram-filtyp.

```csharp
public sealed class DiagramConvertOptions : CommonConvertOptions<DiagramFileType>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DiagramConvertOptions](diagramconvertoptions)() | Initierar en ny instans av [`DiagramConvertOptions`](../diagramconvertoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoFitPageToDrawingContent](../../groupdocs.conversion.options.convert/diagramconvertoptions/autofitpagetodrawingcontent) { get; set; } | Definierar om sidan behöver förstoras för att passa ritningsinnehållet eller inte |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementerar [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementerar [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [DiagramFileType](../../groupdocs.conversion.filetypes/diagramfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
