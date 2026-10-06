---
title: "classe ConversionEvents"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Aggrega i gestori di eventi del ciclo di vita della conversione."
type: docs
url: /it/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Aggrega i gestori di eventi del ciclo di vita della conversione.

Passa un'istanza al parametro `events` del costruttore di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) o al metodo fluente `WithEvents`.

Preferisci questo rispetto alle singole proprietà handler di [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) che sono obsolete.

Il tipo ConversionEvents espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | L'evento che viene generato quando la compressione dell'output della conversione è completata. Invocato solo nelle build che includono la pipeline di compressione (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | L'evento che si attiva una volta quando l'esecuzione della conversione termina, indipendentemente dal successo o dal fallimento. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | Il progresso della conversione in percentuale (0–100), generato periodicamente. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | L'evento che viene generato una volta all'inizio dell'esecuzione della conversione, prima che venga elaborato qualsiasi documento. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | L'evento viene generato una volta per ogni conversione dell'intero documento che si completa con successo. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | L'evento viene generato una volta per ogni conversione dell'intero documento che fallisce. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | L'evento viene generato quando un carattere (font) referenziato dal documento sorgente non è disponibile e viene sostituito (sia tramite una regola [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) fornita dal cliente, dal carattere predefinito configurato, o dal fallback interno della pipeline di conversione). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | L'evento viene generato una volta per pagina quando una conversione per pagina si completa con successo. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | L'evento viene generato una volta per pagina quando una conversione per pagina fallisce. |

### Vedi anche
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
