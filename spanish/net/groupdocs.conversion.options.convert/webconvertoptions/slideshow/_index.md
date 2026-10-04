---
title: "SlideShow"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Se aplica solo al convertir una presentación a Htmlgroupdocs.conversion.filetypes/webfiletype/html o Htmgroupdocs.conversion.filetypes/webfiletype/htm y se ignora para cualquier otra conversión. Especifica si la presentación se convierte en una presentación HTML interactiva con transiciones de diapositivas y animaciones de formas en lugar de la página HTML estática predeterminada. El valor predeterminado es false."
type: docs
weight: 50
url: /es/net/groupdocs.conversion.options.convert/webconvertoptions/slideshow/
---
## WebConvertOptions.SlideShow property

Se aplica solo al convertir una presentación a [`Html`](../../../groupdocs.conversion.filetypes/webfiletype/html) o [`Htm`](../../../groupdocs.conversion.filetypes/webfiletype/htm), y se ignora para cualquier otra conversión. Especifica si la presentación se convierte en una presentación HTML interactiva con transiciones de diapositivas y animaciones de formas, en lugar de la página HTML estática predeterminada. El valor predeterminado es false.

```csharp
public bool SlideShow { get; set; }
```

### Observaciones

El resultado es un único archivo HTML con estilos, scripts, imágenes, fuentes y medios incrustados. Las dos bibliotecas JavaScript que impulsan la presentación se cargan desde un CDN, por lo que la página necesita una conexión a internet para animarse y navegar.

### Ver también

* class [WebConvertOptions](../../webconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
