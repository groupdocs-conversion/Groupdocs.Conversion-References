---
title: "proprietà check_excel_restriction"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "La proprietà determina se le restrizioni dei file Excel vengono verificate durante la modifica di oggetti correlati alle celle."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

La proprietà determina se le restrizioni dei file Excel vengono verificate durante la modifica di oggetti correlati alle celle.

Se true, tentare di inserire una stringa più lunga di 32 K genererà un'eccezione. Se false, la stringa di input è accettata, consentendo di esportare il valore completo in altri formati come CSV. Tuttavia, salvare la cartella di lavoro nuovamente in formato Excel con valori così non validi può causare errori inaspettati.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Vedi anche
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
