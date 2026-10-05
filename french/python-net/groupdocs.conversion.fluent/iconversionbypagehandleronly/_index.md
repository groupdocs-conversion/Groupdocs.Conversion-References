---
title: "classe IConversionByPageHandlerOnly"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Fournit une interface fluide pour définir uniquement les gestionnaires de conversion par page."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Fournit une interface fluide pour définir uniquement les gestionnaires de conversion par page.

Hérite de [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) pour `Convert`/`Compress` ; les surcharges `OnConversion*` mises en scène sont conservées via le mot‑clé `new` pour préserver la rétrocompatibilité.

Le type IConversionByPageHandlerOnly expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Compresse les résultats de la conversion ; enregistrez un gestionnaire de flux compressé à l’étape d’entrée via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (en définissant `OnCompressionCompleted`) au lieu d’utiliser la méthode de chaîne fluide obsolète. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Exécute la chaîne de conversion. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Enregistre un rappel à invoquer lorsqu’une conversion de page se termine avec succès. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Enregistre un rappel à invoquer lorsqu’une conversion de page échoue. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Voir aussi
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
