---
title: "TextFragment"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa una parte del texto reconocido, palabra, símbolo, etc., extraído por el motor OCR."
type: docs
weight: 11
url: /es/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Representa una parte del texto reconocido (palabra, símbolo, etc.), extraída por el motor OCR.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Inicializa una nueva instancia del fragmento de texto reconocido. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getText()](#getText--) | Obtiene el contenido textual del fragmento de texto reconocido. |
|
|  | [getRectangle()](#getRectangle--) | Obtiene un rectángulo delimitador del fragmento de texto reconocido. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Inicializa una nueva instancia del fragmento de texto reconocido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | contenido textual del fragmento de texto reconocido |
|
|  | rectángulo | java.awt.Rectangle | rectángulo delimitador del fragmento de texto reconocido |
|

### getText() {#getText--}
```
public String getText()
```


Obtiene el contenido textual del fragmento de texto reconocido.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Obtiene un rectángulo delimitador del fragmento de texto reconocido.


**Returns:**
[Rectangle](../../java.awt/rectangle)
