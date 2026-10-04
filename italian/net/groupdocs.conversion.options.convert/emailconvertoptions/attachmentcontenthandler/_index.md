---
title: "AttachmentContentHandler"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Un delegato per gestire l'elaborazione personalizzata degli allegati email. Il delegato riceve come parametri il nome dell'allegato, il tipo di contenuto e lo stream dell'allegato originale e restituisce lo stream dell'allegato modificato."
type: docs
weight: 20
url: /it/net/groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler/
---
## EmailConvertOptions.AttachmentContentHandler property

Un delegato per gestire l'elaborazione personalizzata degli allegati email. Il delegato riceve come parametri il nome dell'allegato, il tipo di contenuto e lo stream originale dell'allegato e restituisce lo stream dell'allegato modificato.

```csharp
public Func<string, string, Stream, Stream> AttachmentContentHandler { get; set; }
```

### IConversionConvertOptions

* class [EmailConvertOptions](../../emailconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
