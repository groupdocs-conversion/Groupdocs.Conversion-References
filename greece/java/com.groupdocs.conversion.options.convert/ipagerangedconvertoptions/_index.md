---
title: "IPageRangedConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές μετατροπής που υποστηρίζουν μετατροπή συγκεκριμένης λίστας σελίδων"
type: docs
weight: 52
url: /el/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Αντιπροσωπεύει τις επιλογές μετατροπής που υποστηρίζουν μετατροπή συγκεκριμένης λίστας σελίδων

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPages()](#getPages--) | Λαμβάνει τη λίστα των δεικτών σελίδων που θα μετατραπούν. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Ορίζει τη λίστα των δεικτών σελίδων που θα μετατραπούν. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Λαμβάνει τη λίστα των ευρετηρίων σελίδων που θα μετατραπούν. Πρέπει να καθοριστεί για τη μετατροπή συγκεκριμένων σελίδων.


**Returns:**
java.util.List<java.lang.Integer> - Η λίστα των δεικτών σελίδων που θα μετατραπούν. Θα πρέπει να καθοριστεί για μετατροπή συγκεκριμένων σελίδων.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Ορίζει τη λίστα των ευρετηρίων σελίδων που θα μετατραπούν. Πρέπει να καθοριστεί για τη μετατροπή συγκεκριμένων σελίδων.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | Η λίστα των δεικτών σελίδων που θα μετατραπούν. Θα πρέπει να καθοριστεί για μετατροπή συγκεκριμένων σελίδων. |
|

