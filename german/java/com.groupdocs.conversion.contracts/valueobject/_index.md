---
title: "ValueObject"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Abstrakte Wertobjektklasse."
type: docs
weight: 15
url: /de/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Abstrakte Wertobjektklasse.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
|
|  | [hashCode()](#hashCode--) | Dient als Standard-Hashfunktion. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Gleichheitsoperator. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Ungleichheitsoperator. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


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

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Bestimmt, ob zwei Objektinstanzen gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. |
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

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Gleichheitsoperator.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Das erste Objekt |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Das zweite Objekt |
|

**Returns:**
boolean -  true  wenn Objekte gleich sind

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Ungleichheitsoperator.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Das erste Objekt |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Das zweite Objekt |
|

**Returns:**
boolean -  true  wenn Objekte nicht gleich sind

