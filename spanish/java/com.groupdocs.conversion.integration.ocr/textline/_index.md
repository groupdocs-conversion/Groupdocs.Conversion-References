---
title: "TextLine"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa texto extraído de una imagen como resultado de su proceso de reconocimiento."
type: docs
weight: 12
url: /es/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Representa el texto extraído de una imagen como resultado de su proceso de reconocimiento.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Inicializa una nueva instancia de una línea de texto, extraída por el motor OCR de una imagen. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFragments()](#getFragments--) | Obtiene una matriz de fragmentos de texto, como símbolos y palabras, reconocidos en la línea. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Inicializa una nueva instancia de una línea de texto, extraída por el motor OCR de una imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fragmentos | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | conjunto inicial de fragmentos de texto |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Obtiene una matriz de fragmentos de texto, como símbolos y palabras, reconocidos en la línea.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
