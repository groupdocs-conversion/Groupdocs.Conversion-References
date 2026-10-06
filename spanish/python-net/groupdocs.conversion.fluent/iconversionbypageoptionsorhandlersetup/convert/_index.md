---
title: "método convert"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Ejecuta la cadena de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Ejecuta la cadena de conversión.

```python
def convert(self):
    ...
```

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # Abrir el documento fuente
    with Converter("./business-plan.docx") as converter:
        # Definir opciones de conversión para la salida PDF
        pdf_options = PdfConvertOptions()
        # Ejecutar la conversión y guardar el resultado
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Ver también
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
