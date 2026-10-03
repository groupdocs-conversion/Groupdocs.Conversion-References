---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για τη διαχείριση σελιδοδεικτών στο WordProcessing"
type: docs
weight: 39
url: /el/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Επιλογές για τη διαχείριση σελιδοδεικτών στο WordProcessing

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Καθορίζει το προεπιλεγμένο επίπεδο στο περίγραμμα του εγγράφου όπου θα εμφανίζονται οι σελιδοδείκτες Word. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Καθορίζει το προεπιλεγμένο επίπεδο στο περίγραμμα του εγγράφου όπου θα εμφανίζονται οι σελιδοδείκτες Word. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Καθορίζει πόσα επίπεδα επικεφαλίδων (παράγραφοι μορφοποιημένες με τα στυλ Heading) θα συμπεριληφθούν στο περίγραμμα του εγγράφου. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Καθορίζει πόσα επίπεδα επικεφαλίδων (παράγραφοι μορφοποιημένες με τα στυλ Heading) θα συμπεριληφθούν στο περίγραμμα του εγγράφου. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Καθορίζει πόσα επίπεδα στο περίγραμμα του εγγράφου θα εμφανιστούν αναπτυγμένα όταν το αρχείο προβληθεί. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Καθορίζει πόσα επίπεδα στο περίγραμμα του εγγράφου θα εμφανιστούν αναπτυγμένα όταν το αρχείο προβληθεί. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Καθορίζει το προεπιλεγμένο επίπεδο στο περίγραμμα του εγγράφου στο οποίο θα εμφανίζονται οι σελιδοδείκτες Word. Η προεπιλογή είναι 0. Η έγκυρη περιοχή είναι από 0 έως 9.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Καθορίζει το προεπιλεγμένο επίπεδο στο περίγραμμα του εγγράφου στο οποίο θα εμφανίζονται οι σελιδοδείκτες Word. Η προεπιλογή είναι 0. Η έγκυρη περιοχή είναι από 0 έως 9.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Καθορίζει πόσα επίπεδα επικεφαλίδων (παράγραφοι μορφοποιημένες με τα στυλ Heading) θα συμπεριληφθούν στο περίγραμμα του εγγράφου. Η προεπιλογή είναι 0. Η έγκυρη περιοχή είναι από 0 έως 9.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Καθορίζει πόσα επίπεδα επικεφαλίδων (παράγραφοι μορφοποιημένες με τα στυλ Heading) θα συμπεριληφθούν στο περίγραμμα του εγγράφου. Η προεπιλογή είναι 0. Η έγκυρη περιοχή είναι από 0 έως 9.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Καθορίζει πόσα επίπεδα στο περίγραμμα του εγγράφου θα εμφανιστούν αναπτυγμένα όταν το αρχείο προβληθεί. Η προεπιλογή είναι 0. Η έγκυρη περιοχή είναι από 0 έως 9. Σημειώστε ότι αυτή η επιλογή δεν θα λειτουργήσει κατά την αποθήκευση σε XPS.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Καθορίζει πόσα επίπεδα στο περίγραμμα του εγγράφου θα εμφανιστούν αναπτυγμένα όταν το αρχείο προβληθεί. Η προεπιλογή είναι 0. Η έγκυρη περιοχή είναι από 0 έως 9. Σημειώστε ότι αυτή η επιλογή δεν θα λειτουργήσει κατά την αποθήκευση σε XPS.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

