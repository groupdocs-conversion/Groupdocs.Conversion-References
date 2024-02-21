---
title: Enumeration
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Generic enumeration class.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Generic enumeration class.

 TKey :
## Methods

| Method | Description |
| --- | --- |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Returns all enumeration values. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether two object instances are equal. |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Determines whether two object instances are equal. |
| [hashCode()](#hashCode--) | Serves as the default hash function. |
| [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Returns object by key. |
| [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Returns object by display name. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares current object to other. |
| [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Equality operator. |
| [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Inequality operator. |
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - String representation
### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Returns all enumeration values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Enumerable of the provided type

 T : Enumerated object type.
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
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Determines whether two object instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as the default hash function.

**Returns:**
int - A hash code for the current object.
### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Returns object by key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| value | java.lang.String | The value |

**Returns:**
T - The object
### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Returns object by display name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| displayName | java.lang.String | The display name |

**Returns:**
T - The object
### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Compares current object to other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The other object |

**Returns:**
int - zero if equal
### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Equality operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | The first object |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | The second object |

**Returns:**
boolean -  true  if objects are equal
### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Inequality operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | The first object |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | The second object |

**Returns:**
boolean -  true  if objects are not equal
