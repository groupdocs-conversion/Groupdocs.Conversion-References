---
title: "Metodo get_possible_conversions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Recupera le conversioni possibili per il documento di origine."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Recupera le conversioni possibili per il documento di origine.

L'oggetto restituito fornisce l'accesso a tutte le opzioni di conversione, inclusi i formati primari e secondari, e include i metadati sul file di origine.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Esempio

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Vedi anche
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
