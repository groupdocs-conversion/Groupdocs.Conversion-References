---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Typer under groupdocs.conversion.fluent."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Typer under `groupdocs.conversion.fluent`.

### Klasser
| Klass | Beskrivning |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Hantera konverteringssida när den är slutförd. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Hantera konverteringsslutförande eller utför konvertering. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Tillhandahåller ett flytande gränssnitt efter `OnConversionFailed` har satts för sidkonvertering. Tillåter att sätta `OnConversionCompleted` eller gå vidare till `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Representerar det flytande gränssnittet efter att `OnConversionCompleted` har satts för sidkonvertering, vilket möjliggör konfiguration av `OnConversionFailed` eller att gå vidare till `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Tillhandahåller ett flytande gränssnitt för att endast ställa in per-sida konverteringshanterare. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Tillhandahåller ett flytande gränssnitt för att ställa in sidkonverteringshanterare. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Representerar ett plattat steg för per-sida konverteringshanterare. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | Det flytande gränssnittet för att ange per-sida konverteringsalternativ eller ställa in hanterare. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Hantera konvertering slutförd. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Hantera konvertering slutförd eller utför konvertering. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Komprimerar alla konverteringsresultat till ett enda arkiv. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Hantera komprimering slutförd. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Fortsättning efter `Compress(...)`. Fortsätt direkt med `Convert`; den ärvda [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) är föråldrad — registrera hanteraren i startsteget via [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) istället. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Utför konvertering. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Representerar konverteringsalternativ. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Representerar konverteringsalternativ, slutförandehantering eller utförande för en konvertering. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Representerar konverteringsalternativ, slutförandehantering eller utförande. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Representerar konverteringsalternativ. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Komprimera eller konvertera. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Ställer in källan för konvertering. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Hämtar information om källdokumentet, inklusive sidantal och andra egenskaper som är specifika för filtypen. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Hämtar möjliga konverteringar för källdokumentet. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Representerar det flytande gränssnittet efter att `OnConversionFailed` har satts, vilket möjliggör att sätta `OnConversionCompleted` eller gå vidare till `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Tillhandahåller ett flytande gränssnitt efter att `OnConversionCompleted` har satts, vilket möjliggör konfiguration av `OnConversionFailed` eller att gå vidare till `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Tillhandahåller ett flytande gränssnitt för att endast ställa in konverteringshanterare. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Tillhandahåller ett flytande gränssnitt för att ställa in konverteringshanterare. Tillåter att sätta `OnConversionCompleted` och/eller `OnConversionFailed` i vilken ordning som helst, högst en gång vardera, eller att hoppa över båda. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Representerar ett plattat steg för konverteringshanterare. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Kontrollerar om källdokumentet är lösenordsskyddat. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Representerar konverteringsladdningsalternativ. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Representerar konverteringsladdningsalternativ eller åtgärder med ett laddat dokument. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Tillhandahåller ett flytande gränssnitt för att endast ställa in konverteringsalternativ. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Representerar konverteringsalternativ eller inställning av konverteringshanterare. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Ställ in konverteringsinställningar eller händelser i inträdesstadiet (innan `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Representerar konverteringsinställningar eller konverteringskälla. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Tillhandahåller möjliga åtgärder med ett laddat dokument. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Anger hur det konverterade dokumentet lagras. |
