---
title: "ConvertByPageTo"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Salva la pagina convertita come stream"
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionto/convertbypageto/
---
## IConversionTo.ConvertByPageTo method

Salva la pagina convertita come stream

```csharp
public IConversionByPageOptionsOrHandlerSetup ConvertByPageTo(
    Func<SavePageContext, Stream> convertedStreamProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Provider di flusso della pagina del documento convertito Il contesto di salvataggio |

### Valore restituito

Interfaccia di impostazione delle opzioni di pagina o del gestore per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionByPageOptionsOrHandlerSetup](../../iconversionbypageoptionsorhandlersetup)
* class [SavePageContext](../../../groupdocs.conversion/savepagecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
