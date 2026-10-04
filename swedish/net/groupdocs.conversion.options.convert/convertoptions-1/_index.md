---
title: "ConvertOptionsTFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Abstrakt generisk konverteringsalternativklass."
type: docs
weight: 1770
url: /sv/net/groupdocs.conversion.options.convert/convertoptions-1/
---
## ConvertOptions&lt;TFileType&gt; class

Abstrakt generisk konverteringsalternativklass.

```csharp
public abstract class ConvertOptions<TFileType> : ConvertOptions
    where TFileType : FileType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ConvertOptions](../convertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
