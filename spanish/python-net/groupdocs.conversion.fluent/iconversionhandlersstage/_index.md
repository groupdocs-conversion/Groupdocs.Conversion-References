---
title: "Clase IConversionHandlersStage"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Representa una etapa aplanada de controladores de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Representa una etapa aplanada de controladores de conversión.

Permite establecer `OnConversionCompleted` o `OnConversionFailed` en cualquier orden y cualquier número de veces, antes de continuar con `Convert` / `Compress`. Los eventos deben registrarse en la etapa temprana mediante [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) en lugar de en esta etapa.

El tipo IConversionHandlersStage expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Comprime los resultados de la conversión. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Ejecuta la cadena de conversión. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Registra una devolución de llamada que se invocará cuando una conversión de documento se complete con éxito, reemplazando cualquier controlador previamente establecido al re‑invocar. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Registra una devolución de llamada que se invocará cuando una conversión de documento falle. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Ver también
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
