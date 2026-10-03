---
title: "FileCache"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Συμπεριφορά προσωρινής αποθήκευσης αρχείων."
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Συμπεριφορά προσωρινής αποθήκευσης σε αρχείο. Σημαίνει ότι η προσωρινή μνήμη αποθηκεύεται στο σύστημα αρχείων **Learn more** Περισσότερα σχετικά με την προσωρινή μνήμη και τη βελτιστοποίηση της απόδοσης της διαδικασίας μετατροπής: [Αποθήκευση αποτελεσμάτων μετατροπής](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Δημιουργεί νέο αντικείμενο της κλάσης FileCache |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Εισάγει μια καταχώρηση στην προσωρινή μνήμη. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Αποκτά την καταχώρηση που συσχετίζεται με αυτό το κλειδί, εάν υπάρχει. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Επιστρέφει όλα τα κλειδιά που ταιριάζουν με το φίλτρο. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Δημιουργεί νέο αντικείμενο της κλάσης FileCache


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | cachePath | java.lang.String | Σχετική ή απόλυτη διαδρομή όπου θα αποθηκευτεί η προσωρινή μνήμη του εγγράφου |
|

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Εισάγει μια καταχώρηση στην προσωρινή μνήμη.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | κλειδί | java.lang.String | Ένα μοναδικό αναγνωριστικό για την καταχώρηση της προσωρινής μνήμης. |
|
|  | τιμή | java.lang.Object | Το αντικείμενο προς εισαγωγή. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Αποκτά την καταχώρηση που συσχετίζεται με αυτό το κλειδί, εάν υπάρχει.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | κλειδί | java.lang.String | Ένα κλειδί που αναγνωρίζει την ζητούμενη καταχώρηση. |
|

**Returns:**
java.lang.Object - Αντικείμενο εάν το κλειδί βρέθηκε ή αλλιώς null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Επιστρέφει όλα τα κλειδιά που ταιριάζουν με το φίλτρο.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | φίλτρο | java.lang.String | Το φίλτρο προς χρήση. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Κλειδιά που ταιριάζουν με το φίλτρο.

