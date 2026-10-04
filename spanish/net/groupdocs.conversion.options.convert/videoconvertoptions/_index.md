---
title: "VideoConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones de conversión al tipo de video."
type: docs
weight: 2280
url: /es/net/groupdocs.conversion.options.convert/videoconvertoptions/
---
## VideoConvertOptions class

Opciones de conversión al tipo de video.

```csharp
public sealed class VideoConvertOptions : ConvertOptions<VideoFileType>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VideoConvertOptions](videoconvertoptions)() | Inicializa una nueva instancia de la clase [`VideoConvertOptions`](../videoconvertoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AudioFormat](../../groupdocs.conversion.options.convert/videoconvertoptions/audioformat) { get; set; } | Qué formato de audio se utilizará |
| [ExtractAudioOnly](../../groupdocs.conversion.options.convert/videoconvertoptions/extractaudioonly) { get; set; } | Si se establece en verdadero, extrae el audio del video |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [FramesPerSecond](../../groupdocs.conversion.options.convert/videoconvertoptions/framespersecond) { get; set; } | Fotogramas por segundo. El valor predeterminado es 30. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [VideoFileType](../../groupdocs.conversion.filetypes/videofiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
