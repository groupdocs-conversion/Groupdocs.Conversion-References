---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "L'espace de noms fournit des interfaces pour la conversion fluide."
type: docs
weight: 60
url: /fr/net/groupdocs.conversion.fluent/
---
L'espace de noms fournit des interfaces pour la conversion fluide.

## Interfaces

| Interface | Description |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Gestion de la page de conversion terminée |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Gérer la conversion terminée ou exécuter la conversion |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Interface fluide pour définir uniquement les gestionnaires de conversion par page. Les gestionnaires sont enregistrés via [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Étape aplatie des gestionnaires de conversion par page. Miroir par page de [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Interface fluide pour définir les options de conversion par page ou la configuration des gestionnaires. Permet de définir les options ou les gestionnaires dans n'importe quel ordre, mais une seule fois chacun, ou d'ignorer les deux. |
| [IConversionCompleted](./iconversioncompleted) | Gérer la conversion terminée |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Gérer la conversion terminée ou exécuter la conversion |
| [IConversionCompressResult](./iconversioncompressresult) | Peut compresser tous les résultats de conversion dans une archive unique |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Continuation après `Compress(...)`. Poursuivre avec `Convert` ; enregistrer le gestionnaire de flux compressé à l'étape d'entrée via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Exécuter la conversion |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Options de conversion |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Options de conversion ou conversion terminée ou exécuter |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Options de conversion ou conversion terminée ou exécuter |
| [IConversionConvertOptions](./iconversionconvertoptions) | Options de conversion |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Compresser ou convertir |
| [IConversionFrom](./iconversionfrom) | Configurer la source pour la conversion |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Obtient les informations du document source - nombre de pages et autres propriétés du document spécifiques au type de fichier. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Obtient les conversions possibles pour le document source. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Interface fluide pour définir uniquement les gestionnaires de conversion. Les gestionnaires sont enregistrés via [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Étape aplatie des gestionnaires de conversion. Permet de définir `OnConversionCompleted` ou `OnConversionFailed` dans n'importe quel ordre et autant de fois que nécessaire, avant de passer à `Convert` / `Compress`. Les événements doivent être enregistrés à un stade précoce via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) plutôt que dans cette étape. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Vérifie si le document source est protégé par mot de passe |
| [IConversionLoadOptions](./iconversionloadoptions) | Options de chargement de la conversion |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Options de chargement de la conversion ou actions avec le document chargé |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Interface fluide pour définir uniquement les options de conversion. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Options de conversion ou configuration du gestionnaire de conversion. |
| [IConversionSettings](./iconversionsettings) | Configurer les paramètres de conversion ou les événements à l'étape d'entrée (avant `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Paramètres de conversion ou source de conversion |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Fournit les actions possibles avec le document chargé |
| [IConversionTo](./iconversionto) | Définir comment le document converti doit être stocké |

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
