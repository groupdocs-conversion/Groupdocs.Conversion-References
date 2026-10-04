---
title: "IResourceLoadingOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Rappresenta un insieme di opzioni per controllare come verranno caricati le risorse esterne"
type: docs
weight: 2640
url: /it/net/groupdocs.conversion.options.load/iresourceloadingoptions/
---
## IResourceLoadingOptions interface

Rappresenta un insieme di opzioni per controllare come verranno caricati le risorse esterne

```csharp
public interface IResourceLoadingOptions
```

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [SkipExternalResources](../../groupdocs.conversion.options.load/iresourceloadingoptions/skipexternalresources) { get; set; } | Se true, tutte le risorse esterne non verranno caricate eccetto quelle presenti nell'elenco [`WhitelistedResources`](./whitelistedresources). Predefinito: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/iresourceloadingoptions/whitelistedresources) { get; set; } | Risorse esterne che saranno sempre caricate |

### IConversionConvertOptions

* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
