---
title: "ConversionEvents"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Agrupa los controladores de eventos del ciclo de vida de la conversión. Pase una instancia a los parámetros de eventos de los constructores Converter./converter o al método fluido WithEvents. Prefiera esto sobre las propiedades de controlador individuales ConverterSettings./convertersettings, que están obsoletas."
type: docs
weight: 850
url: /es/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Agrupa los controladores de eventos del ciclo de vida de la conversión. Pase una instancia al parámetro `events` del constructor de [`Converter`](../converter) o al método fluido `WithEvents`. Prefiera esto sobre las propiedades de controlador individuales de [`ConverterSettings`](../convertersettings), que están obsoletas.

```csharp
public sealed class ConversionEvents
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ConversionEvents](conversionevents)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Se dispara cuando se completa la compresión de la salida de la conversión. Sólo se invoca en compilaciones que incluyen la canalización de compresión (LIB_ZIP). |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Se dispara una vez cuando la ejecución de la conversión finaliza, independientemente del éxito o fracaso. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Se dispara periódicamente con el progreso de la conversión como porcentaje (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Se dispara una vez al inicio de la ejecución de la conversión, antes de que se procese cualquier documento. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Se dispara una vez por cada conversión de documento completo que se completa con éxito. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Se dispara una vez por cada conversión de documento completo que falla. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Se dispara cuando una fuente referenciada por el documento de origen no está disponible y se sustituye (ya sea por una regla [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute) suministrada por el cliente, por la fuente predeterminada configurada, o por la alternativa interna de la canalización de conversión). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Se dispara una vez por página cuando una conversión por página se completa con éxito. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Se dispara una vez por página cuando una conversión por página falla. |

### Ver también

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
