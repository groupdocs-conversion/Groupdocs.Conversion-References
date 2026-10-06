---
title: "get_hash_code metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Fungerar som standardhashfunktion."
type: docs
url: /sv/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Fungerar som standardhashfunktion.

Array-, list- och dictionary-komponenter hashas efter deras innehåll, vilket matchar hur likhet jämför dem, så två objekt som jämförs som lika hashas också lika och kan användas som nycklar i dictionary eller som set-medlemmar.

Detta gäller INTE för en komponent som är någon annan `System.Collections.IEnumerable`: en sådan komponent hashas efter referens, och en som exponeras som en lazy iterator ger ett annat värde vid varje åtkomst, så ett objekt som bär den kan inte användas som nyckel alls. Inbäddade samlingar jämförs och hashas på samma sätt efter referens snarare än rekursivt.

Den andra konsekvensen är att förändring av en samling som ett värdeobjekt exponerar – att lägga till i en sidlista eller skriva in i en layout-namn-array – ändrar objektets hash, så en instans som redan lagrats i en hash-behållare blir oåtkomlig. Behandla ett värdeobjekt som fryst när det har använts som nyckel.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Se även
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
