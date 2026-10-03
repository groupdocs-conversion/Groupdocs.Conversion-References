---
title: "IPagedConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές μετατροπής που επιτρέπουν περιορισμό σελίδων καθορίζοντας τη σελίδα έναρξης και τον αριθμό σελίδων"
type: docs
weight: 55
url: /el/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Αντιπροσωπεύει τις επιλογές μετατροπής που επιτρέπουν περιορισμό σελίδων καθορίζοντας τη σελίδα έναρξης και τον αριθμό σελίδων

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Λαμβάνει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Ορίζει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή. |
|
|  | [getPagesCount()](#getPagesCount--) | Λαμβάνει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Ορίζει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Λαμβάνει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή.


**Returns:**
java.lang.Integer - Ο αριθμός σελίδας από τον οποίο ξεκινά η μετατροπή.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Ορίζει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | pageNumber | int | Ο αριθμός σελίδας από τον οποίο ξεκινά η μετατροπή. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Λαμβάνει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber.


**Returns:**
java.lang.Integer - Αριθμός σελίδων προς μετατροπή ξεκινώντας από PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Ορίζει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | pagesCount | int | Αριθμός σελίδων προς μετατροπή ξεκινώντας από PageNumber. |
|

