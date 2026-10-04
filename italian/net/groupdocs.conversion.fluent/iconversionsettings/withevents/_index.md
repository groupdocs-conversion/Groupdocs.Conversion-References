---
title: "WithEvents"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Registra i gestori di eventi del ciclo di vita della conversione su un sacchetto ConversionEventsgroupdocs.conversion/conversionevents che vive per la durata del convertitore e si attiva ad ogni esecuzione di conversione. Si colloca allo stesso stadio di ingresso di WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Le chiamate multiple accumulano lo stesso sacchetto interno che viene passato a ogni azione configure, quindi i gestori impostati nelle chiamate precedenti sopravvivono a meno che non vengano sovrascritti da una successiva."
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Registra i gestori di eventi del ciclo di vita della conversione su un sacchetto [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) che vive per la durata del convertitore e si attiva ad ogni esecuzione di conversione. Si colloca allo stesso stadio di ingresso di [`WithSettings`](../withsettings). Le chiamate multiple si accumulano: lo stesso sacchetto interno viene passato a ogni azione *configure*, quindi i gestori impostati nelle chiamate precedenti sopravvivono a meno che non vengano sovrascritti da una successiva.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| configure | Action`1 | Action che muta il sacchetto di eventi. |

### Valore restituito

La fase di selezione della sorgente in modo che `Load` possa essere concatenato.

### IConversionConvertOptions

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
