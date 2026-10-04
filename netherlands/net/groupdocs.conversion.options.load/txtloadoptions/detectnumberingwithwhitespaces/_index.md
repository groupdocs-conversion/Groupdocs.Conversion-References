---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer een platte‑tekstdocument wordt geconverteerd. De standaardwaarde is true."
type: docs
weight: 30
url: /nl/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer een platte‑tekstdocument wordt geconverteerd. De standaardwaarde is true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Opmerkingen

Als deze optie is ingesteld op false, detecteert het lijstenherkenningsalgoritme lijstparagrafen wanneer lijstnummers eindigen met een punt, rechte haak of opsommingstekens (zoals "•", "*", "-" of "o").

Als deze optie is ingesteld op true, worden spaties ook gebruikt als scheidingsteken voor lijstnummers: het lijstenherkenningsalgoritme voor Arabische nummering (1., 1.1.2.) gebruikt zowel spaties als punt (".") symbolen.

### Zie ook

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
