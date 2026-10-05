---
title: "PdfLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos Pdf."
type: docs
weight: 31
url: /es/nodejs-java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfLoadOptions extends LoadOptions implements Serializable
```

Opciones para cargar documentos Pdf.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Inicializa una nueva instancia de la clase [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Eliminar archivos incrustados. |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Eliminar archivos incrustados. |
| [getPassword()](#getPassword--) | Establecer contraseña para desproteger el documento protegido. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Establecer contraseña para desproteger el documento protegido. |
| [getDefaultFont()](#getDefaultFont--) | Fuente predeterminada para documento Pdf. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Fuente predeterminada para documento Pdf. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Sustituir fuentes específicas al convertir documento Pdf. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sustituir fuentes específicas al convertir documento Pdf. |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Ocultar anotaciones en documentos Pdf. |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Ocultar anotaciones en documentos Pdf. |
| [getFlattenAllFields()](#getFlattenAllFields--) | Aplanar todos los campos del formulario PDF. |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Aplanar todos los campos del formulario PDF. |
| [getResetFontFolders()](#getResetFontFolders--) | Restablecer carpetas de fuentes antes de cargar el documento |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
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
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Eliminar archivos incrustados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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


Fuente predeterminada para documento Pdf. La siguiente fuente se usará si falta una fuente.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Fuente predeterminada para documento Pdf. La siguiente fuente se usará si falta una fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sustituir fuentes específicas al convertir documento Pdf.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sustituir fuentes específicas al convertir documento Pdf.

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
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Ocultar anotaciones en documentos Pdf.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Aplanar todos los campos del formulario PDF.

**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Aplanar todos los campos del formulario PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Restablecer carpetas de fuentes antes de cargar el documento

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resetFontFolders | boolean |  |

