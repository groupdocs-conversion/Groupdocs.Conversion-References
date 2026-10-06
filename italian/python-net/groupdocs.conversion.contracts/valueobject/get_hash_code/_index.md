---
title: "metodo get_hash_code"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Funziona come funzione hash predefinita."
type: docs
url: /it/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Funziona come funzione hash predefinita.

I componenti di array, liste e dizionari sono hashati in base al loro contenuto, corrispondendo al modo in cui l'uguaglianza li confronta, così due oggetti che risultano uguali vengono hashati allo stesso modo e possono essere usati come chiavi di dizionario o membri di un set.

Questo NON si estende a un componente che è qualche altro `System.Collections.IEnumerable`: tale componente è hashato per riferimento, e uno esposto come iteratore pigro restituisce un valore diverso ad ogni accesso, quindi un oggetto che lo contiene non è affatto utilizzabile come chiave. Le collezioni nidificate sono analogamente confrontate e hashate per riferimento anziché ricorsivamente.

L'altra conseguenza è che modificare una collezione a cui un value object espone – aggiungere a una lista di pagine o scrivere in un array di nomi di layout – cambia l'hash di quell'oggetto, quindi un'istanza già memorizzata in un contenitore hash diventa inaccessibile. Tratta un value object come congelato una volta che è stato usato come chiave.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Vedi anche
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
