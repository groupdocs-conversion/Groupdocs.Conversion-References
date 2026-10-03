---
title: "Απαρίθμηση"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Γενική κλάση απαρίθμησης."
type: docs
weight: 11
url: /el/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Γενική κλάση απαρίθμησης.


TKey
:

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Επιστρέφει όλες τις τιμές της απαρίθμησης. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα. |
|
|  | [hashCode()](#hashCode--) | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Επιστρέφει το αντικείμενο με βάση το κλειδί. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Επιστρέφει το αντικείμενο με βάση το όνομα εμφάνισης. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Τελεστής ισότητας. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Τελεστής ανισότητας. |
|
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.


**Returns:**
java.lang.String - Αναπαράσταση συμβολοσειράς

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Επιστρέφει όλες τις τιμές της απαρίθμησης.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Συλλογή του παρεχόμενου τύπου


T
: Απαριθμημένος τύπος αντικειμένου.

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

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Καθορίζει εάν δύο στιγμιότυπα αντικειμένου είναι ίσα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Το αντικείμενο για σύγκριση με το τρέχον αντικείμενο. |
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

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Επιστρέφει το αντικείμενο με βάση το κλειδί.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | τιμή | java.lang.String | Η τιμή |
|

**Returns:**
T - Το αντικείμενο

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Επιστρέφει το αντικείμενο με βάση το όνομα εμφάνισης.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | Το όνομα εμφάνισης |
|

**Returns:**
T - Το αντικείμενο

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Συγκρίνει το τρέχον αντικείμενο με άλλο.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Το άλλο αντικείμενο |
|

**Returns:**
int - μηδέν αν είναι ίσο

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Τελεστής ισότητας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Το πρώτο αντικείμενο |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Το δεύτερο αντικείμενο |
|

**Returns:**
boolean -  true  αν τα αντικείμενα είναι ίσα

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Τελεστής ανισότητας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Το πρώτο αντικείμενο |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Το δεύτερο αντικείμενο |
|

**Returns:**
boolean -  true  αν τα αντικείμενα δεν είναι ίσα

