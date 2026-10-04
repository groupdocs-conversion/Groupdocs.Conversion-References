---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till Email-filtyp."
type: docs
weight: 1800
url: /sv/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Alternativ för konvertering till Email-filtyp.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Initierar en ny instans av [`EmailConvertOptions`](../emailconvertoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | En delegat för att hantera anpassad behandling av e‑postbilagor. Delegaten tar bilagans namn, innehållstyp och den ursprungliga bilagestreamen som parametrar och returnerar den modifierade bilagestreamen. |
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

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
