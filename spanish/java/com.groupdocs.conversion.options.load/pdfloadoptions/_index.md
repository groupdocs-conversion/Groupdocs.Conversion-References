---
title: "PdfLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de PDF."
type: docs
weight: 27
url: /es/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Opciones para cargar documentos de PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Inicializa una nueva instancia de la clase [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Eliminar archivos incrustados. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Eliminar archivos incrustados. |
|
|  | [getPassword()](#getPassword--) | Establecer contraseña para desproteger el documento protegido. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establecer contraseña para desproteger el documento protegido. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Fuente predeterminada para el documento Pdf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Fuente predeterminada para el documento Pdf. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sustituir fuentes específicas al convertir el documento Pdf. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sustituir fuentes específicas al convertir el documento Pdf. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Ocultar anotaciones en documentos Pdf. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Ocultar anotaciones en documentos Pdf. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Aplanar todos los campos del formulario PDF. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Aplanar todos los campos del formulario PDF. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Restablecer carpetas de fuentes antes de cargar el documento. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Habilitar o deshabilitar la generación de numeración de páginas en el documento convertido. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Obtiene la bandera Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Establece la bandera Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Especifica si el documento propietario debe convertirse. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Especifica si el documento propietario debe convertirse. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Especifica si los documentos dependientes deben convertirse. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Especifica si los documentos dependientes deben convertirse. |
|
|  | [getDepth()](#getDepth--) | Profundidad máxima para procesar documentos dependientes. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Profundidad máxima para procesar documentos dependientes. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Inicializa una nueva instancia de la clase [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Tipo de archivo del documento de entrada


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Eliminar archivos incrustados.


**Returns:**
booleano
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Eliminar archivos incrustados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Establecer contraseña para desproteger el documento protegido.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establecer contraseña para desproteger el documento protegido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Fuente predeterminada para el documento Pdf.
Se utilizará la siguiente fuente si falta una fuente.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Fuente predeterminada para el documento Pdf.
Se utilizará la siguiente fuente si falta una fuente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sustituir fuentes específicas al convertir el documento Pdf.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sustituir fuentes específicas al convertir el documento Pdf.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Ocultar anotaciones en documentos Pdf.


**Returns:**
booleano
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Ocultar anotaciones en documentos Pdf.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Aplanar todos los campos del formulario PDF.


**Returns:**
booleano
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Aplanar todos los campos del formulario PDF.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Restablecer carpetas de fuentes antes de cargar el documento.


**Returns:**
booleano
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resetFontFolders | booleano |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Habilitar o deshabilitar la generación de numeración de páginas en el documento convertido. Predeterminado: false.


**Returns:**
booleano
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isPageNumbering | booleano |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Obtiene la bandera Remove JavaScript.


**Returns:**
booleano
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Establece la bandera Remove JavaScript.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeJavascript | booleano |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Especifica si el documento propietario debe convertirse.

El valor predeterminado es
true
.


**Returns:**
booleano
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Especifica si el documento propietario debe convertirse.

El valor predeterminado es
true
.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwner | booleano |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Especifica si los documentos dependientes deben convertirse.

El valor predeterminado es
false
.


**Returns:**
booleano
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Especifica si los documentos dependientes deben convertirse.

El valor predeterminado es
false
.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwned | booleano |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Profundidad máxima para procesar documentos dependientes.

El valor predeterminado es
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Profundidad máxima para procesar documentos dependientes.

El valor predeterminado es
2
.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| depth | int |  |

