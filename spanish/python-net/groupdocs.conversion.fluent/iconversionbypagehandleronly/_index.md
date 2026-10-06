---
title: "Clase IConversionByPageHandlerOnly"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Proporciona una interfaz fluida para establecer solo controladores de conversión por página."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Proporciona una interfaz fluida para establecer solo controladores de conversión por página.

Hereda de [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) para `Convert`/`Compress`; las sobrecargas escalonadas de `OnConversion*` se mantienen mediante la palabra clave `new` para preservar la compatibilidad retroactiva.

El tipo IConversionByPageHandlerOnly expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Comprime los resultados de la conversión; registre un controlador de flujo comprimido en la etapa de entrada mediante [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (estableciendo `OnCompressionCompleted`) en lugar de usar el método de cadena fluida obsoleto. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Ejecuta la cadena de conversión. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Registra una devolución de llamada que se invocará cuando una conversión de página se complete con éxito. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Registra una devolución de llamada que se invocará cuando una conversión de página falle. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Ver también
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
