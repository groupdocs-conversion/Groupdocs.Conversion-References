---
title: "KeepImageStreamOpen"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Cuando es false por defecto el convertidor cierra ImageStreamgroupdocs.conversion.options.convert/markdownimagesavingargs/imagestream después de escribir, idiomático para reemplazos de FileStream que deben vaciarse al disco. Establezca true para mantener la secuencia abierta después de que la conversión finalice, típico para un MemoryStream que pretenda leer usted mismo; el llamador entonces posee la eliminación."
type: docs
weight: 30
url: /es/net/groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen/
---
## MarkdownImageSavingArgs.KeepImageStreamOpen property

Cuando es false (por defecto), el convertidor cierra [`ImageStream`](../imagestream) después de escribir — idiomático para reemplazos de FileStream que deben vaciarse al disco. Establezca true para mantener la secuencia abierta después de que la conversión finalice (típico para un MemoryStream que pretenda leer usted mismo); el llamador entonces posee la eliminación.

```csharp
public bool KeepImageStreamOpen { get; set; }
```

### Ver también

* class [MarkdownImageSavingArgs](../../markdownimagesavingargs)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
