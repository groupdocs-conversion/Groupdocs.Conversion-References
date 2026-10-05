---
title: "PresentationLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos Presentation."
type: docs
weight: 33
url: /es/nodejs-java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Opciones para cargar documentos Presentation.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) | Inicializa una nueva instancia de la clase [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Fuente predeterminada para renderizar la presentación. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Fuente predeterminada para renderizar la presentación. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Sustituir fuentes específicas al convertir un documento de Presentation. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sustituir fuentes específicas al convertir un documento de Presentation. |
| [getPassword()](#getPassword--) | Establecer contraseña para desproteger el documento protegido. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Establecer contraseña para desproteger el documento protegido. |
| [getHideComments()](#getHideComments--) | Ocultar comentarios. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Ocultar comentarios. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Mostrar diapositivas ocultas. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Mostrar diapositivas ocultas. |
| [getSkipExternalResources()](#getSkipExternalResources--) | \\{@inheritDoc\\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \\{@inheritDoc\\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \\{@inheritDoc\\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \\{@inheritDoc\\} |
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
| [getNotesPosition()](#getNotesPosition--) | Representa la forma en que se imprimen los comentarios con la diapositiva. |
| [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | Representa la forma en que se imprimen las notas con la diapositiva. |
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


Inicializa una nueva instancia de la clase [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).

### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


Tipo de archivo del documento de entrada

**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Fuente predeterminada para renderizar la presentación. La siguiente fuente se usará si falta una fuente en la presentación.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Fuente predeterminada para renderizar la presentación. La siguiente fuente se usará si falta una fuente en la presentación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sustituir fuentes específicas al convertir un documento de Presentation.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sustituir fuentes específicas al convertir un documento de Presentation.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Ocultar comentarios.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Ocultar comentarios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Mostrar diapositivas ocultas.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Mostrar diapositivas ocultas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Si es true, todos los recursos externos no se cargarán, con excepción de los recursos en el

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Recursos externos que siempre se cargarán

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getDocumentFontSources() {#getDocumentFontSources--}
```
public List<String> getDocumentFontSources()
```




**Returns:**
java.util.List<java.lang.String>
### setDocumentFontSources(List<String> documentFontSources) {#setDocumentFontSources-java.util.List-java.lang.String--}
```
public void setDocumentFontSources(List<String> documentFontSources)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


Representa la forma en que se imprimen los comentarios con la diapositiva. El valor predeterminado es None.

**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


Representa la forma en que se imprimen las notas con la diapositiva. El valor predeterminado es None.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| notesPosition | [PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition) |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public PresentationCommentsPosition getCommentsPosition()
```




**Returns:**
[PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) - 
### setCommentsPosition(PresentationCommentsPosition commentsPosition) {#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-}
```
public void setCommentsPosition(PresentationCommentsPosition commentsPosition)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

