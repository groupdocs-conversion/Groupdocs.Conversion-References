---
title: "FileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Βασική κλάση τύπου αρχείου"
type: docs
weight: 16
url: /el/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Βασική κλάση τύπου αρχείου

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FileType()](#FileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Unknown](#Unknown) | Άγνωστος τύπος αρχείου |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Η μορφή αρχείου |
|
|  | [getExtension()](#getExtension--) | Η επέκταση αρχείου |
|
|  | [getFamily()](#getFamily--) | Η οικογένεια αρχείου |
|
|  | [getDescription()](#getDescription--) | Περιγραφή του τύπου αρχείου |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Επιστρέφει FileType για το καθορισμένο fileName |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Λαμβάνει FileType για την παρεχόμενη fileExtension |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Επιστρέφει FileType για την παρεχόμενη ροή εγγράφου |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Επιστρέφει όλες τις τιμές της απαρίθμησης. |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς |
|
|  | [getLoadOptions()](#getLoadOptions--) | Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου |
|
|  | [getConvertOptions()](#getConvertOptions--) | Προετοιμάστηκαν προεπιλεγμένες επιλογές μετατροπής για τον τύπο αρχείου |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Κατασκευαστής σειριοποίησης


### Unknown {#Unknown}
```
public static final FileType Unknown
```


Άγνωστος τύπος αρχείου


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Η μορφή αρχείου


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Η επέκταση αρχείου


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


Η οικογένεια αρχείου


**Returns:**
java.lang.String - Η οικογένεια αρχείου

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Περιγραφή του τύπου αρχείου


**Returns:**
java.lang.String - περιγραφή

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Επιστρέφει FileType για το καθορισμένο fileName


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | fileName | java.lang.String | Το όνομα αρχείου |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Λαμβάνει FileType για την παρεχόμενη fileExtension


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | fileExtension | java.lang.String | επέκταση αρχείου |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Επιστρέφει FileType για την παρεχόμενη ροή εγγράφου


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream που θα ελεγχθεί |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Επιστρέφει όλες τις τιμές της απαρίθμησης.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Απαριθμιζόμενοι τύποι αρχείων


T
: Απαριθμημένος τύπος αντικειμένου.

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς


**Returns:**
java.lang.String - Αναπαράσταση συμβολοσειράς του τύπου αρχείου

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές μετατροπής για τον τύπο αρχείου


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
boolean
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού.


**Returns:**
int
