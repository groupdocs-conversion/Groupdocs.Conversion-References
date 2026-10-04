---
title: "VideoConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till videotyp."
type: docs
weight: 2280
url: /sv/net/groupdocs.conversion.options.convert/videoconvertoptions/
---
## VideoConvertOptions class

Alternativ för konvertering till videotyp.

```csharp
public sealed class VideoConvertOptions : ConvertOptions<VideoFileType>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VideoConvertOptions](videoconvertoptions)() | Initierar en ny instans av [`VideoConvertOptions`](../videoconvertoptions) klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AudioFormat](../../groupdocs.conversion.options.convert/videoconvertoptions/audioformat) { get; set; } | Vilket ljudformat som ska användas |
| [ExtractAudioOnly](../../groupdocs.conversion.options.convert/videoconvertoptions/extractaudioonly) { get; set; } | Om den är satt till true extraheras ljudet från videon |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [FramesPerSecond](../../groupdocs.conversion.options.convert/videoconvertoptions/framespersecond) { get; set; } | Bildrutor per sekund. Standard är 30. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [VideoFileType](../../groupdocs.conversion.filetypes/videofiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
