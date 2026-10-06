---
title: "Classe IConversionByPageHandlerOnly"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Fornisce un'interfaccia fluida per impostare solo gestori di conversione per pagina."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Fornisce un'interfaccia fluida per impostare solo gestori di conversione per pagina.

Eredita [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) per `Convert`/`Compress`; le sovraccariche `OnConversion*` a più fasi sono mantenute tramite la parola chiave `new` per preservare la retrocompatibilità.

Il tipo IConversionByPageHandlerOnly espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Comprime i risultati della conversione; registra un gestore di stream compresso nella fase di ingresso tramite [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (impostando `OnCompressionCompleted`) invece di utilizzare il metodo della catena fluida obsoleto. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Esegui la catena di conversione. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Registra una callback da invocare quando una conversione di pagina termina con successo. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Registra una callback da invocare quando una conversione di pagina fallisce. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Vedi anche
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
