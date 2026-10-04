---
title: "WithEvents"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Variante di fase di ingresso della catena fluente che inizia con i gestori di eventi del ciclo di vita della conversione. Si colloca nella stessa fase di ingresso di WithSettingsgroupdocs.conversion/fluentconverter/withsettings e il contenitore ConversionEventsgroupdocs.conversion/conversionevents risultante si attiva ad ogni esecuzione di conversione del convertitore."
type: docs
weight: 20
url: /it/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Variante di fase di ingresso della catena fluente che inizia con i gestori di eventi del ciclo di vita della conversione. Si colloca nella stessa fase di ingresso di [`WithSettings`](../withsettings) e il contenitore [`ConversionEvents`](../../conversionevents) risultante si attiva ad ogni esecuzione di conversione del convertitore.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| configure | Action`1 | Action che muta il sacchetto di eventi. |

### Valore restituito

La fase di selezione della sorgente in modo che `Load` possa essere concatenato.

### IConversionConvertOptions

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
