---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο Cad."
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Επιλογές για μετατροπή σε τύπο Cad.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης.


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Λαμβάνει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Ορίζει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Λαμβάνει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Ορίζει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pagesCount | int |  |

