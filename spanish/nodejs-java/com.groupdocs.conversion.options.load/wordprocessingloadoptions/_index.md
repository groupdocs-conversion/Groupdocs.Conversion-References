---
title: "WordProcessingLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos WordProcessing."
type: docs
weight: 44
url: /es/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Opciones para cargar documentos WordProcessing.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Inicializa una nueva instancia de la clase [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Fuente predeterminada para documentos de Word. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Fuente predeterminada para documentos de Word. |
| [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa DefaultFont para la sustitución de fuentes faltantes. |
| [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa DefaultFont para la sustitución de fuentes faltantes. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Sustituir fuentes específicas al convertir documentos de Word. |
| [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Si EmbedTrueTypeFonts es verdadero, GroupDocs.Conversion incrusta fuentes TrueType en el documento de salida. |
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
| [isUpdatePageLayout()](#isUpdatePageLayout--) | Actualizar el diseño de página después de cargar. |
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
| [isUpdateFields()](#isUpdateFields--) | Actualizar los campos después de cargar. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
| [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Mantener el valor original del campo de fecha. |
| [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Establece mantener el valor original del campo de fecha. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sustituir fuentes específicas al convertir documentos de Word. |
| [getPassword()](#getPassword--) | Establecer contraseña para desproteger el documento protegido. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Establecer contraseña para desproteger el documento protegido. |
| [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Ocultar marcas y seguimiento de cambios para documentos de Word. |
| [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Ocultar marcas y seguimiento de cambios para documentos de Word. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Ocultar comentarios. |
| [getBookmarkOptions()](#getBookmarkOptions--) | Opciones de marcadores |
| [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Opciones de marcadores |
| [isPreserveFontFields()](#isPreserveFontFields--) | Especifica si se deben conservar los campos de formulario de Microsoft Word como campos de formulario en PDF o convertirlos a texto. |
| [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Establece la bandera preserveFontFields |
| [isUseTextShaper()](#isUseTextShaper--) | Especifica si se debe usar un modelador de texto para una mejor visualización del kerning. |
| [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Especifica si se debe usar un modelador de texto para una mejor visualización del kerning. |
| [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Determina si la estructura del documento debe conservarse al convertir a PDF (el valor predeterminado es falso). |
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
| [getSkipExternalResources()](#getSkipExternalResources--) | \\{@inheritDoc\\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \\{@inheritDoc\\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \\{@inheritDoc\\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \\{@inheritDoc\\} |
| [getCommentDisplayMode()](#getCommentDisplayMode--) | Especifica cómo deben mostrarse los comentarios en el documento de salida. |
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
| [getShowFullCommenterName()](#getShowFullCommenterName--) | Mostrar el nombre completo del comentarista en los comentarios. |
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Inicializa una nueva instancia de la clase [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).

### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Tipo de archivo del documento de entrada

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Fuente predeterminada para documentos de Word. La siguiente fuente se usará si falta una fuente.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Fuente predeterminada para documentos de Word. La siguiente fuente se usará si falta una fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa la DefaultFont para la sustitución de fuentes faltantes. Si AutoFontSubstitution está habilitado, GroupDocs.Conversion evalúa todos los campos relacionados en FontInfo (Panose, Sig, etc.) para la fuente faltante y encuentra la coincidencia más cercana entre las fuentes disponibles. Tenga en cuenta que el mecanismo de sustitución de fuentes sobrescribirá la DefaultFont en los casos en que FontInfo para la fuente faltante esté disponible en el documento. El valor predeterminado es True.

**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa la DefaultFont para la sustitución de fuentes faltantes. Si AutoFontSubstitution está habilitado, GroupDocs.Conversion evalúa todos los campos relacionados en FontInfo (Panose, Sig, etc.) para la fuente faltante y encuentra la coincidencia más cercana entre las fuentes disponibles. Tenga en cuenta que el mecanismo de sustitución de fuentes sobrescribirá la DefaultFont en los casos en que FontInfo para la fuente faltante esté disponible en el documento. El valor predeterminado es True.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sustituir fuentes específicas al convertir documentos de Word.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Si EmbedTrueTypeFonts es true, GroupDocs.Conversion incrusta fuentes TrueType en el documento de salida. Predeterminado: false

**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Actualizar el diseño de página después de cargar. Predeterminado: false

**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Actualizar los campos después de cargar. Predeterminado: false

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Mantener el valor original del campo de fecha. Predeterminado: false

**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Establece mantener el valor original del campo de fecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sustituir fuentes específicas al convertir documentos de Word.

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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Ocultar marcas y seguimiento de cambios para documentos de Word.

**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Ocultar marcas y seguimiento de cambios para documentos de Word.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Ocultar comentarios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Opciones de marcadores

**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Opciones de marcadores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Especifica si se deben conservar los campos de formulario de Microsoft Word como campos de formulario en PDF o convertirlos a texto. El predeterminado es false.

**Returns:**
boolean - bandera preserveFontFields
### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Establece la bandera preserveFontFields

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| preserveFontFields | boolean | conservar los campos de formulario de Microsoft Word como campos de formulario en PDF o convertirlos a texto |

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Especifica si se debe usar un formateador de texto para una mejor visualización del kerning. El predeterminado es false.

**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Especifica si se debe usar un formateador de texto para una mejor visualización del kerning. El predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isUseTextShaper | boolean | bandera isUseTextShaper |

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Determina si la estructura del documento debe preservarse al convertir a PDF (predeterminado es false). Tenga en cuenta que exportar la estructura del documento incrementa significativamente el consumo de memoria, especialmente en documentos grandes.

**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

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

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Especifica cómo se deben mostrar los comentarios en el documento de salida. El predeterminado es ShowInBalloons.

**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Mostrar el nombre completo del comentarista en los comentarios. Predeterminado es false.

**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

