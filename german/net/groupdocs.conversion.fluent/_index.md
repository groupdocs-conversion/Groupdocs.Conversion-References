---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Der Namespace stellt Schnittstellen für fluente Konvertierung bereit."
type: docs
weight: 60
url: /de/net/groupdocs.conversion.fluent/
---
Der Namespace stellt Schnittstellen für fluente Konvertierung bereit.

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Konvertierungsseite abgeschlossen behandeln |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Verarbeite Abschluss der Konvertierung oder führe die Konvertierung aus |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Flüssige Schnittstelle zum Festlegen ausschließlich von per‑Seite-Konvertierungs‑Handlern. Die Handler werden über [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage) registriert. |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Abgeflachte per‑Seite-Konvertierungs‑Handler‑Stufe. Pro‑Seite‑Spiegel von [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Flüssige Schnittstelle zum Festlegen von per‑Seite-Konvertierungsoptionen oder Handler‑Einrichtung. Ermöglicht das Setzen von Optionen oder Handlern in beliebiger Reihenfolge, jedoch jeweils nur einmal, oder das Überspringen beider. |
| [IConversionCompleted](./iconversioncompleted) | Verarbeite Abschluss der Konvertierung |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Verarbeite Abschluss der Konvertierung oder führe die Konvertierung aus |
| [IConversionCompressResult](./iconversioncompressresult) | Kann alle Konvertierungsergebnisse in einem einzigen Archiv komprimieren |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Fortsetzung nach `Compress(...)`. Fahren Sie mit `Convert` fort; registrieren Sie den komprimierten Stream‑Handler in der Einstiegsebene über [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Führe Konvertierung aus |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Konvertierungsoptionen |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Konvertierungsoptionen oder Abschluss der Konvertierung oder Ausführen |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Konvertierungsoptionen oder Abschluss der Konvertierung oder Ausführen |
| [IConversionConvertOptions](./iconversionconvertoptions) | Konvertierungsoptionen |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Komprimieren oder konvertieren |
| [IConversionFrom](./iconversionfrom) | Quellendatei für die Konvertierung einrichten |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Liefert Informationen zum Quellendokument – Seitenanzahl und weitere dokumentenspezifische Eigenschaften des Dateityps. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Liefert mögliche Konvertierungen für das Quellendokument. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Flüssige Schnittstelle zum Festlegen ausschließlich von Konvertierungs‑Handlern. Die Handler werden über [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage) registriert. |
| [IConversionHandlersStage](./iconversionhandlersstage) | Abgeflachte Konvertierungs‑Handler‑Stufe. Ermöglicht das Setzen von `OnConversionCompleted` oder `OnConversionFailed` in beliebiger Reihenfolge und beliebig oft, bevor zu `Convert` / `Compress` fortgefahren wird. Ereignisse sollten in der frühen Stufe über [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) registriert werden, nicht in dieser Stufe. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Prüft, ob das Quellendokument passwortgeschützt ist |
| [IConversionLoadOptions](./iconversionloadoptions) | Ladeoptionen für die Konvertierung |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Ladeoptionen für die Konvertierung oder Aktionen mit dem geladenen Dokument |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Flüssige Schnittstelle zum Festlegen ausschließlich von Konvertierungsoptionen. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Konvertierungsoptionen oder Einrichtung des Konvertierungs‑Handlers. |
| [IConversionSettings](./iconversionsettings) | Konvertierungseinstellungen oder Ereignisse in der Einstiegsebene einrichten (vor `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Konvertierungseinstellungen oder Konvertierungsquelle |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Stellt mögliche Aktionen mit dem geladenen Dokument bereit |
| [IConversionTo](./iconversionto) | Legen Sie fest, wie das konvertierte Dokument gespeichert werden soll |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
