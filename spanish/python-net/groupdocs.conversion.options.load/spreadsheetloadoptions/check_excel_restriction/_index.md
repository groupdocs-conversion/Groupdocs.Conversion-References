---
title: "propiedad check_excel_restriction"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad determina si se verifican las restricciones de archivos Excel al modificar objetos relacionados con celdas."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

La propiedad determina si se verifican las restricciones de archivos Excel al modificar objetos relacionados con celdas.

Si es true, intentar ingresar una cadena de más de 32 K generará una excepción. Si es false, la cadena de entrada se acepta, lo que permite que el valor completo se exporte a otros formatos como CSV. Sin embargo, guardar el libro de trabajo nuevamente en formato Excel con dichos valores inválidos puede causar errores inesperados.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Ver también
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
