---
title: "classe IConversionCompressResultCompletedOrConvert"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Continuation après Compress(...)."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/
is_root: false
weight: 130
---


## IConversionCompressResultCompletedOrConvert class

Continuation après `Compress(...)`. Passez directement à `Convert` ; l'interface héritée [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) est obsolète — enregistrez le gestionnaire à l'étape d'entrée via [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) à la place.

Le type IConversionCompressResultCompletedOrConvert expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/convert/) | Exécute la chaîne de conversion. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/#compressed_document_stream) | Reçoit un flux de document compressé. Se déclenche uniquement si `Compress(CompressionConvertOptions)` est défini. |
| [on_compression_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed_action/) |  |

### Voir aussi
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
