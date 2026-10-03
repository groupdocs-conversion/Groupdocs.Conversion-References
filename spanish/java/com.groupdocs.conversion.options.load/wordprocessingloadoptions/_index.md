---
title: "WordProcessingLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de WordProcessing."
type: docs
weight: 40
url: /es/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Opciones para cargar documentos de WordProcessing.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Inicializa una nueva instancia de la clase [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Fuente predeterminada para documentos de Word. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Fuente predeterminada para documentos de Word. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa DefaultFont para la sustitución de fuentes faltantes. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa DefaultFont para la sustitución de fuentes faltantes. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sustituir fuentes específicas al convertir documentos de Word. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Si EmbedTrueTypeFonts es true, GroupDocs.Conversion incrusta fuentes TrueType en el documento de salida. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Actualizar el diseño de página después de cargar. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Actualizar los campos después de cargar. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Mantener el valor original del campo de fecha. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Establece mantener el valor original del campo de fecha. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sustituir fuentes específicas al convertir documentos de Word. |
|
|  | [getPassword()](#getPassword--) | Establecer contraseña para desproteger el documento protegido. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establecer contraseña para desproteger el documento protegido. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Ocultar marcas y seguimiento de cambios para documentos de Word. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Ocultar marcas y seguimiento de cambios para documentos de Word. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Ocultar comentarios. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Opciones de marcadores |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Opciones de marcadores |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Especifica si se deben conservar los campos de formulario de Microsoft Word como campos de formulario en PDF o convertirlos a texto. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Establece la bandera preserveFontFields |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Especifica si se debe usar un formateador de texto para una mejor visualización del kerning. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Especifica si se debe usar un formateador de texto para una mejor visualización del kerning. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Determina si la estructura del documento debe preservarse al convertir a PDF (el valor predeterminado es false). |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Especifica cómo se deben mostrar los comentarios en el documento de salida. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Mostrar el nombre completo del comentarista en los comentarios. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Habilitar o deshabilitar la generación de numeración de páginas en el documento convertido. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Obtiene las opciones de guionado para documentos WordProcessing. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Establece opciones de hifenación para documentos de WordProcessing. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Obtiene la bandera InterruptThreadIfImageExceptionThrown Predeterminado: false Si es true entonces interrumpe el hilo principal de conversión si se produce una excepción en un hilo de procesamiento de imágenes |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Establece la bandera InterruptThreadIfImageExceptionThrown |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Cuando está habilitado (predeterminado), los párrafos y ejecuciones cuyo texto es predominantemente de derecha a izquierda (RTL) tendrán sus banderas bidi reparadas antes de la conversión. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Establece autoDetectRtlDirection |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
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


Fuente predeterminada para documentos de Words. La siguiente fuente se utilizará si falta una fuente.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Fuente predeterminada para documentos de Words. La siguiente fuente se utilizará si falta una fuente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa DefaultFont para la sustitución de fuentes faltantes. Si AutoFontSubstitution está habilitado,
GroupDocs.Conversion evalúa todos los campos relacionados en FontInfo (Panose, Sig, etc.) para la fuente faltante y encuentra la coincidencia más cercana entre las fuentes disponibles.
Tenga en cuenta que el mecanismo de sustitución de fuentes sobrescribirá DefaultFont en los casos en que FontInfo para la fuente faltante esté disponible en el documento. El valor predeterminado es True.


**Returns:**
booleano
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Si AutoFontSubstitution está deshabilitado, GroupDocs.Conversion usa DefaultFont para la sustitución de fuentes faltantes. Si AutoFontSubstitution está habilitado,
GroupDocs.Conversion evalúa todos los campos relacionados en FontInfo (Panose, Sig, etc.) para la fuente faltante y encuentra la coincidencia más cercana entre las fuentes disponibles.
Tenga en cuenta que el mecanismo de sustitución de fuentes sobrescribirá DefaultFont en los casos en que FontInfo para la fuente faltante esté disponible en el documento. El valor predeterminado es True.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

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
booleano
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embedTrueTypeFonts | booleano |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Actualiza el diseño de página después de cargar. Predeterminado: false


**Returns:**
booleano
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| updatePageLayout | booleano |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Actualiza los campos después de cargar. Predeterminado: false


**Returns:**
booleano
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| updateFields | booleano |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Mantiene el valor original del campo de fecha. Predeterminado: false


**Returns:**
booleano
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Establece mantener el valor original del campo de fecha.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keepDateFieldOriginalValue | booleano |  |

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
booleano
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Ocultar marcas y seguimiento de cambios para documentos de Word.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Ocultar comentarios.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

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
|  | preserveFontFields | booleano | conservar los campos de formulario de Microsoft Word como campos de formulario en PDF o convertirlos a texto |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Especifica si se debe usar un modelador de texto para una mejor visualización del kerning. El predeterminado es false.


**Returns:**
booleano
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Especifica si se debe usar un modelador de texto para una mejor visualización del kerning. El predeterminado es false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | isUseTextShaper | booleano | bandera isUseTextShaper |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Determina si la estructura del documento debe preservarse al convertir a PDF (el valor predeterminado es false). Tenga en cuenta que exportar la estructura del documento incrementa significativamente el consumo de memoria, especialmente para los documentos grandes.


**Returns:**
booleano
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| preserveDocumentStructure | booleano |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Si es true, todos los recursos externos no se cargarán, con excepción de los recursos en el


**Returns:**
booleano
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| omitir | booleano |  |

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


Especifica cómo deben mostrarse los comentarios en el documento de salida. El valor predeterminado es ShowInBalloons.


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


Mostrar el nombre completo del comentarista en los comentarios. El valor predeterminado es false.


**Returns:**
booleano
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| showFullCommenterName | booleano |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Habilitar o deshabilitar la generación de numeración de páginas en el documento convertido. Predeterminado: false


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

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Obtiene las opciones de guionado para documentos WordProcessing.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Establece opciones de hifenación para documentos de WordProcessing.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Obtiene la bandera InterruptThreadIfImageExceptionThrown Predeterminado: false Si es true entonces interrumpe el hilo principal de conversión si se produce una excepción en un hilo de procesamiento de imágenes


**Returns:**
booleano
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Establece la bandera InterruptThreadIfImageExceptionThrown


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | booleano |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Cuando está habilitado (predeterminado), los párrafos y ejecuciones cuyo texto es predominantemente de derecha a izquierda (RTL) tendrán sus banderas bidi reparadas antes de la conversión.


Esto coincide con la heurística aplicada por Microsoft Word y LibreOffice y
corrige la renderización de documentos en árabe/hebreo generados por creadores
(principalmente Google Docs) que emiten OOXML sin


y con

en ejecuciones que contienen solo script RTL.


Establecer a
false
para preservar la interpretación estricta de OOXML del
marcado fuente.


**Returns:**
booleano
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Establece autoDetectRtlDirection


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | autoDetectRtlDirection | booleano | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtiene la opción para controlar si el contenedor de los documentos debe convertirse


**Returns:**
booleano
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwner | booleano |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opción para controlar si los documentos propios en el contenedor de documentos deben convertirse


**Returns:**
booleano
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwned | booleano |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opción para controlar cuántos niveles de profundidad se deben usar para realizar la conversión


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| depth | int |  |

