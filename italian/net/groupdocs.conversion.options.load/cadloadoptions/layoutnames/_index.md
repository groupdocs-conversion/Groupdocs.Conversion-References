---
title: "LayoutNames"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Specifica quali layout CAD devono essere convertiti"
type: docs
weight: 70
url: /it/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Specifica quali layout CAD devono essere convertiti

```csharp
public string[] LayoutNames { get; set; }
```

### Osservazioni

Non rispettato durante la conversione in PDF/UA-1. Tale destinazione rende il disegno come una singola pagina taggata, che non può contenere un foglio per ogni layout selezionato, quindi l'intero disegno viene convertito invece e nulla qui si applica. Tutte le altre destinazioni, incluso PDF, rispettano la selezione. Su queste destinazioni, i nomi sono confrontati esattamente con i layout presenti nel disegno, quindi un nome che differisce solo per maiuscole/minuscole è considerato un nome diverso. Un nome che non corrisponde a nulla viene scartato e costa al chiamante solo quel foglio; un elenco in cui nulla corrisponde provoca il fallimento della conversione con un [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) che indica i nomi mancati e i layout che il disegno possiede, anziché rendere i fogli che il chiamante non ha richiesto. Un disegno che non contiene alcun layout è esente: non c'è nulla a cui un nome possa corrispondere, quindi nessuno viene rifiutato.

### IConversionConvertOptions

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
