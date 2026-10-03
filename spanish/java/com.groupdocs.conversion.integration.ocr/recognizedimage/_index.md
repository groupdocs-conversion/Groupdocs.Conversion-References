---
title: "RecognizedImage"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa texto extraído de una imagen como resultado de su proceso de reconocimiento."
type: docs
weight: 10
url: /es/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Representa el texto extraído de una imagen como resultado de su proceso de reconocimiento.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Inicializa una nueva instancia de la clase, usando un conjunto de líneas reconocidas. |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [EMPTY](#EMPTY) | Imagen reconocida vacía |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getLines()](#getLines--) | Obtiene líneas de texto, con sus fragmentos, reconocidas dentro del documento. |
|
|  | [getText()](#getText--) | Obtiene el equivalente textual del texto estructurado |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Inicializa una nueva instancia de la clase, usando un conjunto de líneas reconocidas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | líneas | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | un IEnumerable (p.ej., una lista o una matriz) de líneas reconocidas |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Imagen reconocida vacía


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Obtiene líneas de texto, con sus fragmentos, reconocidas dentro del documento.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Obtiene el equivalente textual del texto estructurado


**Returns:**
java.lang.String
