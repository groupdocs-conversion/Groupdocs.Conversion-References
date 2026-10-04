---
title: "CapResolutionToPageContent"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Quando impostato, limita la risoluzione di rendering PDF per pagina alla risoluzione raster nativa della pagina, in modo che una pagina non venga mai renderizzata a un DPI superiore a quello effettivamente contenuto nella sua immagine incorporata e venga emessa con le sue dimensioni pixel native più piccole e DPI nativi nell'output finale invece di essere reinflata al DPI richiesto. Solo le pagine di scansione dominate dalle immagini sono interessate; le pagine con testo o contenuto vettoriale non vengono mai ammorbidite e vengono emesse al DPI richiesto. Viene ignorato quando è impostato un valore esplicito di output Widthgroupdocs.conversion.options.convert/imageconvertoptions/width o Heightgroupdocs.conversion.options.convert/imageconvertoptions/height. Il valore predefinito è false, nessun limitazione; ogni pagina viene renderizzata ed emessa al DPI richiesto."
type: docs
weight: 40
url: /it/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

Quando impostato, limita la risoluzione di rendering PDF per pagina alla risoluzione raster nativa della pagina, in modo che una pagina non venga mai renderizzata a un DPI superiore a quello effettivamente contenuto nella sua immagine incorporata, e la emette con le sue dimensioni pixel native (più piccole) e DPI nativi nell'output finale invece di reinflarla al DPI richiesto. Solo le pagine dominate dalle immagini (scansione) sono interessate; le pagine con testo o contenuto vettoriale non vengono mai ammorbidite e vengono emesse al DPI richiesto. Viene ignorato quando è impostato un valore esplicito di output [`Width`](../width) o [`Height`](../height). Il valore predefinito è `false` (nessuna limitazione; ogni pagina è renderizzata ed emessa al DPI richiesto).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### IConversionConvertOptions

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
