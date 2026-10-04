---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "De naamruimte biedt interfaces voor vloeiende conversie."
type: docs
weight: 60
url: /nl/net/groupdocs.conversion.fluent/
---
De naamruimte biedt interfaces voor vloeiende conversie.

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Afhandelen van voltooide conversiepagina |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Afhandelen van voltooide conversie of conversie uitvoeren |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Vloeiende interface voor het instellen van alleen per-pagina conversie‑handlers. De handlers worden geregistreerd via [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Vereenvoudigde per-pagina conversie‑handlers fase. Per-pagina spiegel van [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Vloeiende interface voor het instellen van per-pagina conversie‑opties of handler‑configuratie. Staat toe om opties of handlers in willekeurige volgorde in te stellen, maar elk slechts één keer, of beide over te slaan. |
| [IConversionCompleted](./iconversioncompleted) | Afhandelen van voltooide conversie |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Afhandelen van voltooide conversie of conversie uitvoeren |
| [IConversionCompressResult](./iconversioncompressresult) | Kan alle conversieresultaten comprimeren in één enkel archief |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Vervolg na `Compress(...)`. Ga verder met `Convert`; registreer de gecomprimeerde‑stream handler in de instapfase via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Conversie uitvoeren |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Conversie‑opties |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Conversie‑opties of conversie voltooid of uitvoeren |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Conversie‑opties of conversie voltooid of uitvoeren |
| [IConversionConvertOptions](./iconversionconvertoptions) | Conversie‑opties |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Comprimeren of converteren |
| [IConversionFrom](./iconversionfrom) | Bron instellen voor conversie |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Haalt informatie over het bron‑document op – aantal pagina's en andere documenteigenschappen die specifiek zijn voor het bestandstype. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Haalt mogelijke conversies voor het bron‑document op. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Vloeiende interface voor het instellen van alleen conversie‑handlers. De handlers worden geregistreerd via [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Vereenvoudigde conversie‑handlers fase. Staat toe om `OnConversionCompleted` of `OnConversionFailed` in willekeurige volgorde en onbeperkt aantal keren in te stellen, vóór het doorgaan naar `Convert` / `Compress`. Gebeurtenissen moeten in een vroeg stadium worden geregistreerd via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) in plaats van in deze fase. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Controleert of het bron‑document met een wachtwoord is beveiligd |
| [IConversionLoadOptions](./iconversionloadoptions) | Conversie‑laadopties |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Conversie‑laadopties of acties met geladen document |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Vloeiende interface voor het instellen van alleen conversie‑opties. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Conversie‑opties of configuratie van conversie‑handler. |
| [IConversionSettings](./iconversionsettings) | Instellen van conversie‑instellingen of gebeurtenissen in de instapfase (voor `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Conversie‑instellingen of conversie‑bron |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Biedt mogelijke acties met geladen document |
| [IConversionTo](./iconversionto) | Stel in hoe het geconverteerde document moet worden opgeslagen |

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
