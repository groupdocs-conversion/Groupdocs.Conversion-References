---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Registrerar en återuppringning som ska anropas när en sidkonvertering slutförs framgångsrikt. Vid återanrop ersätts tidigare inställd hanterare."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

Registrerar en återuppringning som ska anropas när en sidkonvertering slutförs framgångsrikt. Återanrop ersätter eventuellt tidigare inställd hanterare.

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| onCompleted | Action`1 | En åtgärd för att hantera slutförandet, som tar emot den konverterade sidans kontext. |

### Returvärde

Detta steg, så att ytterligare hanterare eller `Convert` / `Compress` kan kedjas.

### Se även

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
