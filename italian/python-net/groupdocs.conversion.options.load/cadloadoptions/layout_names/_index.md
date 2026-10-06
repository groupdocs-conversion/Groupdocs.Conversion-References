---
title: "proprietà layout_names"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "I nomi del layout da convertire."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

I nomi del layout da convertire.

Non rispettato durante la conversione a PDF/UA-1. Tale destinazione rende il disegno come una singola pagina taggata, che non può contenere un foglio per ogni layout selezionato, quindi l'intero disegno viene convertito invece e nulla qui si applica.

Tutti gli altri target, incluso PDF, rispettano la selezione. Su questi target, i nomi vengono confrontati esattamente con i layout presenti nel disegno, quindi un nome che differisce solo per maiuscole/minuscole è considerato un nome diverso. Un nome che non corrisponde a nulla viene scartato e costa al chiamante solo quel foglio; un elenco in cui nulla corrisponde provoca il fallimento della conversione con un `InvalidLoadOptionsException` che elenca i nomi mancati e i layout che il disegno possiede, anziché rendere i fogli che il chiamante non ha richiesto. Un disegno che non contiene alcun layout è esente: non c'è nulla a cui un nome possa corrispondere, quindi nessuno viene rifiutato.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Vedi anche
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
