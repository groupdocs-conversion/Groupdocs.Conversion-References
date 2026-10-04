---
title: "IConversionFrom"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Configura la sorgente per la conversione"
type: docs
weight: 1440
url: /it/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Configura la sorgente per la conversione

```csharp
public interface IConversionFrom
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Imposta lo stream del documento sorgente |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Imposta l'array di stream dei documenti sorgente |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Imposta il nome file del documento sorgente |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Imposta l'array di documenti sorgente |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Registra i gestori di eventi del ciclo di vita della conversione su una borsa di [`ConversionEvents`](../../groupdocs.conversion/conversionevents) che vive per tutta la durata del convertitore e si attiva a ogni esecuzione di conversione. Può essere chiamata prima o dopo [`WithSettings`](../iconversionsettings/withsettings). Le chiamate multiple si accumulano: la stessa borsa interna viene passata a ogni azione *configure*, quindi i gestori impostati nelle chiamate precedenti sopravvivono a meno che non vengano sovrascritti da una successiva. |

### IConversionConvertOptions

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
