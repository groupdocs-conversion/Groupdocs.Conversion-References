---
title: "get_possible_conversions Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Ruft mögliche Konvertierungen für das Quell-Dokument ab."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Ruft mögliche Konvertierungen für das Quell-Dokument ab.

Das zurückgegebene Objekt bietet Zugriff auf alle Konvertierungsoptionen, einschließlich primärer und sekundärer Formate, und enthält Metadaten über die Quelldatei.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Beispiel

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Siehe auch
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
