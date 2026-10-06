---
title: "propiedad detect_numbering_with_whitespaces"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad especifica cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto plano."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

La propiedad especifica cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto sin formato. El valor predeterminado es True.

Si esta opción se establece en False, el algoritmo de reconocimiento de listas detecta párrafos de lista cuando los números de lista terminan con un punto, corchete derecho o símbolos de viñeta (como "•", "*", "-" u "o").

Si esta opción se establece en True, los espacios en blanco también se utilizan como delimitadores de números de lista: el algoritmo de reconocimiento de listas para numeración al estilo árabe (p. ej., 1., 1.1.2.) usa tanto espacios en blanco como el símbolo de punto (".").

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Ver también
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
