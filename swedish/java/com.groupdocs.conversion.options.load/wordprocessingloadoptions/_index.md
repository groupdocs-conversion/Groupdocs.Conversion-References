---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för inläsning av WordProcessing-dokument."
type: docs
weight: 40
url: /sv/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Alternativ för inläsning av WordProcessing-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Initierar en ny instans av klassen [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för Words-dokument. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för Words-dokument. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Om AutoFontSubstitution är inaktiverat använder GroupDocs.Conversion DefaultFont för ersättning av saknade teckensnitt. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Om AutoFontSubstitution är inaktiverat använder GroupDocs.Conversion DefaultFont för ersättning av saknade teckensnitt. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Ersätt specifika teckensnitt vid konvertering av Words-dokument. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Om EmbedTrueTypeFonts är true, bäddar GroupDocs.Conversion in TrueType-teckensnitt i utdatafilen. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Uppdatera sidlayout efter inläsning. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Uppdatera fält efter inläsning. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Behåll originalvärdet för datumfältet. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Ställer in att behålla originalvärdet för datumfältet. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ersätt specifika teckensnitt vid konvertering av Words-dokument. |
|
|  | [getPassword()](#getPassword--) | Ange lösenord för att avskydda skyddat dokument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ange lösenord för att avskydda skyddat dokument. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Dölj markup och spåra ändringar för Word-dokument. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Dölj markup och spåra ändringar för Word-dokument. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Dölj kommentarer. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Bokmärkesalternativ |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Bokmärkesalternativ |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Anger om Microsoft Word-formulärfält ska bevaras som formulärfält i PDF eller konverteras till text. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Ställer in preserveFontFields-flaggan |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Anger om en textformare ska användas för bättre kerningvisning. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Anger om en textformare ska användas för bättre kerningvisning. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Bestämmer om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är falskt). |
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
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Anger hur kommentarer ska visas i utdata-dokumentet. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Visa fullständigt kommentatorsnamn i kommentarer. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Aktivera eller inaktivera generering av sidnumrering i konverterat dokument. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Hämtar avstavningsalternativ för WordProcessing-dokument. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Ställer in avstavningsalternativ för WordProcessing-dokument. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Hämtar flaggan InterruptThreadIfImageExceptionThrown Standard: falskt Om true avbryts huvudkonverteringstråden om ett undantag i en bildbehandlingstråd inträffade. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Ställer in flaggan InterruptThreadIfImageExceptionThrown |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | När den är aktiverad (standard) repareras bidi-flaggor för stycken och körningar vars text huvudsakligen är från höger till vänster (RTL) innan konvertering. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Ställer in autoDetectRtlDirection |
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


Initierar en ny instans av klassen [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Dokumentfiltyp för inmatning


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardtypsnitt för Words-dokument. Följande typsnitt kommer att användas om ett typsnitt saknas.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardtypsnitt för Words-dokument. Följande typsnitt kommer att användas om ett typsnitt saknas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Om AutoFontSubstitution är inaktiverad använder GroupDocs.Conversion DefaultFont för ersättning av saknade typsnitt. Om AutoFontSubstitution är aktiverad,
GroupDocs.Conversion utvärderar alla relaterade fält i FontInfo (Panose, Sig etc) för det saknade typsnittet och hittar den närmaste matchen bland de tillgängliga typsnittskällorna.
Observera att mekanismen för typsnittsersättning kommer att åsidosätta DefaultFont i fall då FontInfo för det saknade typsnittet finns i dokumentet. Standardvärdet är True.


**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Om AutoFontSubstitution är inaktiverad använder GroupDocs.Conversion DefaultFont för ersättning av saknade typsnitt. Om AutoFontSubstitution är aktiverad,
GroupDocs.Conversion utvärderar alla relaterade fält i FontInfo (Panose, Sig etc) för det saknade typsnittet och hittar den närmaste matchen bland de tillgängliga typsnittskällorna.
Observera att mekanismen för typsnittsersättning kommer att åsidosätta DefaultFont i fall då FontInfo för det saknade typsnittet finns i dokumentet. Standardvärdet är True.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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


Om EmbedTrueTypeFonts är true, embedder GroupDocs.Conversion true type fonts i utdata-dokumentet. Standard: falskt


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


Uppdatera sidlayout efter inläsning. Standard: falskt


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


Uppdatera fält efter inläsning. Standard: falskt


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


Behåll originalvärdet för datumfältet. Standard: falskt


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
| värde | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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
| värde | java.lang.String |  |

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
| värde | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Dölj kommentarer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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


Anger om Microsoft Word-formulärfält ska bevaras som formulärfält i PDF eller konverteras till text. Standard är falskt.


**Returns:**
boolesk - preserveFontFields flag

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Ställer in preserveFontFields-flaggan


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | preserveFontFields | boolean | bevara Microsoft Word-formulärfält som formulärfält i PDF eller konvertera dem till text |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Anger om en textformare ska användas för bättre kerningvisning. Standard är falskt.


**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Anger om en textformare ska användas för bättre kerningvisning. Standard är falskt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | isUseTextShaper | boolean | isUseTextShaper flagga |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Bestämmer om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är falskt). Observera att export av dokumentstrukturen avsevärt ökar minnesförbrukningen, särskilt för stora dokument.


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


Visa fullständigt kommentatorsnamn i kommentarer. Standard är falskt.


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

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Aktivera eller inaktivera generering av sidnumrering i konverterat dokument. Standard: falskt


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Hämtar avstavningsalternativ för WordProcessing-dokument.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Ställer in avstavningsalternativ för WordProcessing-dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Hämtar flaggan InterruptThreadIfImageExceptionThrown Standard: falskt Om true avbryts huvudkonverteringstråden om ett undantag i en bildbehandlingstråd inträffade.


**Returns:**
boolean
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Ställer in flaggan InterruptThreadIfImageExceptionThrown


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | boolean |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


När den är aktiverad (standard) repareras bidi-flaggor för stycken och körningar vars text huvudsakligen är från höger till vänster (RTL) innan konvertering.


Detta matchar den heuristik som används av Microsoft Word och LibreOffice och
fixar rendering av arabiska/hebreiska dokument som produceras av generatorer
(särskilt Google Docs) som avger OOXML utan


och med

i körningar som endast innehåller RTL-skript.


Ställ in på
false
för att bevara strikt OOXML-tolkning av
källmarkup.


**Returns:**
boolean
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Ställer in autoDetectRtlDirection


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | autoDetectRtlDirection | boolean | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Hämtar alternativ för att styra om dokumentbehållaren själv måste konverteras


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Alternativ för att styra om de ägda dokumenten i dokumentbehållaren måste konverteras


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Alternativ för att styra hur många nivåer i djupet konverteringen ska utföras


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| depth | int |  |

