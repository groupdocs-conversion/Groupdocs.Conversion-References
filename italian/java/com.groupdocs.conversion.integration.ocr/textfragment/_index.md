---
title: "TextFragment"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta una parte del testo riconosciuto, parola, simbolo, ecc., estratta dal motore OCR."
type: docs
weight: 11
url: /it/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Rappresenta una parte del testo riconosciuto (parola, simbolo, ecc.), estratta dal motore OCR.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Inizializza una nuova istanza del frammento di testo riconosciuto. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getText()](#getText--) | Restituisce il contenuto testuale del frammento di testo riconosciuto. |
|
|  | [getRectangle()](#getRectangle--) | Restituisce un rettangolo di delimitazione del frammento di testo riconosciuto. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Inizializza una nuova istanza del frammento di testo riconosciuto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | contenuto testuale del frammento di testo riconosciuto |
|
|  | rettangolo | java.awt.Rectangle | rettangolo di delimitazione del frammento di testo riconosciuto |
|

### getText() {#getText--}
```
public String getText()
```


Restituisce il contenuto testuale del frammento di testo riconosciuto.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Restituisce un rettangolo di delimitazione del frammento di testo riconosciuto.


**Returns:**
[Rectangle](../../java.awt/rectangle)
