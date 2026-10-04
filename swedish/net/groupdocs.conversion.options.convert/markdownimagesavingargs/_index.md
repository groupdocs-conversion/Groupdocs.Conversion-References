---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Argument som skickas till ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /sv/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Argument som skickas till [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Filnamn (eller platshållar‑id) inbäddat som bild‑URI i Markdown‑utdata. Tilldela för att skriva om URI:n. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Destinationsström som konverteraren kommer att skriva bild‑bytes till efter att detta återanrop har returnerat. Ersätt den med din egen skrivbara ström (t.ex. en FileStream för lagring på disk eller en MemoryStream som du avser att läsa efteråt). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | När falskt (standard) stänger konverteraren [`ImageStream`](./imagestream) efter skrivning — vanligt för FileStream‑ersättningar som bör spolas till disk. Sätt till sant för att hålla strömmen öppen efter att konverteringen är klar (typiskt för en MemoryStream som du avser att läsa själv); anroparen äger då avyttringen. |

### Se även

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
