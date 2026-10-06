---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Typen onder groupdocs.conversion.fluent."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Typen onder `groupdocs.conversion.fluent`.

### Klassen
| Klasse | Beschrijving |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Verwerkt voltooiing van conversiepagina. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Verwerkt voltooiing van conversie of voert conversie uit. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Biedt een vloeiende interface nadat `OnConversionFailed` is ingesteld voor paginaconversie. Staat toe `OnConversionCompleted` in te stellen of door te gaan naar `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Stelt de vloeiende interface voor nadat `OnConversionCompleted` is ingesteld voor paginaconversie, en maakt de configuratie van `OnConversionFailed` of doorgaan naar `Convert`/`Compress` mogelijk. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Biedt een vloeiende interface voor het instellen van alleen per-pagina conversie‑handlers. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Biedt een vloeiende interface voor het instellen van paginaconversie‑handlers. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Stelt een afgevlakte per-pagina conversie‑handlers fase voor. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | De vloeiende interface voor het instellen van per-pagina conversie‑opties of handler‑configuratie. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Verwerkt voltooide conversie. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Verwerk voltooide conversie of voer conversie uit. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Comprimeert alle conversieresultaten in één enkel archief. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Verwerkt voltooide compressie. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Vervolg na `Compress(...)`. Ga direct verder met `Convert`; de geërfde [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) is verouderd — registreer de handler in de instapfase via [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) in plaats daarvan. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Voer conversie uit. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Vertegenwoordigt conversie‑opties. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Vertegenwoordigt conversie‑opties, afhandelingslogica bij voltooiing, of uitvoering voor een conversie. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Vertegenwoordigt conversie‑opties, afhandeling bij voltooiing, of uitvoering. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Vertegenwoordigt conversie‑opties. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Comprimeer of converteer. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Stelt de bron in voor conversie. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Haalt informatie op over het bron‑document, inclusief paginatelling en andere eigenschappen die specifiek zijn voor het bestandstype. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Haalt mogelijke conversies op voor het bron‑document. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Stelt de vloeiende interface voor nadat `OnConversionFailed` is ingesteld, en maakt het mogelijk `OnConversionCompleted` in te stellen of door te gaan naar `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Biedt een vloeiende interface nadat `OnConversionCompleted` is ingesteld, en maakt de configuratie van `OnConversionFailed` of doorgaan naar `Convert`/`Compress` mogelijk. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Biedt een vloeiende interface voor het instellen van alleen conversie‑handlers. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Biedt een vloeiende interface voor het instellen van conversie‑handlers. Staat toe `OnConversionCompleted` en/of `OnConversionFailed` in willekeurige volgorde in te stellen, elk maximaal één keer, of beide over te slaan. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Stelt een afgevlakte conversie‑handlers fase voor. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Controleert of het bron‑document met een wachtwoord is beveiligd. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Stelt opties voor het laden van conversie voor. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Stelt opties voor het laden van conversie of acties met een geladen document voor. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Biedt een vloeiende interface voor het instellen van alleen conversie‑opties. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Stelt conversie‑opties of configuratie van de conversiehandler voor. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Configureer conversie‑instellingen of -gebeurtenissen in de instapfase (voor `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Stelt conversie‑instellingen of conversiebron voor. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Biedt mogelijke acties met een geladen document. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Stelt in hoe het geconverteerde document wordt opgeslagen. |
