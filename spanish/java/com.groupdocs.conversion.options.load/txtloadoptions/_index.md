---
title: "TxtLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de Txt."
type: docs
weight: 34
url: /es/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Opciones para cargar documentos de Txt.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Inicializa una nueva instancia de la clase [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Permite especificar cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto sin formato. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Permite especificar cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto sin formato. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Obtiene o establece la opción preferida para el manejo de espacios finales. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Obtiene o establece la opción preferida para el manejo de espacios finales. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Obtiene o establece la opción preferida para el manejo de espacios iniciales. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Obtiene o establece la opción preferida para el manejo de espacios iniciales. |
|
|  | [getEncoding()](#getEncoding--) | Obtiene o establece la codificación que se utilizará al cargar el documento Txt. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Obtiene o establece la codificación que se utilizará al cargar el documento Txt. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Inicializa una nueva instancia de la clase [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Tipo de archivo del documento de entrada


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Permite especificar cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto sin formato.
El valor predeterminado es true.

<br />

*** ** * ** ***

Si esta opción se establece en false, el algoritmo de reconocimiento de listas detecta los párrafos de lista, cuando los números de lista terminan con
ya sea punto, corchete derecho o símbolos de viñeta (como "\\u2022", "\*", "-" o "o").

Si esta opción se establece en true, los espacios en blanco también se usan como delimitadores de números de lista:
El algoritmo de reconocimiento de listas para numeración al estilo árabe (1., 1.1.2.) utiliza tanto espacios en blanco como símbolos de punto (".").

<br />



**Returns:**
booleano
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Permite especificar cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto sin formato.
El valor predeterminado es true.

<br />

*** ** * ** ***

Si esta opción se establece en false, el algoritmo de reconocimiento de listas detecta los párrafos de lista, cuando los números de lista terminan con
ya sea punto, corchete derecho o símbolos de viñeta (como "\\u2022", "\*", "-" o "o").

Si esta opción se establece en true, los espacios en blanco también se usan como delimitadores de números de lista:
El algoritmo de reconocimiento de listas para numeración al estilo árabe (1., 1.1.2.) utiliza tanto espacios en blanco como símbolos de punto (".").

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Obtiene o establece la opción preferida para el manejo de espacios finales.
El valor predeterminado es [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Obtiene o establece la opción preferida para el manejo de espacios finales.
El valor predeterminado es [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Obtiene o establece la opción preferida para el manejo de espacios iniciales.
El valor predeterminado es [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Obtiene o establece la opción preferida para el manejo de espacios iniciales.
El valor predeterminado es [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Obtiene o establece la codificación que se usará al cargar el documento Txt. Puede ser null. El valor predeterminado es null.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Obtiene o establece la codificación que se usará al cargar el documento Txt. Puede ser null. El valor predeterminado es null.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset |  |

