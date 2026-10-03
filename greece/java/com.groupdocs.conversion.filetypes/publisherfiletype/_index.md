---
title: "PublisherFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα Publisher."
type: docs
weight: 24
url: /el/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Ορίζει έγγραφα Publisher.
Περιλαμβάνει τους ακόλουθους τύπους:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
Μάθετε περισσότερα για μορφές γραμματοσειρών [εδώ](../https://wiki.fileformat.com/publisher).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Pub](#Pub) | Ένα αρχείο PUB είναι ένα μορφότυπο αρχείου εγγράφου Microsoft Publisher. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Κατασκευαστής σειριοποίησης


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


Ένα αρχείο PUB είναι ένα μορφότυπο αρχείου εγγράφου Microsoft Publisher. Χρησιμοποιείται για τη δημιουργία διαφόρων τύπων σχεδιαστικών εγγράφων, όπως ενημερωτικά δελτία, φυλλάδια, μπροσούρες, καρτ ποστάλ κ.λπ. Τα αρχεία PUB μπορούν να περιέχουν κείμενο, ραστερικές και διανυσματικές εικόνες. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
