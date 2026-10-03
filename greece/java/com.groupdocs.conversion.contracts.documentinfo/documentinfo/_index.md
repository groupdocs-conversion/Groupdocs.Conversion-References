---
title: "DocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Παρέχει βασική υλοποίηση για την ανάκτηση πολυμορφικών πληροφοριών εγγράφου"
type: docs
weight: 16
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Παρέχει βασική υλοποίηση για την ανάκτηση πολυμορφικών πληροφοριών εγγράφου

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPropertyNames()](#getPropertyNames--) | {@inheritDoc} |
|
|  | [getProperty(String propertyName)](#getProperty-java.lang.String-) | {@inheritDoc} |
|
|  | [getPagesCount()](#getPagesCount--) | {@inheritDoc} |
|
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [getSize()](#getSize--) | {@inheritDoc} |
|
|  | [getCreationDate()](#getCreationDate--) | {@inheritDoc} |
|
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


Λίστα όλων των ιδιοτήτων που μπορούν να ληφθούν για τις τρέχουσες πληροφορίες εγγράφου


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Λάβετε την τιμή για μια ιδιότητα που παρέχεται ως κλειδί


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Αριθμός σελίδων εγγράφου.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Μορφή εγγράφου


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Μέγεθος εγγράφου σε bytes


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Ημερομηνία δημιουργίας εγγράφου


**Returns:**
java.util.Date
