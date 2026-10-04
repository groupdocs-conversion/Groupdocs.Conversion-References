---
title: "EmailConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para la conversión al tipo de archivo Correo electrónico."
type: docs
weight: 1800
url: /es/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Opciones para la conversión al tipo de archivo Correo electrónico.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Inicializa una nueva instancia de la clase [`EmailConvertOptions`](../emailconvertoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | Un delegado para manejar el procesamiento personalizado de los archivos adjuntos de correo electrónico. El delegado recibe como parámetros el nombre del adjunto, el tipo de contenido y el flujo de datos del adjunto original, y devuelve el flujo de datos del adjunto modificado. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
