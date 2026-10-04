---
title: "GetHashCode"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Dient als de standaard hash-functie."
type: docs
weight: 20
url: /nl/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

Dient als de standaard hash-functie.

```csharp
public override int GetHashCode()
```

### Retourwaarde

Een hashcode voor het huidige object.

### Opmerkingen

Array-, lijst- en dictionary‑componenten worden gehasht op basis van hun inhoud, overeenkomstig hoe gelijkheid ze vergelijkt, zodat twee objecten die gelijk zijn ook gelijk gehasht worden en als sleutels in een dictionary of als leden van een set kunnen worden gebruikt. Dit geldt NIET voor een component die een andere IEnumerable is: zo’n component wordt gehasht op referentie, en één die wordt blootgesteld als een lui iterator levert bij elke toegang een andere waarde, waardoor een object dat het draagt helemaal niet als sleutel bruikbaar is. Geneste collecties worden op dezelfde manier vergeleken en gehasht op referentie in plaats van recursief. Het andere gevolg is dat het muteren van een collectie die een waardobject blootlegt – toevoegen aan een paginalijst, of schrijven in een lay-out‑naam‑array – de hash van dat object wijzigt, zodat een instantie die al in een hash‑container is opgeslagen onbereikbaar wordt. Beschouw een waardobject als bevroren zodra het als sleutel is gebruikt.

### Zie ook

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
