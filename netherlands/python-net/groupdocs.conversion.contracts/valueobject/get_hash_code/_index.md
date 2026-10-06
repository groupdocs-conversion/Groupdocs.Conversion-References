---
title: "get_hash_code methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Dient als de standaard hash-functie."
type: docs
url: /nl/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Dient als de standaard hash-functie.

Array-, lijst- en woordenboekcomponenten worden gehasht op basis van hun inhoud, overeenkomstig hoe gelijkheid ze vergelijkt, zodat twee objecten die gelijk worden vergeleken ook gelijk gehasht worden en als sleutels in een woordenboek of als leden van een set kunnen worden gebruikt.

Dit geldt NIET voor een component die een andere `System.Collections.IEnumerable` is: zo'n component wordt gehasht op referentie, en één die wordt blootgesteld als een luie iterator levert bij elke toegang een andere waarde op, waardoor een object dat het draagt helemaal niet als sleutel bruikbaar is. Geneste collecties worden op dezelfde manier vergeleken en gehasht op referentie in plaats van recursief.

Het andere gevolg is dat het muteren van een collectie die een value object blootlegt – toevoegen aan een paginalijst, of schrijven in een layout-naam-array – de hash van dat object wijzigt, zodat een instantie die al in een hashcontainer is opgeslagen onbereikbaar wordt. Beschouw een value object als bevroren zodra het als sleutel is gebruikt.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Zie ook
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
