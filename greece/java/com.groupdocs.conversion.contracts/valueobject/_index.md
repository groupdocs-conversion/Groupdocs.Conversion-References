---
title: "ValueObject"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αφηρημένη κλάση αντικειμένου τιμής."
type: docs
weight: 15
url: /el/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Αφηρημένη κλάση αντικειμένου τιμής.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα. |
|
|  | [hashCode()](#hashCode--) | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Τελεστής ισότητας. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Τελεστής ανισότητας. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Το αντικείμενο για σύγκριση με το τρέχον αντικείμενο. |
|

**Returns:**
boolean -  true  αν το συγκεκριμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο· διαφορετικά,  false .

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Το αντικείμενο για σύγκριση με το τρέχον αντικείμενο. |
|

**Returns:**
boolean -  true  αν το συγκεκριμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο· διαφορετικά,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού.


**Returns:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Τελεστής ισότητας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Το πρώτο αντικείμενο |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Το δεύτερο αντικείμενο |
|

**Returns:**
boolean -  true  αν τα αντικείμενα είναι ίσα

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Τελεστής ανισότητας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Το πρώτο αντικείμενο |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Το δεύτερο αντικείμενο |
|

**Returns:**
boolean -  true  αν τα αντικείμενα δεν είναι ίσα

