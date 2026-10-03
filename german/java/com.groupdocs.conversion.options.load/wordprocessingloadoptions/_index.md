---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von WordProcessing-Dokumenten."
type: docs
weight: 40
url: /de/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Optionen zum Laden von WordProcessing-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Initialisiert eine neue Instanz der Klasse [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standard-Schriftart für ein Words-Dokument. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standard-Schriftart für ein Words-Dokument. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Wenn AutoFontSubstitution deaktiviert ist, verwendet GroupDocs.Conversion die DefaultFont für den Ersatz fehlender Schriftarten. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Wenn AutoFontSubstitution deaktiviert ist, verwendet GroupDocs.Conversion die DefaultFont für den Ersatz fehlender Schriftarten. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Ersetzen Sie bestimmte Schriftarten beim Konvertieren eines Words-Dokuments. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Wenn EmbedTrueTypeFonts wahr ist, bettet GroupDocs.Conversion TrueType-Schriftarten in das Ausgabedokument ein. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Seitenlayout nach dem Laden aktualisieren. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Felder nach dem Laden aktualisieren. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Ursprünglichen Wert des Datumsfeldes beibehalten. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Legt fest, den ursprünglichen Wert des Datumsfeldes beizubehalten. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ersetzen Sie bestimmte Schriftarten beim Konvertieren eines Words-Dokuments. |
|
|  | [getPassword()](#getPassword--) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Markup ausblenden und Änderungen für Word-Dokumente nachverfolgen. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Markup ausblenden und Änderungen für Word-Dokumente nachverfolgen. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Kommentare ausblenden. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Lesezeichen-Optionen |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Lesezeichen-Optionen |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Gibt an, ob Microsoft Word-Formularfelder als Formularfelder im PDF erhalten bleiben oder in Text konvertiert werden sollen. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Setzt das preserveFontFields-Flag |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Gibt an, ob ein Text-Shaper für eine bessere Kerning-Anzeige verwendet werden soll. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Gibt an, ob ein Text-Shaper für eine bessere Kerning-Anzeige verwendet werden soll. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Bestimmt, ob die Dokumentstruktur beim Konvertieren in PDF erhalten bleiben soll (Standard ist false). |
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
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Gibt an, wie Kommentare im Ausgabedokument angezeigt werden sollen. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Vollständigen Namen des Kommentators in Kommentaren anzeigen. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Ermöglicht oder deaktiviert die Erzeugung von Seitenzahlen im konvertierten Dokument. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Liefert Silbentrennungsoptionen für WordProcessing-Dokumente. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Setzt Silbentrennungsoptionen für WordProcessing-Dokumente. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Liefert das InterruptThreadIfImageExceptionThrown-Flag Standard: false. Wenn true, wird der Hauptkonvertierungs-Thread unterbrochen, falls in einem Bildverarbeitungs-Thread eine Ausnahme auftritt. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Setzt das InterruptThreadIfImageExceptionThrown-Flag |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Wenn aktiviert (Standard), werden Absätze und Läufe, deren Text überwiegend von rechts nach links (RTL) verläuft, vor der Konvertierung ihre Bidi-Flags repariert. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Setzt die autoDetectRtlDirection |
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


Initialisiert eine neue Instanz der Klasse [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standard-Schriftart für Words-Dokumente. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standard-Schriftart für Words-Dokumente. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Wenn AutoFontSubstitution deaktiviert ist, verwendet GroupDocs.Conversion die DefaultFont für den Ersatz fehlender Schriftarten. Wenn AutoFontSubstitution aktiviert ist,
GroupDocs.Conversion bewertet alle zugehörigen Felder in FontInfo (Panose, Sig usw.) für die fehlende Schriftart und findet die am besten passende unter den verfügbaren Schriftquellen.
Beachten Sie, dass der Schriftart-Ersetzungsmechanismus die DefaultFont überschreibt, wenn FontInfo für die fehlende Schriftart im Dokument verfügbar ist. Der Standardwert ist True.


**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Wenn AutoFontSubstitution deaktiviert ist, verwendet GroupDocs.Conversion die DefaultFont für den Ersatz fehlender Schriftarten. Wenn AutoFontSubstitution aktiviert ist,
GroupDocs.Conversion bewertet alle zugehörigen Felder in FontInfo (Panose, Sig usw.) für die fehlende Schriftart und findet die am besten passende unter den verfügbaren Schriftquellen.
Beachten Sie, dass der Schriftart-Ersetzungsmechanismus die DefaultFont überschreibt, wenn FontInfo für die fehlende Schriftart im Dokument verfügbar ist. Der Standardwert ist True.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ersetzen Sie bestimmte Schriftarten beim Konvertieren eines Words-Dokuments.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Wenn EmbedTrueTypeFonts true ist, bettet GroupDocs.Conversion TrueType-Schriftarten in das Ausgabedokument ein. Standard: false


**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Seitenlayout nach dem Laden aktualisieren. Standard: false


**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Felder nach dem Laden aktualisieren. Standard: false


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Behalte den ursprünglichen Wert des Datumsfeldes bei. Standard: false


**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Legt fest, den ursprünglichen Wert des Datumsfeldes beizubehalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ersetzen Sie bestimmte Schriftarten beim Konvertieren eines Words-Dokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Passwort festlegen, um ein geschütztes Dokument zu entsperren.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Passwort festlegen, um ein geschütztes Dokument zu entsperren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Markup ausblenden und Änderungen für Word-Dokumente nachverfolgen.


**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Markup ausblenden und Änderungen für Word-Dokumente nachverfolgen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Kommentare ausblenden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Lesezeichen-Optionen


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Lesezeichen-Optionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Gibt an, ob Microsoft Word-Formularfelder als Formularfelder im PDF erhalten oder in Text konvertiert werden sollen. Standard ist false.


**Returns:**
boolescher - preserveFontFields-Flag

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Setzt das preserveFontFields-Flag


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | preserveFontFields | boolean | Microsoft Word-Formularfelder als Formularfelder im PDF erhalten oder in Text konvertieren |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Gibt an, ob ein Text-Shaper für eine bessere Kerning-Anzeige verwendet werden soll. Standard ist false.


**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Gibt an, ob ein Text-Shaper für eine bessere Kerning-Anzeige verwendet werden soll. Standard ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | isUseTextShaper | boolean | isUseTextShaper-Flag |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Bestimmt, ob die Dokumentstruktur beim Konvertieren in PDF erhalten bleiben soll (Standard ist false). Hinweis: Das Exportieren der Dokumentstruktur erhöht den Speicherverbrauch erheblich, insbesondere bei großen Dokumenten.


**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Wenn true, werden alle externen Ressourcen nicht geladen, mit Ausnahme der Ressourcen in der


**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Externe Ressourcen, die immer geladen werden


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Gibt an, wie Kommentare im Ausgabedokument angezeigt werden sollen. Standard ist ShowInBalloons.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Vollständigen Namen des Kommentators in Kommentaren anzeigen. Standard ist false.


**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Aktivieren oder deaktivieren der Seitennummerierung im konvertierten Dokument. Standard: false


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Liefert Silbentrennungsoptionen für WordProcessing-Dokumente.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Setzt Silbentrennungsoptionen für WordProcessing-Dokumente.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Liefert das InterruptThreadIfImageExceptionThrown-Flag Standard: false. Wenn true, wird der Hauptkonvertierungs-Thread unterbrochen, falls in einem Bildverarbeitungs-Thread eine Ausnahme auftritt.


**Returns:**
boolean
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Setzt das InterruptThreadIfImageExceptionThrown-Flag


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | boolean |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Wenn aktiviert (Standard), werden Absätze und Läufe, deren Text überwiegend von rechts nach links (RTL) verläuft, vor der Konvertierung ihre Bidi-Flags repariert.


Dies entspricht der von Microsoft Word und LibreOffice angewandten Heuristik und
behebt die Darstellung von Arabisch/Hebräisch-Dokumenten, die von Generatoren erzeugt werden
(insbesondere Google Docs), die OOXML ohne


und mit

bei Ausführungen, die nur RTL‑Skript enthalten.


Setzen Sie auf
false
um die strenge OOXML‑Interpretation des
Quell‑Markups.


**Returns:**
boolean
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Setzt die autoDetectRtlDirection


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | autoDetectRtlDirection | boolean | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ruft die Option ab, um zu steuern, ob der Dokumentcontainer selbst konvertiert werden muss


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option, um zu steuern, ob die im Dokumentcontainer enthaltenen Dokumente konvertiert werden müssen


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option, um zu steuern, wie viele Ebenen tief die Konvertierung durchgeführt werden soll


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tiefe | int |  |

