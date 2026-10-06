---
title: "Classe IConversionHandlersStage"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Rappresenta una fase appiattita di gestori di conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Rappresenta una fase appiattita di gestori di conversione.

Consente di impostare `OnConversionCompleted` o `OnConversionFailed` in qualsiasi ordine e più volte, prima di procedere a `Convert` / `Compress`. Gli eventi dovrebbero essere registrati nella fase iniziale tramite [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) invece di farlo in questa fase.

Il tipo IConversionHandlersStage espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Comprimi i risultati della conversione. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Esegui la catena di conversione. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Registra una callback da invocare quando una conversione di documento termina con successo, sostituendo qualsiasi gestore precedentemente impostato alla reinvocazione. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Registra una callback da invocare quando una conversione di documento fallisce. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Vedi anche
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
