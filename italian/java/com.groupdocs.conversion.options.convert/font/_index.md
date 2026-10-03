---
title: "Font"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Impostazioni del carattere"
type: docs
weight: 16
url: /it/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Impostazioni del carattere

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | crea una nuova istanza di Font |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Recupera il nome della famiglia del font |
|
|  | [getSize()](#getSize--) | Ottiene la dimensione del font |
|
|  | [isBold()](#isBold--) | Flag grassetto del Font |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Imposta il flag grassetto del Font |
|
|  | [isItalic()](#isItalic--) | Flag corsivo del Font |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Imposta il flag corsivo del font |
|
|  | [isUnderline()](#isUnderline--) | Ottiene la sottolineatura del font |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Imposta la sottolineatura del font |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


crea una nuova istanza di Font


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Nome del font |
|
|  | dimensione | float | Dimensione del font |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Recupera il nome della famiglia del font


**Returns:**
java.lang.String - Nome della famiglia del font

### getSize() {#getSize--}
```
public float getSize()
```


Ottiene la dimensione del font


**Returns:**
float - Dimensione del font

### isBold() {#isBold--}
```
public boolean isBold()
```


Flag grassetto del Font


**Returns:**
boolean - vero se in grassetto

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Imposta il flag grassetto del Font


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | grassetto | booleano | vero se in grassetto |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Flag corsivo del Font


**Returns:**
boolean - vero se corsivo

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Imposta il flag corsivo del font


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | corsivo | booleano | vero se corsivo |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Ottiene la sottolineatura del font


**Returns:**
boolean - vero se il Font è sottolineato

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Imposta la sottolineatura del font


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | sottolineatura | booleano | Flag della sottolineatura del font |
|

### getDefault() {#getDefault--}
```
public static Font getDefault()
```




**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
### clone(float newSize) {#clone-float-}
```
public Font clone(float newSize)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
