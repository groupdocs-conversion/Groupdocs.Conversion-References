---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Typen unter groupdocs.conversion.fluent."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Typen unter `groupdocs.conversion.fluent`.

### Klassen
| Klasse | Beschreibung |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Verarbeitet die abgeschlossene Konvertierungsseite. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Verarbeitet den Abschluss der Konvertierung oder führt die Konvertierung aus. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Stellt eine fluent API bereit, nachdem `OnConversionFailed` für die Seitenkonvertierung festgelegt wurde. Ermöglicht das Festlegen von `OnConversionCompleted` oder das Fortfahren zu `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Stellt die fluent API dar, nachdem `OnConversionCompleted` für die Seitenkonvertierung festgelegt wurde, und ermöglicht die Konfiguration von `OnConversionFailed` oder das Fortfahren zu `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Stellt eine fluent API bereit, um ausschließlich per‑Seite-Konvertierungs‑Handler festzulegen. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Stellt eine fluent API bereit, um Seitenkonvertierungs‑Handler festzulegen. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Stellt eine abgeflachte per‑Seite-Konvertierungs‑Handler‑Stufe dar. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | Die fluent API zum Festlegen von per‑Seite-Konvertierungsoptionen oder zur Einrichtung von Handlern. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Verarbeitet den Abschluss der Konvertierung. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Verarbeite den Abschluss der Konvertierung oder führe die Konvertierung aus. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Komprimiert alle Konvertierungsergebnisse in ein einzelnes Archiv. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Verarbeitet den Abschluss der Komprimierung. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Fortsetzung nach `Compress(...)`. Fahren Sie direkt mit `Convert` fort; das geerbte [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) ist veraltet — registrieren Sie den Handler stattdessen in der Einstiegsebene über [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/). |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Führe die Konvertierung aus. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Stellt Konvertierungsoptionen dar. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Stellt Konvertierungsoptionen, Abschlussbehandlung oder Ausführung für eine Konvertierung dar. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Stellt Konvertierungsoptionen, Abschlussbehandlung oder Ausführung dar. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Stellt Konvertierungsoptionen dar. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Komprimieren oder konvertieren. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Richtet die Quelle für die Konvertierung ein. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Ruft Informationen zum Quelldokument ab, einschließlich Seitenzahl und anderer eigenschaftsspezifischer Details des Dateityps. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Ermittelt mögliche Konvertierungen für das Quelldokument. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Stellt die fluent API dar, nachdem `OnConversionFailed` festgelegt wurde, und ermöglicht das Festlegen von `OnConversionCompleted` oder das Fortfahren zu `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Stellt eine fluent API bereit, nachdem `OnConversionCompleted` festgelegt wurde, und ermöglicht die Konfiguration von `OnConversionFailed` oder das Fortfahren zu `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Stellt eine fluent API bereit, um ausschließlich Konvertierungs‑Handler festzulegen. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Stellt eine fluent API bereit, um Konvertierungs‑Handler festzulegen. Ermöglicht das Festlegen von `OnConversionCompleted` und/oder `OnConversionFailed` in beliebiger Reihenfolge, jeweils höchstens einmal, oder das Überspringen beider. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Stellt eine abgeflachte Konvertierungs‑Handler‑Stufe dar. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Prüft, ob das Quelldokument passwortgeschützt ist. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Stellt Konvertierungs‑Ladeoptionen dar. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Stellt Konvertierungs‑Ladeoptionen oder Aktionen mit einem geladenen Dokument dar. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Bietet eine fluente Schnittstelle zum Festlegen ausschließlich von Konvertierungsoptionen. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Stellt Konvertierungsoptionen oder die Einrichtung des Konvertierungs‑Handlers dar. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Richten Sie Konvertierungseinstellungen oder -ereignisse in der Eintrittsphase ein (vor `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Stellt Konvertierungseinstellungen oder die Konvertierungsquelle dar. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Bietet mögliche Aktionen mit geladenem Dokument. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Legt fest, wie das konvertierte Dokument gespeichert wird. |
