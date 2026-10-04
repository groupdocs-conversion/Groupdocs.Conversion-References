---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Namnrymden tillhandahåller gränssnitt för flytande konvertering."
type: docs
weight: 60
url: /sv/net/groupdocs.conversion.fluent/
---
Namnrymden tillhandahåller gränssnitt för flytande konvertering.

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Hantera konverteringssida slutförd |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Hantera konvertering slutförd eller utför konvertering |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Fluent-gränssnitt för att endast ställa in per-sida konverteringshanterare. Hanterarna registreras via [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Förenklad per-sida konverteringshanterarstadium. Per-sida spegel av [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Fluent-gränssnitt för att ställa in per-sida konverteringsalternativ eller hanterarinställning. Tillåter att ange alternativ eller hanterare i vilken ordning som helst, men endast en gång vardera, eller hoppa över båda. |
| [IConversionCompleted](./iconversioncompleted) | Hantera konvertering slutförd |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Hantera konvertering slutförd eller utför konvertering |
| [IConversionCompressResult](./iconversioncompressresult) | Kan komprimera alla konverteringsresultat i ett enda arkiv |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Fortsättning efter `Compress(...)`. Fortsätt med `Convert`; registrera komprimerad-ström hanteraren i inträdesstadiet via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Utför konvertering |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Konverteringsalternativ |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Konverteringsalternativ eller konvertering slutförd eller utför |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Konverteringsalternativ eller konvertering slutförd eller utför |
| [IConversionConvertOptions](./iconversionconvertoptions) | Konverteringsalternativ |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Komprimera eller konvertera |
| [IConversionFrom](./iconversionfrom) | Ställ in källa för konvertering |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Hämtar information om källdokumentet – sidantal och andra dokumentegenskaper specifika för filtypen. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Hämtar möjliga konverteringar för källdokumentet. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Fluent-gränssnitt för att endast ställa in konverteringshanterare. Hanterarna registreras via [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Förenklad konverteringshanterarstadium. Tillåter att ställa in `OnConversionCompleted` eller `OnConversionFailed` i vilken ordning som helst och hur många gånger som helst, innan du fortsätter till `Convert` / `Compress`. Händelser bör registreras i ett tidigt stadium via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) istället för i detta stadium. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Kontrollerar om källdokumentet är lösenordsskyddat |
| [IConversionLoadOptions](./iconversionloadoptions) | Laddningsalternativ för konvertering |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Laddningsalternativ för konvertering eller åtgärder med laddat dokument |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Fluent-gränssnitt för att endast ställa in konverteringsalternativ. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Konverteringsalternativ eller konverteringshanterarinställning. |
| [IConversionSettings](./iconversionsettings) | Ställ in konverteringsinställningar eller händelser i inträdesstadiet (innan `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Konverteringsinställningar eller konverteringskälla |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Tillhandahåller möjliga åtgärder med laddat dokument |
| [IConversionTo](./iconversionto) | Ange hur det konverterade dokumentet ska lagras |

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
