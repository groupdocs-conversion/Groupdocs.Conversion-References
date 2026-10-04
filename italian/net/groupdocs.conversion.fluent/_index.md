---
title: "GroupDocs.Conversion.Fluent"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Lo spazio dei nomi fornisce interfacce per la conversione fluida."
type: docs
weight: 60
url: /it/net/groupdocs.conversion.fluent/
---
Lo spazio dei nomi fornisce interfacce per la conversione fluida.

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Gestione della pagina di conversione completata |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Gestisci la conversione completata o esegui la conversione |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Interfaccia fluente per impostare solo i gestori di conversione per pagina. I gestori sono registrati tramite [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Fase appiattita dei gestori di conversione per pagina. Specchio per pagina di [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Interfaccia fluente per impostare le opzioni di conversione per pagina o la configurazione del gestore. Consente di impostare opzioni o gestori in qualsiasi ordine, ma solo una volta ciascuno, o di saltare entrambi. |
| [IConversionCompleted](./iconversioncompleted) | Gestisci la conversione completata |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Gestisci la conversione completata o esegui la conversione |
| [IConversionCompressResult](./iconversioncompressresult) | Può comprimere tutti i risultati della conversione in un unico archivio |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Continuazione dopo `Compress(...)`. Prosegui con `Convert`; registra il gestore del flusso compresso nella fase di ingresso tramite [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Esegui la conversione |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Opzioni di conversione |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Opzioni di conversione o conversione completata o esegui |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Opzioni di conversione o conversione completata o esegui |
| [IConversionConvertOptions](./iconversionconvertoptions) | Opzioni di conversione |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Comprimi o converti |
| [IConversionFrom](./iconversionfrom) | Configura la sorgente per la conversione |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Ottiene le informazioni del documento sorgente - conteggio delle pagine e altre proprietà del documento specifiche del tipo di file. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Ottiene le conversioni possibili per il documento sorgente. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Interfaccia fluente per impostare solo i gestori di conversione. I gestori sono registrati tramite [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Fase appiattita dei gestori di conversione. Consente di impostare `OnConversionCompleted` o `OnConversionFailed` in qualsiasi ordine e più volte, prima di procedere a `Convert` / `Compress`. Gli eventi dovrebbero essere registrati nella fase iniziale tramite [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) invece di questa fase. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Verifica se il documento sorgente è protetto da password |
| [IConversionLoadOptions](./iconversionloadoptions) | Opzioni di caricamento della conversione |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Opzioni di caricamento della conversione o azioni con il documento caricato |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Interfaccia fluente per impostare solo le opzioni di conversione. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Opzioni di conversione o configurazione del gestore di conversione. |
| [IConversionSettings](./iconversionsettings) | Configura le impostazioni di conversione o gli eventi nella fase di ingresso (prima di `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Impostazioni di conversione o sorgente della conversione |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Fornisce le azioni possibili con il documento caricato |
| [IConversionTo](./iconversionto) | Imposta come deve essere archiviato il documento convertito |

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
