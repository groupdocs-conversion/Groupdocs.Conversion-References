---
title: "GroupDocs.Conversion.Fluent"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "El espacio de nombres proporciona interfaces para conversión fluida."
type: docs
weight: 60
url: /es/net/groupdocs.conversion.fluent/
---
El espacio de nombres proporciona interfaces para conversión fluida.

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Manejar página de conversión completada |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Manejar la conversión completada o ejecutar la conversión |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Interfaz fluida para establecer solo controladores de conversión por página. Los controladores se registran a través de [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Etapa aplanada de controladores de conversión por página. Espejo por página de [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Interfaz fluida para establecer opciones de conversión por página o configuración de controladores. Permite establecer opciones o controladores en cualquier orden, pero solo una vez cada uno, o omitir ambos. |
| [IConversionCompleted](./iconversioncompleted) | Manejar la conversión completada |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Manejar la conversión completada o ejecutar la conversión |
| [IConversionCompressResult](./iconversioncompressresult) | Puede comprimir todos los resultados de la conversión en un solo archivo |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Continuación después de `Compress(...)`. Continúe con `Convert`; registre el controlador de flujo comprimido en la etapa de entrada mediante [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Ejecutar la conversión |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Opciones de conversión |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Opciones de conversión o conversión completada o ejecutar |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Opciones de conversión o conversión completada o ejecutar |
| [IConversionConvertOptions](./iconversionconvertoptions) | Opciones de conversión |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Comprimir o convertir |
| [IConversionFrom](./iconversionfrom) | Configurar la fuente para la conversión |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Obtiene información del documento fuente: recuento de páginas y otras propiedades del documento específicas del tipo de archivo. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Obtiene conversiones posibles para el documento fuente. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Interfaz fluida para establecer solo controladores de conversión. Los controladores se registran a través de [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Etapa aplanada de controladores de conversión. Permite establecer `OnConversionCompleted` o `OnConversionFailed` en cualquier orden y cualquier número de veces, antes de proceder a `Convert` / `Compress`. Los eventos deben registrarse en la etapa temprana mediante [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) en lugar de en esta etapa. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Comprueba si el documento fuente está protegido con contraseña |
| [IConversionLoadOptions](./iconversionloadoptions) | Opciones de carga de conversión |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Opciones de carga de conversión o acciones con el documento cargado |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Interfaz fluida para establecer solo opciones de conversión. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Opciones de conversión o configuración del controlador de conversión. |
| [IConversionSettings](./iconversionsettings) | Configura la configuración de conversión o eventos en la etapa de entrada (antes de `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Configuración de conversión o fuente de conversión |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Proporciona acciones posibles con el documento cargado |
| [IConversionTo](./iconversionto) | Establece cómo se almacenará el documento convertido |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
