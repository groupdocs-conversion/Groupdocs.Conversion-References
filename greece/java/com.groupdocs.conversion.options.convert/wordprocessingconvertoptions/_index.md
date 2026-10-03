---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Επεξεργασίας Κειμένου."
type: docs
weight: 48
url: /el/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Επιλογές για μετατροπή σε τύπο αρχείου Επεξεργασίας Κειμένου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) class. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getDpi()](#getDpi--) | Επιθυμητό DPI σελίδας μετά τη μετατροπή. |
|
|  | [setDpi(int value)](#setDpi-int-) | Επιθυμητό DPI σελίδας μετά τη μετατροπή. |
|
|  | [getPassword()](#getPassword--) | Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
|
|  | [getRtfOptions()](#getRtfOptions--) | Ειδικές επιλογές μετατροπής RTF |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | Ειδικές επιλογές μετατροπής RTF |
|
|  | [getZoom()](#getZoom--) | Καθορίζει το επίπεδο ζουμ σε ποσοστό. |
|
|  | [setZoom(int value)](#setZoom-int-) | Καθορίζει το επίπεδο ζουμ σε ποσοστό. |
|
|  | [getMarginTop()](#getMarginTop--) | Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [getMarginRight()](#getMarginRight--) | Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή. |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Λαμβάνει |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Ορίζει |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) class.


### getDpi() {#getDpi--}
```
public final int getDpi()
```


Επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι: 96 dpi.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


Ειδικές επιλογές μετατροπής RTF


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


Ειδικές επιλογές μετατροπής RTF


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100.
Η προεπιλεγμένη ζουμ υποστηρίζεται μέχρι το Microsoft Word 2010. Από το Microsoft Word 2013 η προεπιλεγμένη ζουμ δεν ορίζεται πλέον στο έγγραφο, αλλά φαίνεται ότι χρησιμοποιεί τον παράγοντα ζουμ του τελευταίου ανοιγμένου εγγράφου.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100.
Η προεπιλεγμένη ζουμ υποστηρίζεται μέχρι το Microsoft Word 2010. Από το Microsoft Word 2013 η προεπιλεγμένη ζουμ δεν ορίζεται πλέον στο έγγραφο, αλλά φαίνεται ότι χρησιμοποιεί τον παράγοντα ζουμ του τελευταίου ανοιγμένου εγγράφου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Λαμβάνει προσανατολισμό σελίδας μετά τη μετατροπή


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Ορίζει επιθυμητό προσανατολισμό σελίδας μετά τη μετατροπή


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Λαμβάνει επιθυμητό μέγεθος σελίδας μετά τη μετατροπή


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Ορίστε επιθυμητό μέγεθος σελίδας μετά τη μετατροπή


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Καθορισμένο πλάτος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Ορίστε επιθυμητό πλάτος σελίδας


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Καθορισμένο ύψος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Ορίστε επιθυμητό ύψος σελίδας


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Λαμβάνει τη λειτουργία αναγνώρισης κατά τη μετατροπή από pdf


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Ορίζει τη λειτουργία αναγνώρισης κατά τη μετατροπή από pdf


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Λαμβάνει


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Ορίζει


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

