---
title: "proprietà layout_scope"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "L'ambito di layout che determina quali spazi di disegno vengono convertiti."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

L'ambito del layout che determina quali spazi di disegno vengono convertiti. Il valore predefinito è [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), che non limita la conversione. Ignorato quando viene fornito [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/), poiché i nomi di layout espliciti hanno sempre la precedenza. Un valore `None` è trattato come [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Se l'ambito non seleziona nessuno dei fogli offerti da un disegno, la conversione fallisce con `InvalidLoadOptionsException`, che indica l'ambito e i fogli disponibili invece di renderizzare gli spazi esclusi. Un disegno che non offre alcun foglio rimane invariato e si converte comunque come un'unica unità. Non è rispettato quando si converte in PDF/UA-1, per il motivo indicato su [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Vedi anche
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
