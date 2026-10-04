---
title: "AudioLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos de audio."
type: docs
weight: 2390
url: /es/net/groupdocs.conversion.options.load/audioloadoptions/
---
## AudioLoadOptions class

Opciones para cargar documentos de audio.

```csharp
public sealed class AudioLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AudioLoadOptions](audioloadoptions)() | Inicializa una nueva instancia de la clase [`AudioLoadOptions`](../audioloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/audioloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |
| [SetAudioConnector](../../groupdocs.conversion.options.load/audioloadoptions/setaudioconnector)(IAudioConnector) | Establece el conector de documento de audio |

### Ver también

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
