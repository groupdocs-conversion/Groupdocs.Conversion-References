---
title: "Fuente"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Configuración de fuentes"
type: docs
weight: 16
url: /es/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Configuración de fuentes

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | crea una nueva instancia de Font |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Obtiene el nombre de la familia de font |
|
|  | [getSize()](#getSize--) | Obtiene el tamaño de font |
|
|  | [isBold()](#isBold--) | Indicador de negrita de Font |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Establece el indicador de negrita de Font |
|
|  | [isItalic()](#isItalic--) | Indicador de cursiva de Font |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Establece la bandera de cursiva de la fuente |
|
|  | [isUnderline()](#isUnderline--) | Obtiene el subrayado de la fuente |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Establece el subrayado de la fuente |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


crea una nueva instancia de Font


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Nombre de la fuente |
|
|  | size | float | Tamaño de la fuente |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtiene el nombre de la familia de font


**Returns:**
java.lang.String - Nombre de la familia de la fuente

### getSize() {#getSize--}
```
public float getSize()
```


Obtiene el tamaño de font


**Returns:**
float - Tamaño de la fuente

### isBold() {#isBold--}
```
public boolean isBold()
```


Indicador de negrita de Font


**Returns:**
boolean - true si es negrita

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Establece el indicador de negrita de Font


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | negrita | booleano | true si es negrita |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Indicador de cursiva de Font


**Returns:**
boolean - true si es cursiva

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Establece la bandera de cursiva de la fuente


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cursiva | booleano | true si es cursiva |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Obtiene el subrayado de la fuente


**Returns:**
boolean - true si la fuente está subrayada

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Establece el subrayado de la fuente


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | subrayado | booleano | Bandera de subrayado de la fuente |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
