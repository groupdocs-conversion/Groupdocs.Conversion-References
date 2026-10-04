---
title: "AttachmentContentHandler"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Un delegado para manejar el procesamiento personalizado de los archivos adjuntos de correo electrónico. El delegado recibe como parámetros el nombre del adjunto, el tipo de contenido y el flujo del adjunto original, y devuelve el flujo del adjunto modificado."
type: docs
weight: 20
url: /es/net/groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler/
---
## EmailConvertOptions.AttachmentContentHandler property

Un delegado para manejar el procesamiento personalizado de los archivos adjuntos de correo electrónico. El delegado recibe como parámetros el nombre del adjunto, el tipo de contenido y el flujo de datos del adjunto original, y devuelve el flujo de datos del adjunto modificado.

```csharp
public Func<string, string, Stream, Stream> AttachmentContentHandler { get; set; }
```

### Ver también

* class [EmailConvertOptions](../../emailconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
