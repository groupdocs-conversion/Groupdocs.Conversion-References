---
title: "FontSubstitute"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιγράφει την αντικατάσταση για ελλιπή γραμματοσειρά."
type: docs
weight: 12
url: /el/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Περιγράφει την αντικατάσταση για ελλιπή γραμματοσειρά.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Δημιουργήστε νέο ζεύγος αντικατάστασης γραμματοσειράς. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | Το αρχικό όνομα γραμματοσειράς. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | Το εναλλακτικό όνομα γραμματοσειράς. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Δημιουργήστε νέο ζεύγος αντικατάστασης γραμματοσειράς.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | originalFont | java.lang.String | Γραμματοσειρά από το πηγαίο έγγραφο. |
|
|  | substituteWith | java.lang.String | Γραμματοσειρά που θα χρησιμοποιηθεί για την αντικατάσταση του originalFont. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Το αρχικό όνομα γραμματοσειράς.


**Returns:**
java.lang.String - το αρχικό όνομα γραμματοσειράς.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


Το εναλλακτικό όνομα γραμματοσειράς.


**Returns:**
java.lang.String - το εναλλακτικό όνομα γραμματοσειράς.

