---
title: "layout_names eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De lay-outnamen die moeten worden geconverteerd."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

De lay-outnamen die moeten worden geconverteerd.

Niet gerespecteerd bij het converteren naar PDF/UA-1. Dat doel rendert de tekening als één enkele getagde pagina, die geen blad per geselecteerde lay-out kan bevatten, waardoor de hele tekening in plaats daarvan wordt geconverteerd en hier niets op van toepassing is.

Elk ander doel, inclusief PDF, respecteert de selectie. Op die doelen worden namen exact vergeleken met de lay-outs die de tekening bevat, zodat een naam die alleen in hoofdlettergebruik verschilt een andere naam is. Een naam die nergens overeenkomt wordt verwijderd en kost de aanroeper alleen dat blad; een lijst waarin niets overeenkomt laat de conversie falen met een `InvalidLoadOptionsException` die de namen benoemt die missen en de lay-outs die de tekening wel bevat, in plaats van bladen te renderen die de aanroeper niet heeft gevraagd. Een tekening die helemaal geen lay-outs bevat, is vrijgesteld: er is niets voor een naam om te matchen, dus wordt er niets geweigerd.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Zie ook
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
