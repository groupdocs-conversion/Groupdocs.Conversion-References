---
title: "SpreadsheetConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para la conversión al tipo de archivo Spreadsheet."
type: docs
weight: 40
url: /es/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Opciones para la conversión al tipo de archivo Spreadsheet.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Inicializa una nueva instancia de la clase [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establezca esta propiedad si desea proteger el documento convertido con una contraseña. |
|
|  | [getZoom()](#getZoom--) | Especifica el nivel de zoom en porcentaje. |
|
|  | [setZoom(int value)](#setZoom-int-) | Especifica el nivel de zoom en porcentaje. |
|
|  | [getSeparator()](#getSeparator--) | Especifica el separador que se usará al convertir a formatos delimitados |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Inicializa una nueva instancia de la clase [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Establezca esta propiedad si desea proteger el documento convertido con una contraseña.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establezca esta propiedad si desea proteger el documento convertido con una contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Especifica el separador que se usará al convertir a formatos delimitados


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separador | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


El tipo de archivo deseado al que debe convertirse el documento de entrada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

