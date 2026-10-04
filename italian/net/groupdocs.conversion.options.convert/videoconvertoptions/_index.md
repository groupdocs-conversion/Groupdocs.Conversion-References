---
title: "VideoConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo Video."
type: docs
weight: 2280
url: /it/net/groupdocs.conversion.options.convert/videoconvertoptions/
---
## VideoConvertOptions class

Opzioni per la conversione al tipo Video.

```csharp
public sealed class VideoConvertOptions : ConvertOptions<VideoFileType>
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [VideoConvertOptions](videoconvertoptions)() | Inizializza una nuova istanza della classe [`VideoConvertOptions`](../videoconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AudioFormat](../../groupdocs.conversion.options.convert/videoconvertoptions/audioformat) { get; set; } | Quale formato audio utilizzare |
| [ExtractAudioOnly](../../groupdocs.conversion.options.convert/videoconvertoptions/extractaudioonly) { get; set; } | Se impostato su true, estrae l'audio dal video |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [FramesPerSecond](../../groupdocs.conversion.options.convert/videoconvertoptions/framespersecond) { get; set; } | Fotogrammi al secondo. Il valore predefinito è 30. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [VideoFileType](../../groupdocs.conversion.filetypes/videofiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
