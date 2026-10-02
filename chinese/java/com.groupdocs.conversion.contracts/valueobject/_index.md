---
title: "ValueObject"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "抽象值对象类。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

抽象值对象类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定两个对象实例是否相等。 |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | 确定两个对象实例是否相等。 |
|
|  | [hashCode()](#hashCode--) | 作为默认的哈希函数。 |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | 相等运算符。 |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | 不等运算符。 |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


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

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


确定两个对象实例是否相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 用于与当前对象比较的对象。 |
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

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


相等运算符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 第一个对象 |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 第二个对象 |
|

**Returns:**
boolean -  true  如果对象相等

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


不等运算符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 第一个对象 |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 第二个对象 |
|

**Returns:**
boolean -  true  如果对象不相等

