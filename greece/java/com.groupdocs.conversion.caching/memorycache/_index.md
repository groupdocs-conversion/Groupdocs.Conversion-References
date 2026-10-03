---
title: "MemoryCache"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Συμπεριφορά προσωρινής αποθήκευσης μνήμης."
type: docs
weight: 11
url: /el/java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Συμπεριφορά προσωρινής μνήμης. Σημαίνει ότι η προσωρινή μνήμη αποθηκεύεται στη μνήμη **Learn more** Περισσότερα σχετικά με την προσωρινή μνήμη και τη βελτιστοποίηση της απόδοσης της διαδικασίας μετατροπής: [Αποθήκευση αποτελεσμάτων μετατροπής](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [MemoryCache()](#MemoryCache--) | Δημιουργεί νέο αντικείμενο της κλάσης MemoryCache |
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
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


Δημιουργεί νέο αντικείμενο της κλάσης MemoryCache


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
java.lang.Object - Η εντοπισμένη τιμή ή null.

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

