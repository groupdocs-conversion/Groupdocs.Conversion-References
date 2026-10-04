---
title: "LayoutNames"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Specificeert welke CAD-indelingen moeten worden geconverteerd"
type: docs
weight: 70
url: /nl/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Specificeert welke CAD-indelingen moeten worden geconverteerd

```csharp
public string[] LayoutNames { get; set; }
```

### Opmerkingen

Wordt niet gerespecteerd bij het converteren naar PDF/UA-1. Dat doel rendert de tekening als één enkele getagde pagina, die geen blad per geselecteerde lay-out kan bevatten, waardoor de hele tekening in plaats daarvan wordt geconverteerd en hier niets op van toepassing is. Elk ander doel, PDF inbegrepen, respecteert de selectie. Op die doelen worden namen exact vergeleken met de lay-outs die de tekening bevat, dus een naam die alleen in hoofdletters verschilt is een andere naam. Een naam die niets overeenkomt wordt verwijderd en kost de aanroeper alleen dat blad; een lijst waarin niets overeenkomt laat de conversie falen met een [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) die de namen vermeldt die ontbreken en de lay-outs die de tekening wel bevat, in plaats van bladen te renderen die de aanroeper niet heeft gevraagd. Een tekening die helemaal geen lay-outs bevat, is vrijgesteld: er is niets voor een naam om mee te vergelijken, dus geen enkele wordt geweigerd.

### Zie ook

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
