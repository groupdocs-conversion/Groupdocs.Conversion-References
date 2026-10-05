---
title: "classe ConversionEvents"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Regroupe les gestionnaires d'événements du cycle de vie de la conversion."
type: docs
url: /fr/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Regroupe les gestionnaires d'événements du cycle de vie de la conversion.

Passez une instance au paramètre `events` du constructeur de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) ou à la méthode fluide `WithEvents`.

Préférez cela aux propriétés de gestionnaire individuelles de [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), qui sont obsolètes.

Le type ConversionEvents expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | L'événement déclenché lorsque la compression de la sortie de conversion se termine. Invoqué uniquement dans les builds qui incluent le pipeline de compression (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | L'événement qui se déclenche une fois lorsque l'exécution de la conversion se termine, quel que soit le succès ou l'échec. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | La progression de la conversion en pourcentage (0–100), déclenchée périodiquement. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | L'événement qui se déclenche une fois au début de l'exécution de la conversion, avant que tout document ne soit traité. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | L'événement est déclenché une fois par conversion de document complet qui se termine avec succès. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | L'événement déclenché une fois par conversion de document complet qui échoue. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | L'événement déclenché lorsqu'une police référencée par le document source n'est pas disponible et est substituée (soit par une règle fournie par le client [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/), soit par la police par défaut configurée, ou par le mécanisme de secours interne du pipeline de conversion). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | L'événement déclenché une fois par page lorsqu'une conversion page par page se termine avec succès. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | L'événement déclenché une fois par page lorsqu'une conversion page par page échoue. |

### Voir aussi
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
