---
title: "SlideShow"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Si applica solo alla conversione di una presentazione in Htmlgroupdocs.conversion.filetypes/webfiletype/html o Htmgroupdocs.conversion.filetypes/webfiletype/htm e viene ignorato per tutte le altre conversioni. Specifica se la presentazione diventa una presentazione HTML interattiva con transizioni diapositive e animazioni di forme invece della pagina HTML statica predefinita. Il valore predefinito è false."
type: docs
weight: 50
url: /it/net/groupdocs.conversion.options.convert/webconvertoptions/slideshow/
---
## WebConvertOptions.SlideShow property

Si applica solo alla conversione di una presentazione in [`Html`](../../../groupdocs.conversion.filetypes/webfiletype/html) o [`Htm`](../../../groupdocs.conversion.filetypes/webfiletype/htm), e viene ignorato per tutte le altre conversioni. Specifica se la presentazione diventa una presentazione HTML interattiva con transizioni diapositive e animazioni di forme, invece della pagina HTML statica predefinita. Il valore predefinito è false.

```csharp
public bool SlideShow { get; set; }
```

### Osservazioni

Il risultato è un unico file HTML con stili, script, immagini, font e media incorporati. Le due librerie JavaScript che gestiscono la presentazione vengono caricate da un CDN, quindi la pagina necessita di una connessione internet per animare e navigare.

### IConversionConvertOptions

* class [WebConvertOptions](../../webconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
