---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för att ladda WordProcessing-dokument."
type: docs
weight: 44
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Alternativ för att ladda WordProcessing-dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Initierar en ny instans av klassen [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för Words-dokument. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för Words-dokument. |
| [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Om AutoFontSubstitution är inaktiverat använder GroupDocs.Conversion DefaultFont för ersättning av saknade teckensnitt. |
| [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Om AutoFontSubstitution är inaktiverat använder GroupDocs.Conversion DefaultFont för ersättning av saknade teckensnitt. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Ersätt specifika teckensnitt vid konvertering av Words-dokument. |
| [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Om EmbedTrueTypeFonts är true, bäddar GroupDocs.Conversion in true type-teckensnitt i utdatafilen. |
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
| [isUpdatePageLayout()](#isUpdatePageLayout--) | Uppdatera sidlayout efter inläsning. |
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
| [isUpdateFields()](#isUpdateFields--) | Uppdatera fält efter inläsning. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
| [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Behåll originalvärdet för datumfältet. |
| [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Ställer in att behålla originalvärdet för datumfältet. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ersätt specifika teckensnitt vid konvertering av Words-dokument. |
| [getPassword()](#getPassword--) | Ange lösenord för att avskydda skyddat dokument. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ange lösenord för att avskydda skyddat dokument. |
| [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Dölj markup och spåra ändringar för Word-dokument. |
| [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Dölj markup och spåra ändringar för Word-dokument. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Dölj kommentarer. |
| [getBookmarkOptions()](#getBookmarkOptions--) | Bokmärkesalternativ |
| [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Bokmärkesalternativ |
| [isPreserveFontFields()](#isPreserveFontFields--) | Anger om Microsoft Word-formulärfält ska bevaras som formulärfält i PDF eller konverteras till text. |
| [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Ställer in preserveFontFields-flaggan |
| [isUseTextShaper()](#isUseTextShaper--) | Anger om en textformare ska användas för bättre kerningvisning. |
| [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Anger om en textformare ska användas för bättre kerningvisning. |
| [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Bestämmer om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är false). |
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
| [getSkipExternalResources()](#getSkipExternalResources--) | \\{@inheritDoc\\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \\{@inheritDoc\\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \\{@inheritDoc\\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \\{@inheritDoc\\} |
| [getCommentDisplayMode()](#getCommentDisplayMode--) | Anger hur kommentarer ska visas i utdata-dokumentet. |
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
| [getShowFullCommenterName()](#getShowFullCommenterName--) | Visa kommentatorns fullständiga namn i kommentarer. |
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Initierar en ny instans av klassen [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).

### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Inmatningsdokumentets filtyp

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardteckensnitt för Words-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardteckensnitt för Words-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Om AutoFontSubstitution är inaktiverad använder GroupDocs.Conversion DefaultFont för ersättning av saknade teckensnitt. Om AutoFontSubstitution är aktiverad utvärderar GroupDocs.Conversion alla relaterade fält i FontInfo (Panose, Sig osv.) för det saknade teckensnittet och hittar den närmaste matchen bland de tillgängliga teckensnittskällorna. Observera att teckensnittsersättningsmekanismen kommer att åsidosätta DefaultFont i fall där FontInfo för det saknade teckensnittet finns i dokumentet. Standardvärdet är True.

**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Om AutoFontSubstitution är inaktiverad använder GroupDocs.Conversion DefaultFont för ersättning av saknade teckensnitt. Om AutoFontSubstitution är aktiverad utvärderar GroupDocs.Conversion alla relaterade fält i FontInfo (Panose, Sig osv.) för det saknade teckensnittet och hittar den närmaste matchen bland de tillgängliga teckensnittskällorna. Observera att teckensnittsersättningsmekanismen kommer att åsidosätta DefaultFont i fall där FontInfo för det saknade teckensnittet finns i dokumentet. Standardvärdet är True.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ersätt specifika teckensnitt vid konvertering av Words-dokument.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Om EmbedTrueTypeFonts är true, bäddar GroupDocs.Conversion in TrueType-teckensnitt i utdata-dokumentet. Standard: false

**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Uppdatera sidlayout efter inläsning. Standard: false

**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Uppdatera fält efter inläsning. Standard: false

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Behåll det ursprungliga värdet för datumfältet. Standard: false

**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Ställer in att behålla originalvärdet för datumfältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ersätt specifika teckensnitt vid konvertering av Words-dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ange lösenord för att avskydda skyddat dokument.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ange lösenord för att avskydda skyddat dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Dölj markup och spåra ändringar för Word-dokument.

**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Dölj markup och spåra ändringar för Word-dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Dölj kommentarer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Bokmärkesalternativ

**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Bokmärkesalternativ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Anger om Microsoft Word-formulärfält ska bevaras som formulärfält i PDF eller konverteras till text. Standard är false.

**Returns:**
boolean - preserveFontFields flagga
### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Ställer in preserveFontFields-flaggan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| preserveFontFields | boolean | bevara Microsoft Word-formulärfält som formulärfält i PDF eller konvertera dem till text |

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Anger om en textformare ska användas för bättre kerningvisning. Standard är false.

**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Anger om en textformare ska användas för bättre kerningvisning. Standard är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isUseTextShaper | boolean | isUseTextShaper flagga |

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Bestämmer om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är false). Observera att export av dokumentstrukturen avsevärt ökar minnesförbrukningen, särskilt för stora dokument.

**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Om true kommer alla externa resurser inte att laddas med undantag för resurserna i

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Externa resurser som alltid kommer att laddas

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Anger hur kommentarer ska visas i utdata-dokumentet. Standard är ShowInBalloons.

**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Visa fullständigt kommentatorsnamn i kommentarer. Standard är false.

**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

