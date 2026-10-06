---
title: "check_excel_restriction-eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De eigenschap bepaalt of Excel‑bestandbeperkingen worden gecontroleerd bij het wijzigen van celgerelateerde objecten."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

De eigenschap bepaalt of Excel‑bestandbeperkingen worden gecontroleerd bij het wijzigen van celgerelateerde objecten.

Indien true, zal een poging om een tekenreeks langer dan 32 K in te voeren een uitzondering veroorzaken. Indien false wordt de tekenreeks geaccepteerd, waardoor de volledige waarde kan worden uitgegeven naar andere formaten zoals CSV. Het opslaan van de werkmap terug naar Excel-formaat met dergelijke ongeldige waarden kan echter onverwachte fouten veroorzaken.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Zie ook
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
