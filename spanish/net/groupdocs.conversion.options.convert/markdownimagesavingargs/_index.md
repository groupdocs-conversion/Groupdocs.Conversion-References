---
title: "MarkdownImageSavingArgs"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Argumentos pasados a ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /es/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Argumentos pasados a [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Nombre de archivo (o id de marcador) incrustado como la URI de la imagen en la salida Markdown. Asigne para reescribir la URI. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Secuencia de destino en la que el convertidor escribirá los bytes de la imagen después de que este callback devuelva. Reemplácela con su propia secuencia de escritura (p. ej., un FileStream para persistencia en disco o un MemoryStream que planea leer después). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | Cuando es false (por defecto), el convertidor cierra [`ImageStream`](./imagestream) después de escribir — lo habitual para sustituciones de FileStream que deben vaciarse al disco. Establézcalo en true para mantener la secuencia abierta después de que la conversión finalice (típico para un MemoryStream que planea leer usted mismo); el llamador entonces es responsable de su eliminación. |

### Ver también

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
