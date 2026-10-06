---
title: "layout_names egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Layoutnamnen som ska konverteras."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

Layoutnamnen som ska konverteras.

Respekteras inte när man konverterar till PDF/UA-1. Det målet renderar ritningen som en enda taggad sida, vilket inte kan bära ett blad per vald layout, så hela ritningen konverteras istället och inget här gäller för den.

Alla andra mål, inklusive PDF, respekterar urvalet. På dessa mål matchas namn exakt mot de layouter som ritningen har, så ett namn som bara skiljer sig i versaler är ett annat namn. Ett namn som inte matchar något släpps och kostar anroparen endast det bladet; en lista där inget matchar får konverteringen att misslyckas med ett `InvalidLoadOptionsException` som namnger de namn som saknades och de layouter som ritningen faktiskt har, snarare än att rendera blad som anroparen inte begärde. En ritning som inte har några layouter alls är undantagen: det finns inget för ett namn att matcha, så inget avvisas.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Se även
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
