---
title: "Classe CadDocumentInfo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Contiene i metadati del documento CAD."
type: docs
url: /it/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Contiene i metadati del documento CAD.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Senza espliciti [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) quei fogli sono lo spazio modello, che è sempre plottabile e quindi sempre un foglio, più ogni layout di paper‑space il cui setup di pagina memorizzato ha una larghezza e un’altezza positive, limitato da [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). I nomi di layout espliciti prevalgono invece: i fogli sono allora i nomi forniti dal disegno, corrispondenti ordinalmente, senza che né lo scope né il setup di pagina li filtrino.

Per un DWF viene segnalato il set di pagine pubblicato. Il conteggio inferiore a uno è zero, segnalato quando lo scope richiesto non corrisponde a nessun foglio di un disegno che ne offre uno: i metadati descrivono comunque il disegno, e zero indica che lo scope non seleziona nulla anziché generare un errore per chi ha chiesto cosa contiene il disegno. Una conversione con le stesse opzioni di caricamento fallisce.

Il conteggio non è quindi la dimensione di [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), che elenca ogni configurazione di stampa che il disegno contiene, incluse quelle da cui non può essere pubblicato alcun foglio, e non prevede quante pagine emetterà una determinata conversione.

Il tipo CadDocumentInfo espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | La data di creazione del documento. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Il formato del documento. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | L'altezza del documento CAD. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | I livelli nel documento. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | I layout nel documento. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Il conteggio delle pagine del documento. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | L'enumerabile di tutte le proprietà che possono essere recuperate per le informazioni del documento corrente. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | La dimensione del documento in byte. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | La larghezza del documento CAD. |

### Vedi anche
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
