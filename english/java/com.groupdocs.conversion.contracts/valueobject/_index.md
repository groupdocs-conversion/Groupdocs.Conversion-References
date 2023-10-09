---
title: ValueObject
second_title: GroupDocs.Conversion for Java API Reference
description: Abstract value object class.
type: docs
weight: 15
url: /java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Abstract value object class.
## Constructors

| Constructor | Description |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether two object instances are equal. |
| [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Determines whether two object instances are equal. |
| [hashCode()](#hashCode--) | Serves as the default hash function. |
| [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Equality operator. |
| [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Inequality operator. |
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether two object instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Determines whether two object instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as the default hash function.

**Returns:**
int - A hash code for the current object.
### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Equality operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | The first object |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | The second object |

**Returns:**
boolean -  true  if objects are equal
### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Inequality operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | The first object |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | The second object |

**Returns:**
boolean -  true  if objects are not equal
