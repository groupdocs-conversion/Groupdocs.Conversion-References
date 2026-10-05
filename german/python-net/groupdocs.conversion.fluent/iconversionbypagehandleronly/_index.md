---
title: "Klasse IConversionByPageHandlerOnly"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Stellt eine fluent API bereit, um ausschließlich per‑Seite-Konvertierungs‑Handler festzulegen."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Stellt eine fluent API bereit, um ausschließlich per‑Seite-Konvertierungs‑Handler festzulegen.

Erbt [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) für `Convert`/`Compress`; die gestaffelten `OnConversion*`-Überladungen werden über das Schlüsselwort `new` beibehalten, um die Rückwärtskompatibilität zu wahren.

Der Typ IConversionByPageHandlerOnly stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Komprimiert die Konvertierungsergebnisse; registrieren Sie einen komprimierten‑Stream‑Handler in der Einstiegsebene über [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (Einstellung `OnCompressionCompleted`) anstatt die veraltete fluente Kettenmethode zu verwenden. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Führt die Konvertierungskette aus. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung erfolgreich abgeschlossen wird. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung fehlschlägt. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Siehe auch
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
