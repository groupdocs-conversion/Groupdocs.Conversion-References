---
title: "AutoDetectRtlDirection"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Quando è true, i paragrafi e le run predefiniti il cui testo è prevalentemente da destra a sinistra avranno i loro flag bidi riparati prima della conversione. Questo corrisponde all'euristica applicata da Microsoft Word e LibreOffice e corregge il rendering dei documenti arabi/ebraici prodotti da generatori, in particolare Google Docs, che emettono OOXML senza ltwbidi/gt e con ltwrtl wval0/gt su run che contengono solo script RTL. Impostare su false per preservare l'interpretazione rigorosa di OOXML del markup di origine."
type: docs
weight: 20
url: /it/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

Quando è true (predefinito), i paragrafi e le run il cui testo è prevalentemente da destra a sinistra avranno i loro flag bidi riparati prima della conversione. Questo corrisponde all'euristica applicata da Microsoft Word e LibreOffice e corregge il rendering di documenti arabi/ebraici prodotti da generatori (in particolare Google Docs) che generano OOXML senza &lt;w:bidi/&gt; e con &lt;w:rtl w:val="0"/&gt; sulle run che contengono solo script RTL. Impostare a false per preservare un'interpretazione OOXML rigorosa del markup di origine.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### IConversionConvertOptions

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
