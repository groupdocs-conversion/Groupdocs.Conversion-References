---
title: "IConversionSettings"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Configura le impostazioni di conversione o gli eventi nella fase di ingresso prima di Load."
type: docs
weight: 1540
url: /it/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Configura le impostazioni di conversione o gli eventi nella fase di ingresso (prima di `Load`).

```csharp
public interface IConversionSettings
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Registra i gestori degli eventi del ciclo di vita della conversione su un sacchetto [`ConversionEvents`](../../groupdocs.conversion/conversionevents) che vive per tutta la durata del convertitore e si attiva ad ogni esecuzione di conversione. Si trova nella stessa fase di ingresso di [`WithSettings`](./withsettings). Le chiamate multiple si accumulano: lo stesso sacchetto interno viene passato a ogni azione *configure*, quindi i gestori impostati nelle chiamate precedenti sopravvivono a meno che non vengano sovrascritti da una successiva. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Imposta le impostazioni del convertitore |

### IConversionConvertOptions

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
