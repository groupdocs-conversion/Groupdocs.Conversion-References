---
title: "Clase ConversionEvents"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Agrupa los controladores de eventos del ciclo de vida de la conversión."
type: docs
url: /es/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Agrupa los controladores de eventos del ciclo de vida de la conversión.

Pase una instancia al parámetro `events` del constructor de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) o al método fluido `WithEvents`.

Prefiera esto sobre las propiedades de controlador individuales de [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), que están obsoletas.

El tipo ConversionEvents expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | El evento que se dispara cuando la compresión de la salida de la conversión se completa. Sólo se invoca en compilaciones que incluyen la canalización de compresión (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | El evento que se dispara una vez cuando la ejecución de la conversión finaliza, independientemente del éxito o del fracaso. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | El progreso de la conversión como un porcentaje (0–100), emitido periódicamente. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | El evento que se dispara una vez al inicio de la ejecución de la conversión, antes de que se procese cualquier documento. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | El evento se dispara una vez por cada conversión de documento completo que se completa con éxito. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | El evento se dispara una vez por cada conversión de documento completo que falla. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | El evento se dispara cuando una fuente referenciada por el documento de origen no está disponible y se sustituye (ya sea por una regla proporcionada por el cliente [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/), por la fuente predeterminada configurada, o por la alternativa interna del pipeline de conversión). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | El evento se dispara una vez por página cuando una conversión por página se completa con éxito. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | El evento se dispara una vez por página cuando una conversión por página falla. |

### Ver también
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
