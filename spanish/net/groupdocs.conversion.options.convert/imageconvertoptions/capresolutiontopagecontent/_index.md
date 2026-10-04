---
title: "CapResolutionToPageContent"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Cuando está activado, limita la resolución de renderizado PDF por página a la resolución raster nativa de la página, de modo que una página nunca se renderiza a un DPI mayor al que contiene realmente su imagen incrustada y emite esa página con sus dimensiones de píxel nativas más pequeñas y DPI nativo en la salida final en lugar de volver a inflarla al DPI solicitado. Sólo se ven afectadas las páginas escaneadas dominadas por imágenes; las páginas con texto o contenido vectorial nunca se suavizan y se emiten al DPI solicitado. Se omite cuando se establece una salida explícita Widthgroupdocs.conversion.options.convert/imageconvertoptions/width o Heightgroupdocs.conversion.options.convert/imageconvertoptions/height. El valor predeterminado es false, sin limitación; cada página se renderiza y emite al DPI solicitado."
type: docs
weight: 40
url: /es/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

Cuando está activado, limita la resolución de renderizado PDF por página a la resolución raster nativa de la página, de modo que una página nunca se renderiza a un DPI mayor al que contiene realmente su imagen incrustada, y emite esa página con sus dimensiones de píxel nativas (más pequeñas) y DPI nativo en la salida final en lugar de volver a inflarla al DPI solicitado. Sólo se ven afectadas las páginas dominadas por imágenes (escaneadas); las páginas con texto o contenido vectorial nunca se suavizan y se emiten al DPI solicitado. Se omite cuando se establece una salida explícita [`Width`](../width) o [`Height`](../height). El valor predeterminado es `false` (sin limitación; cada página se renderiza y emite al DPI solicitado).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### Ver también

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
