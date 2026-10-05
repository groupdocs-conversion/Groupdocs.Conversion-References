---
title: "Klasse IConversionHandlersStage"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Stellt eine abgeflachte Konvertierungs‑Handler‑Stufe dar."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Stellt eine abgeflachte Konvertierungs‑Handler‑Stufe dar.

Ermöglicht das Festlegen von `OnConversionCompleted` oder `OnConversionFailed` in beliebiger Reihenfolge und beliebig oft, bevor zu `Convert` / `Compress` fortgefahren wird. Ereignisse sollten in der frühen Phase über [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) registriert werden, anstatt in dieser Phase.

Der Typ IConversionHandlersStage stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Komprimiert die Konvertierungsergebnisse. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Führt die Konvertierungskette aus. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Registriert einen Rückruf, der aufgerufen wird, wenn eine Dokumentkonvertierung erfolgreich abgeschlossen ist, und ersetzt bei erneuter Aufrufung jeden zuvor gesetzten Handler. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung fehlschlägt. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Siehe auch
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
