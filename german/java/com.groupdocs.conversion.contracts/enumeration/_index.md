---
title: "Aufzählung"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Generische Aufzählungsklasse."
type: docs
weight: 11
url: /de/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Generische Aufzählungsklasse.


TKey
:

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [toString()](#toString--) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Gibt alle Enumerationswerte zurück. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
|
|  | [hashCode()](#hashCode--) | Dient als Standard-Hashfunktion. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Gibt das Objekt anhand des Schlüssels zurück. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Gibt das Objekt anhand des Anzeigenamens zurück. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | Vergleicht das aktuelle Objekt mit einem anderen. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Gleichheitsoperator. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Ungleichheitsoperator. |
|
### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.


**Returns:**
java.lang.String - Zeichenkettenrepräsentation

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Gibt alle Enumerationswerte zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Aufzählung des bereitgestellten Typs


T
: Aufgezählter Objekttyp.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob zwei Objektinstanzen gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. |
|

**Returns:**
boolean -  true  wenn das angegebene Objekt dem aktuellen Objekt gleich ist; andernfalls  false .

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Bestimmt, ob zwei Objektinstanzen gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. |
|

**Returns:**
boolean -  true  wenn das angegebene Objekt dem aktuellen Objekt gleich ist; andernfalls  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Standard-Hashfunktion.


**Returns:**
int - Ein Hashcode für das aktuelle Objekt.

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Gibt das Objekt anhand des Schlüssels zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | Wert | java.lang.String | Der Wert |
|

**Returns:**
T - Das Objekt

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Gibt das Objekt anhand des Anzeigenamens zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | Der Anzeigename |
|

**Returns:**
T - Das Objekt

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Vergleicht das aktuelle Objekt mit einem anderen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Das andere Objekt |
|

**Returns:**
int - 0, wenn gleich

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Gleichheitsoperator.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Das erste Objekt |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Das zweite Objekt |
|

**Returns:**
boolean -  true  wenn Objekte gleich sind

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Ungleichheitsoperator.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Das erste Objekt |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Das zweite Objekt |
|

**Returns:**
boolean -  true  wenn Objekte nicht gleich sind

