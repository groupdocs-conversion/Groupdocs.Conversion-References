---
title: "枚举"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "通用枚举类。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

通用枚举类。


TKey
:

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [toString()](#toString--) | 返回表示当前对象的字符串。 |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | 返回所有枚举值。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定两个对象实例是否相等。 |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | 确定两个对象实例是否相等。 |
|
|  | [hashCode()](#hashCode--) | 作为默认的哈希函数。 |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | 通过键返回对象。 |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | 通过显示名称返回对象。 |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | 比较当前对象与其他对象。 |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | 相等运算符。 |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | 不等运算符。 |
|
### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。


**Returns:**
java.lang.String - 字符串表示

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


返回所有枚举值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - 提供类型的可枚举集合


T
: 枚举对象类型。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定两个对象实例是否相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | obj | java.lang.Object | 用于与当前对象比较的对象。 |
|

**Returns:**
布尔型 - `true` 表示指定对象等于当前对象；否则为 `false`。

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


确定两个对象实例是否相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 用于与当前对象比较的对象。 |
|

**Returns:**
布尔型 - `true` 表示指定对象等于当前对象；否则为 `false`。

### hashCode() {#hashCode--}
```
public int hashCode()
```


作为默认的哈希函数。


**Returns:**
int - 当前对象的哈希码。

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


通过键返回对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | 值 | java.lang.String | 值 |
|

**Returns:**
T - 对象

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


通过显示名称返回对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | 显示名称 |
|

**Returns:**
T - 对象

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


比较当前对象与其他对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | obj | java.lang.Object | 另一个对象 |
|

**Returns:**
int - 如果相等则为零

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


相等运算符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 第一个对象 |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 第二个对象 |
|

**Returns:**
boolean -  true  如果对象相等

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


不等运算符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 第一个对象 |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 第二个对象 |
|

**Returns:**
boolean -  true  如果对象不相等

