---
title: "groupdocs.conversion.fluent"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Tipi sotto groupdocs.conversion.fluent."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Tipi sotto `groupdocs.conversion.fluent`.

### Classi
| Classe | Descrizione |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Gestisce il completamento della pagina di conversione. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Gestisce il completamento della conversione o esegue la conversione. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Fornisce un'interfaccia fluida dopo che `OnConversionFailed` è impostato per la conversione della pagina. Consente di impostare `OnConversionCompleted` o di procedere a `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Rappresenta l'interfaccia fluida dopo che `OnConversionCompleted` è impostato per la conversione della pagina, consentendo la configurazione di `OnConversionFailed` o procedendo a `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Fornisce un'interfaccia fluida per impostare solo gestori di conversione per pagina. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Fornisce un'interfaccia fluida per impostare i gestori di conversione della pagina. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Rappresenta una fase appiattita di gestori di conversione per pagina. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | L'interfaccia fluida per impostare le opzioni di conversione per pagina o la configurazione del gestore. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Gestisce la conversione completata. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Gestisci la conversione completata o esegui la conversione. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Comprimi tutti i risultati della conversione in un unico archivio. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Gestisce la compressione completata. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Continuazione dopo `Compress(...)`. Procedi direttamente con `Convert`; l'interfaccia ereditata [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) è obsoleta — registra il gestore nella fase di ingresso tramite [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) invece. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Esegui la conversione. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Rappresenta le opzioni di conversione. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Rappresenta le opzioni di conversione, la gestione del completamento o l'esecuzione di una conversione. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Rappresenta le opzioni di conversione, la gestione del completamento o l'esecuzione. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Rappresenta le opzioni di conversione. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Comprimi o converti. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Imposta la sorgente per la conversione. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Recupera le informazioni del documento sorgente, inclusi il conteggio delle pagine e altre proprietà specifiche del tipo di file. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Ottiene le conversioni possibili per il documento sorgente. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Rappresenta l'interfaccia fluida dopo che `OnConversionFailed` è impostato, consentendo di impostare `OnConversionCompleted` o procedere a `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Fornisce un'interfaccia fluida dopo che `OnConversionCompleted` è impostato, consentendo la configurazione di `OnConversionFailed` o procedendo a `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Fornisce un'interfaccia fluida per impostare solo i gestori di conversione. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Fornisce un'interfaccia fluida per impostare i gestori di conversione. Consente di impostare `OnConversionCompleted` e/o `OnConversionFailed` in qualsiasi ordine, al massimo una volta ciascuno, o di saltarli entrambi. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Rappresenta una fase appiattita di gestori di conversione. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Verifica se il documento sorgente è protetto da password. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Rappresenta le opzioni di caricamento della conversione. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Rappresenta le opzioni di caricamento della conversione o le azioni con un documento caricato. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Fornisce un'interfaccia fluida per impostare solo le opzioni di conversione. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Rappresenta le opzioni di conversione o la configurazione del gestore di conversione. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Configura le impostazioni di conversione o gli eventi nella fase di ingresso (prima di `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Rappresenta le impostazioni di conversione o la sorgente di conversione. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Fornisce le possibili azioni con il documento caricato. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Imposta come viene memorizzato il documento convertito. |
