---
title: "Classe FontTransformation"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Descrive la configurazione della trasformazione del font, inclusi gli attributi del font, applicata dopo il caricamento del documento e la sostituzione del font."
type: docs
url: /it/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Descrive la configurazione della trasformazione del font, inclusi gli attributi del font, applicata dopo il caricamento del documento e la sostituzione del font.

Il tipo FontTransformation espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Crea una trasformazione di carattere con corrispondenza esatta del carattere (dimensione e stile devono corrispondere). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Crea una trasformazione di carattere solo per nome, corrispondendo a qualsiasi dimensione e stile, con il carattere di sostituzione che preserva la dimensione e lo stile del carattere originale. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Crea una trasformazione di carattere con opzioni di corrispondenza flessibili. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina se due istanze di oggetti sono uguali. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Funge da funzione hash predefinita. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | La proprietà indica se qualsiasi dimensione del carattere per il nome del carattere originale è corrispondente (true) o solo la dimensione esatta del carattere specificata in `OriginalFont` è corrispondente (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | La proprietà determina se qualsiasi stile del carattere (grassetto, corsivo, sottolineato) del carattere originale è corrispondente (True) o se è richiesto lo stile esatto del carattere specificato in `OriginalFont` (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | La specifica del carattere originale da corrispondere e sostituire. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | La specifica del carattere di sostituzione. |

### Vedi anche
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
