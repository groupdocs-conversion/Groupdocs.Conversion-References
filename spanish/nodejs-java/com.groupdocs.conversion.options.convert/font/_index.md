---
title: "Fuente"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Configuración de fuentes"
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/font/
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
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | crea una nueva instancia de Font |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Obtiene el nombre de la familia de fuentes |
| [getSize()](#getSize--) | Obtiene el tamaño de fuente |
| [isBold()](#isBold--) | Indicador de negrita de fuente |
| [setBold(boolean bold)](#setBold-boolean-) | Establece el indicador de negrita de fuente |
| [isItalic()](#isItalic--) | Indicador de cursiva de fuente |
| [setItalic(boolean italic)](#setItalic-boolean-) | Establece el indicador de cursiva de fuente |
| [isUnderline()](#isUnderline--) | Obtiene el subrayado de fuente |
| [setUnderline(boolean underline)](#setUnderline-boolean-) | Establece el subrayado de fuente |
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
| fontFamilyName | java.lang.String | Nombre de fuente |
| tamaño | float | Tamaño de fuente |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtiene el nombre de la familia de fuentes

**Returns:**
java.lang.String - Nombre de familia de fuente
### getSize() {#getSize--}
```
public float getSize()
```


Obtiene el tamaño de fuente

**Returns:**
float - Tamaño de fuente
### isBold() {#isBold--}
```
public boolean isBold()
```


Indicador de negrita de fuente

**Returns:**
boolean - verdadero si es negrita
### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Establece el indicador de negrita de fuente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| negrita | boolean | verdadero si es negrita |

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Indicador de cursiva de fuente

**Returns:**
boolean - verdadero si es cursiva
### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Establece el indicador de cursiva de fuente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cursiva | boolean | verdadero si es cursiva |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Obtiene el subrayado de fuente

**Returns:**
boolean - verdadero si la fuente está subrayada
### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Establece el subrayado de fuente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subrayado | boolean | Indicador de subrayado de fuente |

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
