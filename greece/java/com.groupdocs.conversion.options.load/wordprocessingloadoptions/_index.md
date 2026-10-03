---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για τη φόρτωση εγγράφων WordProcessing."
type: docs
weight: 40
url: /el/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Επιλογές για τη φόρτωση εγγράφων WordProcessing.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Προεπιλεγμένη γραμματοσειρά για έγγραφο Words. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Προεπιλεγμένη γραμματοσειρά για έγγραφο Words. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Εάν η AutoFontSubstitution είναι απενεργοποιημένη, το GroupDocs.Conversion χρησιμοποιεί το DefaultFont για την αντικατάσταση των ελλιπών γραμματοσειρών. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Εάν η AutoFontSubstitution είναι απενεργοποιημένη, το GroupDocs.Conversion χρησιμοποιεί το DefaultFont για την αντικατάσταση των ελλιπών γραμματοσειρών. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου Words. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Εάν η EmbedTrueTypeFonts είναι true, το GroupDocs.Conversion ενσωματώνει γραμματοσειρές TrueType στο τελικό έγγραφο. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Ενημέρωση διάταξης σελίδας μετά τη φόρτωση. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Ενημέρωση πεδίων μετά τη φόρτωση. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Διατήρηση αρχικής τιμής του πεδίου ημερομηνίας. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Ορίζει τη διατήρηση της αρχικής τιμής του πεδίου ημερομηνίας. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου Words. |
|
|  | [getPassword()](#getPassword--) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Απόκρυψη σήμανσης και παρακολούθηση αλλαγών για έγγραφα Word. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Απόκρυψη σήμανσης και παρακολούθηση αλλαγών για έγγραφα Word. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Απόκρυψη σχολίων. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Επιλογές σελιδοδεικτών |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Επιλογές σελιδοδεικτών |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Καθορίζει εάν θα διατηρηθούν τα πεδία φόρμας του Microsoft Word ως πεδία φόρμας σε PDF ή θα μετατραπούν σε κείμενο. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Ορίζει τη σημαία preserveFontFields |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Καθορίζει εάν θα χρησιμοποιηθεί ένας διαμορφωτής κειμένου για καλύτερη εμφάνιση του kerning. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Καθορίζει εάν θα χρησιμοποιηθεί ένας διαμορφωτής κειμένου για καλύτερη εμφάνιση του kerning. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Καθορίζει εάν η δομή του εγγράφου πρέπει να διατηρηθεί κατά τη μετατροπή σε PDF (η προεπιλογή είναι false). |
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
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Καθορίζει πώς θα εμφανίζονται τα σχόλια στο τελικό έγγραφο. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Εμφάνιση πλήρους ονόματος σχολιαστή στα σχόλια. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Λαμβάνει τις επιλογές συλλαβισμού για έγγραφα WordProcessing. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Ορίζει επιλογές συλλαβισμού για έγγραφα WordProcessing. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Λαμβάνει τη σημαία InterruptThreadIfImageExceptionThrown Προεπιλογή: false Εάν είναι true, διακόπτει το κύριο νήμα μετατροπής εάν προκύψει εξαίρεση σε νήμα επεξεργασίας εικόνας |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Ορίζει τη σημαία InterruptThreadIfImageExceptionThrown |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Όταν είναι ενεργό (προεπιλογή), οι παράγραφοι και τα τμήματα κειμένου των οποίων το κείμενο είναι κυρίως από δεξιά προς αριστερά (RTL) θα έχουν τις σημαίες bidi διορθωμένες πριν από τη μετατροπή. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Ορίζει το autoDetectRtlDirection |
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


Αρχικοποιεί νέα παρουσία της κλάσης [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Προεπιλεγμένη γραμματοσειρά για έγγραφο Words. Η ακόλουθη γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Προεπιλεγμένη γραμματοσειρά για έγγραφο Words. Η ακόλουθη γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Εάν το AutoFontSubstitution είναι απενεργοποιημένο, το GroupDocs.Conversion χρησιμοποιεί το DefaultFont για την αντικατάσταση των ελλιπών γραμματοσειρών. Εάν το AutoFontSubstitution είναι ενεργοποιημένο,
Το GroupDocs.Conversion αξιολογεί όλα τα σχετικά πεδία στο FontInfo (Panose, Sig κλπ) για τη λείπουσα γραμματοσειρά και βρίσκει την πιο κοντινή αντιστοιχία μεταξύ των διαθέσιμων πηγών γραμματοσειρών.
Σημειώστε ότι ο μηχανισμός αντικατάστασης γραμματοσειρών θα παρακάμπτει το DefaultFont σε περιπτώσεις όπου το FontInfo για τη λείπουσα γραμματοσειρά είναι διαθέσιμο στο έγγραφο. Η προεπιλεγμένη τιμή είναι True.


**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Εάν το AutoFontSubstitution είναι απενεργοποιημένο, το GroupDocs.Conversion χρησιμοποιεί το DefaultFont για την αντικατάσταση των ελλιπών γραμματοσειρών. Εάν το AutoFontSubstitution είναι ενεργοποιημένο,
Το GroupDocs.Conversion αξιολογεί όλα τα σχετικά πεδία στο FontInfo (Panose, Sig κλπ) για τη λείπουσα γραμματοσειρά και βρίσκει την πιο κοντινή αντιστοιχία μεταξύ των διαθέσιμων πηγών γραμματοσειρών.
Σημειώστε ότι ο μηχανισμός αντικατάστασης γραμματοσειρών θα παρακάμπτει το DefaultFont σε περιπτώσεις όπου το FontInfo για τη λείπουσα γραμματοσειρά είναι διαθέσιμο στο έγγραφο. Η προεπιλεγμένη τιμή είναι True.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου Words.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Εάν το EmbedTrueTypeFonts είναι true, το GroupDocs.Conversion ενσωματώνει γραμματοσειρές TrueType στο έγγραφο εξόδου. Προεπιλογή: false


**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Ενημέρωση διάταξης σελίδας μετά τη φόρτωση. Προεπιλογή: false


**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Ενημέρωση πεδίων μετά τη φόρτωση. Προεπιλογή: false


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Διατήρηση αρχικής τιμής του πεδίου ημερομηνίας. Προεπιλογή: false


**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Ορίζει τη διατήρηση της αρχικής τιμής του πεδίου ημερομηνίας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου Words.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Απόκρυψη σήμανσης και παρακολούθηση αλλαγών για έγγραφα Word.


**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Απόκρυψη σήμανσης και παρακολούθηση αλλαγών για έγγραφα Word.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Απόκρυψη σχολίων.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Επιλογές σελιδοδεικτών


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Επιλογές σελιδοδεικτών


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Καθορίζει αν θα διατηρηθούν τα πεδία φόρμας του Microsoft Word ως πεδία φόρμας σε PDF ή θα μετατραπούν σε κείμενο. Η προεπιλογή είναι false.


**Returns:**
boolean - σημαία preserveFontFields

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Ορίζει τη σημαία preserveFontFields


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | preserveFontFields | boolean | διατηρήστε τα πεδία φόρμας του Microsoft Word ως πεδία φόρμας σε PDF ή μετατρέψτε τα σε κείμενο |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Καθορίζει αν θα χρησιμοποιηθεί ένας διαμορφωτής κειμένου για καλύτερη εμφάνιση του kerning. Η προεπιλογή είναι false.


**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Καθορίζει αν θα χρησιμοποιηθεί ένας διαμορφωτής κειμένου για καλύτερη εμφάνιση του kerning. Η προεπιλογή είναι false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | isUseTextShaper | boolean | σημαία isUseTextShaper |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Καθορίζει εάν η δομή του εγγράφου πρέπει να διατηρηθεί κατά τη μετατροπή σε PDF (η προεπιλογή είναι ψευδής). Σημειώστε ότι η εξαγωγή της δομής του εγγράφου αυξάνει σημαντικά την κατανάλωση μνήμης, ιδιαίτερα για τα μεγάλα έγγραφα.


**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Εάν είναι αληθές, όλοι οι εξωτερικοί πόροι δεν θα φορτώνονται, εκτός από τους πόρους στο


**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| παράλειψη | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Εξωτερικοί πόροι που θα φορτώνονται πάντα


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Καθορίζει πώς πρέπει να εμφανίζονται τα σχόλια στο τελικό έγγραφο. Η προεπιλογή είναι ShowInBalloons.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Εμφάνιση πλήρους ονόματος σχολιαστή στα σχόλια. Η προεπιλογή είναι ψευδής.


**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. Προεπιλογή: ψευδής.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Λαμβάνει τις επιλογές συλλαβισμού για έγγραφα WordProcessing.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Ορίζει επιλογές συλλαβισμού για έγγραφα WordProcessing.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Λαμβάνει τη σημαία InterruptThreadIfImageExceptionThrown Προεπιλογή: false Εάν είναι true, διακόπτει το κύριο νήμα μετατροπής εάν προκύψει εξαίρεση σε νήμα επεξεργασίας εικόνας


**Returns:**
boolean
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Ορίζει τη σημαία InterruptThreadIfImageExceptionThrown


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | boolean |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Όταν είναι ενεργό (προεπιλογή), οι παράγραφοι και τα τμήματα κειμένου των οποίων το κείμενο είναι κυρίως από δεξιά προς αριστερά (RTL) θα έχουν τις σημαίες bidi διορθωμένες πριν από τη μετατροπή.


Αυτό ταιριάζει με την ευρετική μέθοδο που εφαρμόζεται από το Microsoft Word και το LibreOffice και
διορθώνει την απόδοση εγγράφων Αραβικών/Εβραϊκών που παράγονται από δημιουργούς
(ιδιαίτερα Google Docs) που εκδίδουν OOXML χωρίς


και με

σε τμήματα που περιέχουν μόνο κείμενο RTL.


Ορίστε σε
ψευδής
για να διατηρηθεί αυστηρή ερμηνεία OOXML του
πρωτογενές markup.


**Returns:**
boolean
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Ορίζει το autoDetectRtlDirection


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | autoDetectRtlDirection | boolean | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Λαμβάνει επιλογή για τον έλεγχο εάν το ίδιο το δοχείο των εγγράφων πρέπει να μετατραπεί


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Επιλογή για έλεγχο του αν τα ιδιόκτητα έγγραφα στο δοχείο εγγράφων πρέπει να μετατραπούν


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Επιλογή για έλεγχο του πόσων επιπέδων σε βάθος θα γίνει η μετατροπή


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| depth | int |  |

