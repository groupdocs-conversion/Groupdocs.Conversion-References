---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Platt bypage konverteringshanterare steg. Perpage spegel av IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /sv/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Platt by-page konverteringshanterare steg. Per-page spegel av [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Registrerar en återuppringning som ska anropas när en sidkonvertering slutförs framgångsrikt. Återanrop ersätter eventuellt tidigare inställd hanterare. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Registrerar en återuppringning som ska anropas när en sidkonvertering misslyckas. Återanrop ersätter eventuellt tidigare inställd hanterare. |

### Se även

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
