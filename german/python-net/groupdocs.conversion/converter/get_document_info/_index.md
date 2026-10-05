---
title: "Methode get_document_info"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Ruft Informationen zum Quelldokument ab, einschließlich Seitenzahl und anderer eigenschaftsspezifischer Angaben zum Dateityp."
type: docs
url: /de/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Ruft Informationen zum Quelldokument ab, einschließlich Seitenzahl und anderer eigenschaftsspezifischer Angaben zum Dateityp.

Erfahren Sie mehr über das konvertierte Dokument – Dateityp, Seitenanzahl, Erstellungsdatum und viele weitere format‑spezifische Eigenschaften:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Beispiel

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Siehe auch
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
