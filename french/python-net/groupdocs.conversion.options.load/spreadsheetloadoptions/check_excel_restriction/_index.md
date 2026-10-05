---
title: "propriété check_excel_restriction"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "La propriété détermine si les restrictions des fichiers Excel sont vérifiées lors de la modification d’objets liés aux cellules."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

La propriété détermine si les restrictions des fichiers Excel sont vérifiées lors de la modification d’objets liés aux cellules.

Si true, tenter d'entrer une chaîne de caractères de plus de 32 K déclenchera une exception. Si false, la chaîne d'entrée est acceptée, permettant à la valeur complète d'être exportée vers d'autres formats tels que CSV. Cependant, enregistrer le classeur au format Excel avec de telles valeurs invalides peut entraîner des erreurs inattendues.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Voir aussi
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
