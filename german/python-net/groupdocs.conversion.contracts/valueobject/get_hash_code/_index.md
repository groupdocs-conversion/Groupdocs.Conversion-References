---
title: "get_hash_code Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Dient als Standard-Hashfunktion."
type: docs
url: /de/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Dient als Standard-Hashfunktion.

Array-, Listen- und Dictionary-Komponenten werden anhand ihres Inhalts gehasht, was dem entspricht, wie die Gleichheit sie vergleicht, sodass zwei Objekte, die als gleich gelten, ebenfalls gleich gehasht werden und als Dictionary-Schlüssel oder Set-Elemente verwendet werden können.

Dies gilt NICHT für eine Komponente, die ein anderes `System.Collections.IEnumerable` ist: Eine solche Komponente wird nach Referenz gehasht, und eine, die als Lazy-Iterator bereitgestellt wird, liefert bei jedem Zugriff einen anderen Wert, sodass ein Objekt, das sie trägt, überhaupt nicht als Schlüssel verwendet werden kann. Verschachtelte Sammlungen werden ebenfalls nach Referenz verglichen und gehasht, anstatt rekursiv.

Die andere Konsequenz ist, dass das Ändern einer Sammlung, die ein Value-Object offenlegt – z. B. das Hinzufügen zu einer Seitenliste oder das Schreiben in ein Layout‑Name‑Array – den Hash dieses Objekts ändert, sodass eine bereits in einem Hash‑Container gespeicherte Instanz nicht mehr erreichbar ist. Betrachte ein Value-Object als unveränderlich, sobald es als Schlüssel verwendet wurde.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Siehe auch
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
