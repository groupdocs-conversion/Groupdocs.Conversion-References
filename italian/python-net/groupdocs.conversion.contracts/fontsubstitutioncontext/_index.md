---
title: "classe FontSubstitutionContext"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Descrive una singola sostituzione del font avvenuta durante il caricamento o il rendering di un documento sorgente."
type: docs
url: /it/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Descrive una singola sostituzione del font avvenuta durante il caricamento o il rendering di un documento sorgente.

Le istanze vengono passate a [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

Il tipo FontSubstitutionContext espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Inizializza un nuovo FontSubstitutionContext. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Il nome del font a cui fa riferimento il documento sorgente ma non è disponibile per la pipeline di conversione. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Il messaggio di sostituzione esattamente come riportato dalla pipeline di conversione, verbatim e non analizzato. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Il nome file del documento sorgente in fase di conversione. Quando la sorgente è stata fornita come stream che non è un `io.RawIOBase`, questo contiene un identificatore generato anziché un vero nome file. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | Il nome del font usato come sostituto. Può essere None per i documenti il cui motore segnala la sostituzione solo come testo descrittivo — in tal caso leggere [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Vedi anche
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
