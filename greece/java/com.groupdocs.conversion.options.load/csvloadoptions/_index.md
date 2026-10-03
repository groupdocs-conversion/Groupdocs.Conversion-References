---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων CSV."
type: docs
weight: 13
url: /el/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Επιλογές φόρτωσης εγγράφων CSV.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Διαχωριστικό ενός αρχείου Csv. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Διαχωριστικό ενός αρχείου Csv. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True σημαίνει ότι το αρχείο περιέχει πολλαπλές κωδικοποιήσεις. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True σημαίνει ότι το αρχείο περιέχει πολλαπλές κωδικοποιήσεις. |
|
|  | [hasFormula()](#hasFormula--) | Δείχνει εάν το κείμενο είναι τύπος αν αρχίζει με "=". |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Δείχνει εάν το κείμενο είναι τύπος αν αρχίζει με "=". |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Δείχνει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε αριθμητική. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Δείχνει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε αριθμητική. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Δείχνει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε ημερομηνία. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Δείχνει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε ημερομηνία. |
|
|  | [getEncoding()](#getEncoding--) | Κωδικοποίηση. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Κωδικοποίηση. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Διαχωριστικό ενός αρχείου Csv.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Διαχωριστικό ενός αρχείου Csv.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True σημαίνει ότι το αρχείο περιέχει πολλαπλές κωδικοποιήσεις.


**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True σημαίνει ότι το αρχείο περιέχει πολλαπλές κωδικοποιήσεις.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Δείχνει εάν το κείμενο είναι τύπος αν αρχίζει με "=".


**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Δείχνει εάν το κείμενο είναι τύπος αν αρχίζει με "=".


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Υποδεικνύει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε αριθμητική. Η προεπιλογή είναι True.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Υποδεικνύει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε αριθμητική. Η προεπιλογή είναι True.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Υποδεικνύει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε ημερομηνία. Η προεπιλογή είναι True.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Υποδεικνύει εάν η συμβολοσειρά στο αρχείο μετατρέπεται σε ημερομηνία. Η προεπιλογή είναι True.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Κωδικοποίηση. Η προεπιλογή είναι Encoding.Default.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Κωδικοποίηση. Η προεπιλογή είναι Encoding.Default.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Text.Encoding |  |

