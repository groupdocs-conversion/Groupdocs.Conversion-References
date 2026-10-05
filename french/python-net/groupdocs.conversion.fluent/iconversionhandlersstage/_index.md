---
title: "classe IConversionHandlersStage"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Représente une étape aplatie des gestionnaires de conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Représente une étape aplatie des gestionnaires de conversion.

Permet de définir `OnConversionCompleted` ou `OnConversionFailed` dans n’importe quel ordre et un nombre illimité de fois, avant de passer à `Convert` / `Compress`. Les événements doivent être enregistrés à la première étape via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) au lieu de le faire à cette étape.

Le type IConversionHandlersStage expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Compresse les résultats de la conversion. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Exécute la chaîne de conversion. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Enregistre un rappel à invoquer lorsqu’une conversion de document se termine avec succès, remplaçant tout gestionnaire précédemment défini lors d’une ré‑invocation. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Enregistre un rappel à invoquer lorsqu’une conversion de document échoue. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Voir aussi
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
