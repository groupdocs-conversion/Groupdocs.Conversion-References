---
title: "MarkdownOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file markdown."
type: docs
weight: 2010
url: /it/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Opzioni per la conversione al tipo di file markdown.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Inizializza una nuova istanza della classe [`MarkdownOptions`](../markdownoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Esporta le immagini come base64. Il valore predefinito è true. Ignorato quando è impostato [`ImageSavingCallback`](./imagesavingcallback). |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Callback invocato una volta per immagine durante il salvataggio di Markdown. Consente al chiamante di conservare le immagini esternamente e sostituire l'URI incorporato nel documento. Ha la precedenza su [`ExportImagesAsBase64`](./exportimagesasbase64) quando non è null. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
