---
title: "layout_scope egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Layout omfånget som bestämmer vilka ritningsutrymmen som konverteras."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

Layoutomfånget som bestämmer vilka ritningsutrymmen som konverteras. Standard är [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), vilket inte begränsar konverteringen. Ignoreras när [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) anges, eftersom explicita layoutnamn alltid har företräde. Ett `None`‑värde behandlas som [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Om omfånget inte väljer någon av de blad som erbjuds av en ritning, misslyckas konverteringen med `InvalidLoadOptionsException`, som namnger omfånget och de tillgängliga bladen istället för att rendera de uteslutna utrymmena. En ritning som inte erbjuder något blad alls påverkas inte och konverteras fortfarande som en enhet. Respekteras inte när man konverterar till PDF/UA-1, av den anledning som ges på [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Se även
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
