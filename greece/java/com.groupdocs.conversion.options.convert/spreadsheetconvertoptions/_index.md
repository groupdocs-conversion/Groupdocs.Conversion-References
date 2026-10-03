---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Φύλλου Εργασίας."
type: docs
weight: 40
url: /el/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Επιλογές για μετατροπή σε τύπο αρχείου Φύλλου Εργασίας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) class. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
|
|  | [getZoom()](#getZoom--) | Καθορίζει το επίπεδο ζουμ σε ποσοστό. |
|
|  | [setZoom(int value)](#setZoom-int-) | Καθορίζει το επίπεδο ζουμ σε ποσοστό. |
|
|  | [getSeparator()](#getSeparator--) | Καθορίζει το διαχωριστικό που θα χρησιμοποιηθεί κατά τη μετατροπή σε μορφές διαχωρισμένων. |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) class.


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

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Καθορίζει το διαχωριστικό που θα χρησιμοποιηθεί κατά τη μετατροπή σε μορφές διαχωρισμένων.


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| διαχωριστικό | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

