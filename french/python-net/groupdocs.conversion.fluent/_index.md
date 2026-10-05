---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Types sous groupdocs.conversion.fluent."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Types sous `groupdocs.conversion.fluent`.

### Classes
| Classe | Description |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Gère la page de conversion terminée. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Gère l'achèvement de la conversion ou exécute la conversion. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Fournit une interface fluide après que `OnConversionFailed` soit défini pour la conversion de page. Permet de définir `OnConversionCompleted` ou de passer à `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Représente l'interface fluide après que `OnConversionCompleted` soit défini pour la conversion de page, permettant la configuration de `OnConversionFailed` ou le passage à `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Fournit une interface fluide pour définir uniquement les gestionnaires de conversion par page. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Fournit une interface fluide pour définir les gestionnaires de conversion de page. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Représente une étape aplatie des gestionnaires de conversion par page. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | L'interface fluide pour définir les options de conversion par page ou la configuration des gestionnaires. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Gère la conversion terminée. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Gérer la conversion terminée ou exécuter la conversion. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Compresse tous les résultats de conversion dans une archive unique. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Gère la compression terminée. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Continuation après `Compress(...)`. Passez directement à `Convert` ; l'interface héritée [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) est obsolète — enregistrez le gestionnaire à l'étape d'entrée via [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) à la place. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Exécuter la conversion. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Représente les options de conversion. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Représente les options de conversion, la gestion de la fin, ou l'exécution d'une conversion. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Représente les options de conversion, la gestion de la fin, ou l'exécution. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Représente les options de conversion. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Compresser ou convertir. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Configure la source pour la conversion. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Obtient les conversions possibles pour le document source. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Représente l'interface fluide après que `OnConversionFailed` soit défini, permettant de définir `OnConversionCompleted` ou de passer à `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Fournit une interface fluide après que `OnConversionCompleted` soit défini, permettant la configuration de `OnConversionFailed` ou le passage à `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Fournit une interface fluide pour définir uniquement les gestionnaires de conversion. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Fournit une interface fluide pour définir les gestionnaires de conversion. Permet de définir `OnConversionCompleted` et/ou `OnConversionFailed` dans n'importe quel ordre, au plus une fois chacun, ou de les ignorer tous les deux. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Représente une étape aplatie des gestionnaires de conversion. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Vérifie si le document source est protégé par mot de passe. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Représente les options de chargement de conversion. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Représente les options de chargement de conversion ou les actions avec un document chargé. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Fournit une interface fluide pour définir uniquement les options de conversion. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Représente les options de conversion ou la configuration du gestionnaire de conversion. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Configure les paramètres ou les événements de conversion à l'étape d'entrée (avant `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Représente les paramètres de conversion ou la source de conversion. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Fournit les actions possibles avec un document chargé. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Définit comment le document converti est stocké. |
