---
title: "groupdocs.conversion.fluent"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Tipos bajo groupdocs.conversion.fluent."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Tipos bajo `groupdocs.conversion.fluent`.

### Clases
| Clase | Descripción |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Controla la finalización de la página de conversión. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Controla la finalización de la conversión o ejecuta la conversión. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Proporciona una interfaz fluida después de que se establezca `OnConversionFailed` para la conversión de página. Permite establecer `OnConversionCompleted` o continuar con `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Representa la interfaz fluida después de que se establezca `OnConversionCompleted` para la conversión de página, permitiendo la configuración de `OnConversionFailed` o continuar con `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Proporciona una interfaz fluida para establecer solo controladores de conversión por página. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Proporciona una interfaz fluida para establecer controladores de conversión de página. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Representa una etapa aplanada de controladores de conversión por página. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | La interfaz fluida para establecer opciones de conversión por página o la configuración de controladores. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Controla la finalización de la conversión. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Controla la finalización de la conversión o ejecuta la conversión. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Comprime todos los resultados de la conversión en un único archivo. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Controla la finalización de la compresión. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Continuación después de `Compress(...)`. Proceda directamente con `Convert`; el heredado [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) está obsoleto — registre el controlador en la etapa de entrada mediante [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) en su lugar. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Ejecute la conversión. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Representa las opciones de conversión. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Representa opciones de conversión, manejo de finalización o ejecución para una conversión. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Representa opciones de conversión, manejo de finalización o ejecución. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Representa las opciones de conversión. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Comprimir o convertir. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Configura la fuente para la conversión. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Recupera la información del documento de origen, incluido el recuento de páginas y otras propiedades específicas del tipo de archivo. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Obtiene las conversiones posibles para el documento de origen. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Representa la interfaz fluida después de que se establezca `OnConversionFailed`, permitiendo establecer `OnConversionCompleted` o continuar con `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Proporciona una interfaz fluida después de que se establezca `OnConversionCompleted`, permitiendo la configuración de `OnConversionFailed` o continuar con `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Proporciona una interfaz fluida para establecer solo controladores de conversión. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Proporciona una interfaz fluida para establecer controladores de conversión. Permite establecer `OnConversionCompleted` y/o `OnConversionFailed` en cualquier orden, como máximo una vez cada uno, o omitir ambos. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Representa una etapa aplanada de controladores de conversión. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Comprueba si el documento de origen está protegido con contraseña. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Representa opciones de carga de conversión. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Representa opciones de carga de conversión o acciones con un documento cargado. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Proporciona una interfaz fluida para establecer solo opciones de conversión. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Representa opciones de conversión o configuración del manejador de conversión. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Configura la configuración de conversión o eventos en la etapa de entrada (antes de `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Representa la configuración de conversión o la fuente de conversión. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Proporciona acciones posibles con un documento cargado. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Establece cómo se almacena el documento convertido. |
