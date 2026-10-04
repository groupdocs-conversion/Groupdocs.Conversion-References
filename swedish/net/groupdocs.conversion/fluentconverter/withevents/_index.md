---
title: "WithEvents"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Entrystage‑variant av den flytande kedjan som startar med händelsehanterare för konverteringslivscykeln. Sitter på samma ingångssteg som WithSettingsgroupdocs.conversion/fluentconverter/withsettings och den resulterande ConversionEventsgroupdocs.conversion/conversionevents‑påsen avfyras vid varje konverteringskörning av konverteraren."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Variant av ingångsstadiet av den flytande kedjan som startar med händelsehanterare för konverteringslivscykeln. Sitter på samma ingångsstadium som [`WithSettings`](../withsettings), och den resulterande [`ConversionEvents`](../../conversionevents)-påsen avfyras vid varje konverteringskörning av konverteraren.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| konfigurera | Action`1 | Åtgärd som ändrar händelsepåsen. |

### Returvärde

Källvalsstadiet så att `Load` kan kedjas.

### Se även

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
