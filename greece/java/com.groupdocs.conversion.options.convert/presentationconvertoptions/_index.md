---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιγράφει τις επιλογές για μετατροπή σε τύπο αρχείου Παρουσίασης."
type: docs
weight: 33
url: /el/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Περιγράφει τις επιλογές για μετατροπή σε τύπο αρχείου Παρουσίασης.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
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
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


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
Το προεπιλεγμένο ζουμ υποστηρίζεται έως το Microsoft Powerpoint 2010. Από το Microsoft Powerpoint 2013 το προεπιλεγμένο ζουμ δεν ορίζεται πλέον στο έγγραφο, αλλά φαίνεται να χρησιμοποιεί τον παράγοντα ζουμ του τελευταίου ανοιγμένου εγγράφου.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100.
Το προεπιλεγμένο ζουμ υποστηρίζεται έως το Microsoft Powerpoint 2010. Από το Microsoft Powerpoint 2013 το προεπιλεγμένο ζουμ δεν ορίζεται πλέον στο έγγραφο, αλλά φαίνεται να χρησιμοποιεί τον παράγοντα ζουμ του τελευταίου ανοιγμένου εγγράφου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

